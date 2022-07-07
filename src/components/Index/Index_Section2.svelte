<script>
    export let payload={
      strong_word1: "",
      strong_word2: "",
      strong_word3: "",
      description1: "",
      description2: "",
      description3: ""
    }
</script>

<div class="section reduced-padding">
    <div class="main-container">
      <div class="w-layout-grid horizontal-icon-thirds">
        <div class="horizontal-icon-large"><img
            src="./Optic - Webflow HTML Website Template_files/5f0fb077426c0142e96eb483_icon-security-cameras.svg"
            alt="" class="horizontal-icon-large-image">
          <div><strong>{payload.strong_word1}</strong> {payload.description1}</div>
        </div>
        <div class="horizontal-icon-large"><img
            src="./Optic - Webflow HTML Website Template_files/5f0fb077c82800fc90146aa8_icon-show-password.svg" alt=""
            class="horizontal-icon-large-image">
          <div><strong>{payload.strong_word2}</strong> {payload.description2}</div>
        </div>
        <div class="horizontal-icon-large"><img
            src="./Optic - Webflow HTML Website Template_files/5f0fb077b345c7508abea8eb_icon-web-design.svg" alt=""
            class="horizontal-icon-large-image">
          <div><strong>{payload.strong_word3}</strong> {payload.description3}</div>
        </div>
      </div>
    </div>
</div>