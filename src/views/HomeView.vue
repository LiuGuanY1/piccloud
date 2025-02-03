<template>


  <section class="p-5 bg-dark text-light text-center text-sm-start">
    <div class="container">
      <div class="d-flex">
        <div>
          <h1>影云:<span class="text-warning">管理你的数字影像世界</span></h1>
          <p class="my-4">
            在数字化时代，我们的生活中充斥着大量的图片，如何高效地管理这些珍贵的回忆和重要的资料成为了一个挑战。影云图片管理系统应运而生，它是一款功能强大、操作便捷的图片管理工具，为用户提供一站式的图片管理解决方案。
          </p>
          <button class="btn btn-lg" style="background-color: #6375FF;">了解更多</button>
        </div>
        <img src="../components/icons/4.svg" alt="img" class="w-50 d-none d-md-block">
      </div>
    </div>
  </section>



  <section class="p-5" style="background-color: #6375FF;">
    <div class="container">
      <div class="row g-4">
        <div class="col-md">
          <div class="card bg-dark text-light">
            <div class="card-body text-center">
              <div class="card-title text-warning">
                前端：流畅交互，多端适配
              </div>
              <div class="card-text">
                前端注重用户体验，PC 端界面精美，兼容主流浏览器且适配各类分辨率；移动端涵盖安卓、小程序和
                iOS，支持扫码、定位，适配不同设备。支持多端快速上传图片，查看时可进行裁剪、旋转等操作，界面简洁易上手。此外，还支持第三方接口调用，以数据可视化形式展示图片相关信息，助力轻松管理图片库
              </div>
              <a href="#" class="btn btn-primary mt-2">了解更多</a>
            </div>
          </div>
        </div>
        <div class="col-md">
          <div class="card bg-secondary text-light">
            <div class="card-body text-center">
              <div class="card-title  text-warning">
                后端：高效稳定，智能管理
              </div>
              <div class="card-text">
                后端为系统稳定运行提供有力保障。具备高并发后端接口，可应对大量请求，即使高负载也能稳定流畅运行。集成性能监控、定时任务等功能，方便系统管理，支持 AI 接入拓展智能化功能。数据管理规范，通过 Git
                进行版本控制，系统部署于 Docker 环境，扩展性强，存储功能确保数据完整一致
              </div>
              <a href="#" class="btn btn-dark mt-2">了解更多</a>
            </div>
          </div>
        </div>
        <div class="col-md">
          <div class="card bg-dark text-light">
            <div class="card-body text-center">
              <div class="card-title  text-warning">
                AI：智能驱动，创新管理
              </div>
              <div class="card-text">
                AI 技术深度融入影云项目，实现智能图片管理。通过 AI 算法自动为图片分类、添加标签，支持多维度搜索，快速找到目标图片。利用 AI
                自动检测并删除违规图片，保证图片库内容合规。同时，能依据图片内容自动命名，让文件名更规范，并优化图片参数提升质量，带来更智能的图片管理体验
              </div>
              <a href="#" class="btn btn-primary mt-2">了解更多</a>
            </div>
          </div>
        </div>
      </div>
    </div>

  </section>

  <section class="p-5">
    <div class="container">
      <div class="row align-items-center justify-content-between">
        <div class="col-md">
          <img src="../components/icons/5.svg" alt="img" class="img-fluid">
        </div>
        <div class="col-md p-5">
          <h2 class="text-warning">满足多种功能性需求</h2>
          <p class="lead text-info">影云项目涵盖丰富且实用的功能模块</p>
          <p>用户管理方面，具备完善的用户注册、登录流程，同时通过身份认证与权限控制，保障用户数据的安全与隐私。图片上传与查看功能便捷高效，支持移动端和 PC
            端上传，用户还能对图片进行查看、裁剪、旋转等操作。图片搜索功能强大，可基于时间、地理位置和标签等多维度进行搜索，让用户能快速精准定位所需图片。图片内容过滤功能会自动检测并删除不符合规定的图片，维护图片库的健康与合规。图片分类管理支持文件夹、标签及多级目录结构，方便用户对图片进行有序整理。智能命名与批量重命名功能，可按照智能规则自动命名或批量重命名文件，提升管理效率。此外，图像元数据管理能存储并展示图片的
            EXIF 数据，如拍摄日期、相机型号等，为用户提供更详细的图片信息。</p>
          <a href="" class="btn btn-dark">查看更多</a>
        </div>
      </div>
    </div>
  </section>

  <section class="p-5 bg-dark text-light">
    <div class="container">
      <div class="row align-items-center justify-content-between">
        <div class="col-md p-5">
          <h2 class="text-warning">实现多种非功能性需求</h2>
          <p class="lead text-info">影云项目在各端表现出色</p>
          <p>PC 端界面设计美观，兼容 Chrome、Firefox、Edge 等主流浏览器，能适应不同分辨率，同时支持第三方接口调用和数据可视化，增强了系统的扩展性与数据展示能力。移动端兼容安卓、小程序和 iOS
            系统，支持扫码、定位等实用功能，且适配不同品牌和型号的设备，让用户随时随地都能便捷管理图片。服务器提供高并发的后端接口，保障系统在大量用户同时访问时的稳定运行，还支持性能监控、定时任务、AI 接入等功能，并部署在
            Docker 环境中，便于系统的部署与维护。数据库设计符合相关规范，实现了存储过程和游标等功能，确保数据的完整性与一致性。在代码管理上，所有代码、数据库备份等均通过 Git
            进行管理，且遵循严格的代码规范，保证了代码的质量与可维护性。</p>
          <a href="" class="btn btn-light">查看更多</a>
        </div>
        <div class="col-md">
          <img src="../components/icons/6.svg" alt="img" class="img-fluid">
        </div>
      </div>
    </div>
  </section>

  <section class="p-5">
    <div class="container">
      <h2 class="text-center">常见问题</h2>
      <div class="accordion accordion-flush" id="accordionFlushExample">
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
              忘记密码
            </button>
          </h2>
          <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne"
            data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">
              请联系我们
            </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
              系统性能与兼容性问题
            </button>
          </h2>
          <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo"
            data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">
              请联系我们
            </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingThree">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
              数据安全与隐私问题
            </button>
          </h2>
          <div id="flush-collapseThree" class="accordion-collapse collapse" aria-labelledby="flush-headingThree"
            data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">
              请联系我们
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="p-5" style="background-color: #6375FF;">
    <div class="container">
      <h2 class="text-center text-light">人员分工</h2>
      <p class="lead text-center mb-5 text-warning">
        感谢这些开发者做出的贡献
      </p>
      <div class="row g-4">
        <div class="col-md-4 col-lg-2">
          <div class="card bg-light">
            <div class="card-body text-center">
              <img src="../components/icons/2.svg" alt="img" class="mb-3 rounded-circle img-fluid small-img">
              <h3 class="card-title">蔡明辰</h3>
              <p class="card-text">后端AI</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-lg-2">
          <div class="card bg-light">
            <div class="card-body text-center">
              <img src="../components/icons/2.svg" alt="img" class="mb-3 rounded-circle img-fluid small-img">
              <h3 class="card-title">张行</h3>
              <p class="card-text">后端数据库</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-lg-2">
          <div class="card bg-light">
            <div class="card-body text-center">
              <img src="../components/icons/2.svg" alt="img" class="mb-3 rounded-circle img-fluid small-img">
              <h3 class="card-title">李灿</h3>
              <p class="card-text">后端数据库</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-lg-2">
          <div class="card bg-light">
            <div class="card-body text-center">
              <img src="../components/icons/2.svg" alt="img" class="mb-3 rounded-circle img-fluid small-img">
              <h3 class="card-title">唐嘉俊</h3>
              <p class="card-text">前端手机端</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-lg-2">
          <div class="card bg-light">
            <div class="card-body text-center">
              <img src="../components/icons/2.svg" alt="img" class="mb-3 rounded-circle img-fluid small-img">
              <h3 class="card-title">施志鸿</h3>
              <p class="card-text">前端手机端</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-lg-2">
          <div class="card bg-light">
            <div class="card-body text-center">
              <img src="../components/icons/2.svg" alt="img" class="mb-3 rounded-circle img-fluid small-img">
              <h3 class="card-title">李星呈</h3>
              <p class="card-text">前端web端</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="p-5">
    <div class="container">
      <h2 class="text-center mb-4">联系我们</h2>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">电话：123</li>
        <li class="list-group-item">邮箱：123</li>
        <li class="list-group-item">地址：123</li>

      </ul>
    </div>
  </section>

  <footer class="p-5 bg-dark text-white text-center">
    <div class="containter">
      <p class="lead">Copyright &copy; 2025 Piccloud</p>
    </div>
  </footer>
</template>


<script>

</script>

<style>
@media(min-width:768px) {
  .news-input {
    width: 50%;
  }
}

.small-img {
  width: 50%;
}

.smaller-img {
  width: 15%;
}

body::before {
  display: block;
  content: '';
  height: 60px;
}
</style>
