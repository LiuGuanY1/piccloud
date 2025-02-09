<template>
  <section class="p-5 bg-dark" style="width: 100vw; height: 90vh; display: flex; justify-content: center; align-items: center;">
    <div class="p-4 bg-light" style="border-radius: 10px; width: 100%; max-height: 80vh; overflow: auto;">
      <div class="container mt-5 text-center">
        <ul class="nav nav-pills mb-3" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link" :class="{ active: activeTab === 'android' }" id="android-tab"
              @click="handleTabClick('android')" type="button" role="tab" aria-controls="android" aria-selected="true"
              :style="{ backgroundColor: activeTab === 'android'? '#6375FF' : 'transparent' }">
              Android
            </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" :class="{ active: activeTab === 'ios' }" id="ios-tab"
              @click="handleTabClick('ios')" type="button" role="tab" aria-controls="ios" aria-selected="false"
              :style="{ backgroundColor: activeTab === 'ios'? '#6375FF' : 'transparent' }">
              iOS
            </button>
          </li>
        </ul>
        <section class="p-5" style="background-color: #6375FF; border-radius: 10px; max-height: 60vh; overflow: auto;">
          <!-- 选项卡内容 -->
          <div class="tab-content" id="myTabContent">
            <!-- Android 选项卡内容 -->
            <div class="tab-pane fade" :class="{ show: activeTab === 'android', active: activeTab === 'android' }"
              id="android" role="tabpanel" aria-labelledby="android-tab">
              <div class="row align-items-center justify-content-between">
                <div class="col-md p-5">
                  <!-- 修改按钮类名 -->
                  <a href="https://mp-52a185d0-9d2e-4968-af9b-07db381d8ec8.cdn.bspapp.com/__UNI__D654B50__20250208224316.apk.1" class="btn bg-dark text-warning">
                    <!-- 这里可以写按钮上显示的文字 -->
                    下载 Android APK
                  </a>
                </div>
                <div class="col-md">
                  <img src="../components/icons/download_img.svg" alt="Android Logo" width="300">
                </div>
              </div>
            </div>
            <!-- iOS 选项卡内容 -->
            <div class="tab-pane fade" :class="{ show: activeTab === 'ios', active: activeTab === 'ios' }" id="ios"
              role="tabpanel" aria-labelledby="ios-tab">
              <div class="row align-items-center justify-content-between">
                <div class="col-md p-5">
                  <!-- 修改按钮类名 -->
                  <button class="btn bg-dark text-warning">下载 ios app</button>
                </div>
                <div class="col-md">
                  <img src="../components/icons/download_img.svg" alt="Android Logo" width="300">
                </div>
              </div>
            </div>
          </div>
        </section>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      activeTab: 'android'
    };
  },
  methods: {
    handleTabClick(tab) {
      this.activeTab = tab;
    }
  }
};
</script>

<style>
/* 媒体查询，针对小屏幕设备 */
@media (max-width: 768px) {
  .p-5 {
    padding: 20px !important;
  }
  .col-md {
    padding: 10px !important;
  }
  img {
    width: 100%;
    max-width: 200px;
  }
}
</style>