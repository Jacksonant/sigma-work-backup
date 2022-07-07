<script>
    export let payload={
      title: '',
      description: ''
    }
</script>

<div class="grid-halves-section wf-section">
    <div class="grid-section-half bg-primary-4">
      <div class="container">
        <div
          data-w-id="bd589181-9d04-1900-2d6d-6f01da1c4af6"
          style="opacity: 1;"
          class="grid-text-content"
        >
          <h1 class="display-heading-1">{payload.title}</h1>
          <p class="text-large">
            {payload.description}
          </p>
          <a
            href=""
            class="button large w-inline-block"
          >
            <div>Get Started</div>
          </a>
        </div>
      </div>
    </div>
    <div class="grid-section-half bg-primary-3">
      <img
        src="./Optic - Webflow HTML Website Template_files/5f110f989c0b89ec54791a50_Interface-01.png"
        width="473"
        srcset="https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f110f989c0b89ec54791a50_Interface-01-p-500.png 500w, https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f110f989c0b89ec54791a50_Interface-01-p-800.png 800w, https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f110f989c0b89ec54791a50_Interface-01.png 946w"
        sizes="(max-width: 479px) 88vw, (max-width: 767px) 85vw, (max-width: 991px) 473px, 43vw"
        alt=""
        class="top-layer"
      />
      <div
        class="interface-screenshot-decoration bg-primary-5 round-bottom-right"
      />
    </div>
</div>