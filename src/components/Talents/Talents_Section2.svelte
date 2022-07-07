<script>
    export let payload={
      title: "",
      description: "",
      card1: "",
      card2: "",
      card3: "",
      img: "",
      img_caption: ""

    }
</script>

<div class="section no-bottom-padding"  style="margin-bottom: 100px;">
    <div class="main-container">
      <div class="w-layout-grid grid-halves">
        <div id="w-node-_077b8c0b-df57-30b5-1e1c-8dfde2961b72-8930f3e0" class="container">
          <div class="portrait-image-container align-content-right">
            <div class="portrait-image-bg left bg-primary-3"></div>
            <div class="blurred-image-container"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fa0e2057709539468ff6a_Portrait-02.jpg"
                srcset={payload.img}
                sizes="(max-width: 479px) 91vw, (max-width: 767px) 334px, 418px" alt=""
                class="portrait-image blurred-image"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fa0e2057709539468ff6a_Portrait-02.jpg"
                srcset={payload.img}
                sizes="(max-width: 479px) 91vw, (max-width: 767px) 334px, 418px" alt=""
                class="portrait-image focussed-image"></div>
            <div class="portrait-image-overlay left">
              <div class="padded-text">
                <div class="text-small">{payload.img_caption}
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="container">
          <h4 class="large-heading">{payload.title}</h4>
          <p>{payload.description}</p>
          <div class="w-layout-grid vertical-icon-grid">
            <div class="horizontal-icon padded-large"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fb0771fc43a104975889a_icon-voice-id.svg" alt=""
                class="horizontal-icon">
              <h5 class="no-bottom-margin">{payload.card1}</h5>
            </div>
            <div class="horizontal-icon padded-large"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fb077426c0142e96eb483_icon-security-cameras.svg"
                alt="" class="horizontal-icon">
              <h5 class="no-bottom-margin">{payload.card2}</h5>
            </div>
            <div class="horizontal-icon padded-large"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fb077426c0142e96eb483_icon-security-cameras.svg"
                alt="" class="horizontal-icon">
              <h5 class="no-bottom-margin">{payload.card3}</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
</div>