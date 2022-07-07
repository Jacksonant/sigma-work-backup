<script>
    export let payload={
      title: "",
      card1_title: "",
      card2_title: "",
      card3_title: "",
      card4_title: "",
      card1_description: "",
      card2_description: "",
      card3_description: "",
      card4_description: "",
      img: ""
    }
</script>

<div class="section bg-primary-1">
    <div class="main-container">
      <div class="w-layout-grid grid-halves">
        <div class="container align-center">
          <div class="section-heading">
            <h3 class="display-heading-2 text-white no-bottom-margin">{payload.title}</h3>
          </div>
          <div class="w-layout-grid vertical-text-grid">
            <div>
              <h4 class="text-white">{payload.card1_title}</h4>
              <div>{payload.card1_description}</div>
            </div>
            <div>
              <h4 class="text-white">{payload.card2_title}</h4>
              <div>{payload.card2_description}</div>
            </div>
            <div>
              <h4 class="text-white">{payload.card3_title}</h4>
              <div>{payload.card3_description}</div>
            </div>
            <div>
                <h4 class="text-white">{payload.card4_title}</h4>
                <div>{payload.card4_description}</div>
            </div>
          </div>
        </div>
        <div id="w-node-da199a86-e56e-7936-fbcc-482df5b10b60-8930f3e0" class="container align-center">
          <div class="portrait-image-container">
            <div class="portrait-image-bg bg-primary-3"></div>
            <div class="blurred-image-container"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fa0e2261e39aa24e26d92_Portrait-04.jpg"
                srcset={payload.img}
                sizes="(max-width: 479px) 91vw, (max-width: 767px) 334px, 418px" alt=""
                class="portrait-image focussed-image"></div>
          </div>
        </div>
      </div>
    </div>
</div>