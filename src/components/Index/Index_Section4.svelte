<script>
    export let payload={
      title: "",
      description: "",
      img: ""
      }
</script>

<div class="section reduced-bottom-padding bg-primary-4" >
    <div class="main-container">
      <div class="w-layout-grid grid-halves">
        <div class="container align-center">
          <h4 class="large-heading">{payload.title}</h4>
          <div>{payload.description}</div>
        </div>
        <div class="portrait-image-container">
          <div class="portrait-image-bg bg-primary-3"></div>
          <div class="blurred-image-container landscape"><img
              src="{payload.img}"
              srcset="https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e15d293a96bd61006c_landscape-02-p-1080.jpeg 1080w, https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e15d293a96bd61006c_landscape-02.jpg 1220w"
              sizes="(max-width: 479px) 91vw, (max-width: 767px) 88vw, (max-width: 991px) 572px, 91vw" alt=""
              class="focussed-image"><img
              src="{payload.img}"
              srcset="https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e15d293a96bd61006c_landscape-02-p-1080.jpeg 1080w, https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e15d293a96bd61006c_landscape-02.jpg 1220w"
              sizes="(max-width: 479px) 91vw, (max-width: 767px) 88vw, (max-width: 991px) 572px, 91vw" alt=""
              class="blurred-image">
            <div class="overlay-bottom-right"><a href="./employers"
                class="w-inline-block w-lightbox">
                <div class="square-button bg-white"><img
                    src="./Optic - Webflow HTML Website Template_files/5f0cff2d4a0b1c40c419792a_Video Play Icon.svg"
                    alt="">
                  <div class="icon-button-text">For Employers</div>
                </div>
              </a></div>
          </div>
        </div>
      </div>
    </div>
</div>