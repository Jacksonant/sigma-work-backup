<script>
    export let payload={
      title: "",
      card1_title: "",
      card2_title: "",
      card3_title: "",
      card4_title: "",
      card5_title: "",
      card6_title: "",
      card1_description: "",
      card2_description: "",
      card3_description: "",
      card4_description: "",
      card5_description: "",
      card6_description: ""
    }
</script>

<div class="section">
    <div class="decoration-tall top-left">
      <div class="decoration-bg bg-primary-1 round-bottom-right"></div>
      <div class="decoration-tall-inner bg-primary-5 round-bottom-left"></div>
    </div>
    <div class="main-container narrow">
      <div class="horizontal-title">
        <div class="text">{payload.title}</div>
        <div class="title-line"></div>
      </div>
      <div class="w-layout-grid icons-grid">
        <div class="icons-grid-item centered"><img
            src="./Optic - Webflow HTML Website Template_files/5f0fb077426c0142e96eb483_icon-security-cameras.svg"
            alt="" class="icons-grid-image">
          <h4>{payload.card1_title}</h4>
          <div>{payload.card1_description}</div>
        </div>
        <div class="icons-grid-item centered"><img
            src="./Optic - Webflow HTML Website Template_files/5f0fb076c8280018f4146aa7_icon-multicultural-people.svg"
            alt="" class="icons-grid-image">
          <h4>{payload.card2_title}</h4>
          <div>{payload.card2_description}</div>
        </div>
        <div class="icons-grid-item centered"><img
            src="./Optic - Webflow HTML Website Template_files/5f0fb0771fc43a104975889a_icon-voice-id.svg" alt=""
            class="icons-grid-image">
          <h4>{payload.card3_title}</h4>
          <div>{payload.card3_description}</div>
        </div>
        <div class="icons-grid-item centered"><img
            src="./Optic - Webflow HTML Website Template_files/5f0fb0775f3755380dd02537_icon-passport.svg" alt=""
            class="icons-grid-image">
          <h4>{payload.card4_title}</h4>
          <div>{payload.card4_description}</div>
        </div>
        <div class="icons-grid-item centered"><img
            src="./Optic - Webflow HTML Website Template_files/5f0fb0771fc43a104975889a_icon-voice-id.svg" alt=""
            class="icons-grid-image">
          <h4>{payload.card5_title}</h4>
          <div>{payload.card5_description}</div>
        </div>
        <div class="icons-grid-item centered"><img
            src="./Optic - Webflow HTML Website Template_files/5f0fb0775f3755380dd02537_icon-passport.svg" alt=""
            class="icons-grid-image">
          <h4>{payload.card6_title}</h4>
          <div>{payload.card6_description}</div>
        </div>
      </div>
    </div>
</div>