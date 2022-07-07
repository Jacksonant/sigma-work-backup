<script>
    export let payload={
      title: "",
      btn_link: ""
    }
</script>

<div class="cta-section bg-primary-1">
    <div class="cta bg-primary-3">
      <div class="cta-content">
        <h3 class="large-heading cta-heading">{payload.title}</h3>
        <div class="cta-button-container"><a href={payload.btn_link}
            class="button large bg-white w-inline-block">
            <div>Browse jobs</div>
          </a></div>
      </div>
      <div class="cta-decoration">
        <div class="decoration-bg bg-primary-4 round-top-left"></div>
        <div class="decoration-tall-inner bg-primary-5 round-top-right"></div>
      </div>
    </div>
    <div class="main-container"></div>
</div>