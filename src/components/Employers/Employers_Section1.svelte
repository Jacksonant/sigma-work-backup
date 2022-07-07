<script>
    export let payload={
      title: "",
      description: "",
      img: ""
    }
</script>

<div class="section no-bottom-padding bg-primary-4">
    <div class="main-container">
      <div class="w-layout-grid grid-halves">
        <div data-w-id="e8de6537-6ce7-5962-0e6b-6cf4552f522d" style="opacity: 1;" class="grid-text-content">
          <h1 class="display-heading-1">{payload.title}</h1>
          <p class="text-large">{payload.description}</p>
          <a href="#email-form"
            class="button large w-inline-block">
            <div>Get Started</div>
          </a>
          <!-- <div class="hero-reviews">
            <div class="stars"><img
                src="./Optic - Webflow HTML Website Template_files/5f0cff2d03a8674725eea78f_icon-star.svg" alt=""><img
                src="./Optic - Webflow HTML Website Template_files/5f0cff2d03a8674725eea78f_icon-star.svg" alt=""><img
                src="./Optic - Webflow HTML Website Template_files/5f0cff2d03a8674725eea78f_icon-star.svg" alt=""><img
                src="./Optic - Webflow HTML Website Template_files/5f0cff2d03a8674725eea78f_icon-star.svg" alt=""><img
                src="./Optic - Webflow HTML Website Template_files/5f0cff2d03a8674725eea78f_icon-star.svg" alt=""></div>
            <div>Average rating of 4.89/5 on Trustpilot</div>
          </div> -->
        </div>
        <div id="w-node-e8de6537-6ce7-5962-0e6b-6cf4552f523e-65b9c6e9" class="container">
          <div class="portrait-image-container">
            <div class="portrait-image-bg bg-primary-3"></div>
            <div class="blurred-image-container"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fa0e2c295be7ce2d09969_Portrait-06.jpg"
                srcset= {payload.img}
                sizes="(max-width: 479px) 91vw, (max-width: 767px) 334px, 418px" alt=""
                class="portrait-image blurred-image"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fa0e2c295be7ce2d09969_Portrait-06.jpg"
                srcset= {payload.img}
                sizes="(max-width: 479px) 91vw, (max-width: 767px) 334px, 418px" alt=""
                class="portrait-image focussed-image"></div>
            <div class="portrait-image-overlay">
              <div class="w-layout-grid vertical-icon-grid">
                <div class="horizontal-icon padded"><img
                    src="./Optic - Webflow HTML Website Template_files/5f0fb077426c0142e96eb483_icon-security-cameras.svg"
                    alt="" class="icon-small horizontal-icon">
                  <div>Vetted candidates</div>
                </div>
                <div class="horizontal-icon padded"><img
                    src="./Optic - Webflow HTML Website Template_files/5f0fb077b345c7508abea8eb_icon-web-design.svg"
                    alt="" class="icon-small horizontal-icon">
                  <div>Proven skills</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</div>

