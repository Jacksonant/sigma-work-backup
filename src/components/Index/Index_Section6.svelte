<script>
    export let payload={
      logo1: "",
      logo2: "",
      logo3: "",
      logo4: ""
    }
</script>

<div class="section top-padding-small">
    <div class="main-container">
      <div class="logo-row-title">
        <div class="text-muted">Trusted by the world’s fastest growing companies including:</div>
      </div>
      <div class="logo-row"><img
          src={payload.logo1} alt=""
          class="logo-row-item"><img
          src={payload.logo2} alt=""
          class="logo-row-item">
          <img 
          src={payload.logo3} alt=""
          class="logo-row-item size:0.1" >
          <img 
          src={payload.logo4} alt=""
          class="logo-row-item"></div>
    </div>
</div>