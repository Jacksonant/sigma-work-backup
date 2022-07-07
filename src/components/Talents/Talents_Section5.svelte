<script>
    export let payload={
      title: "",
      description: ""
    }
</script>

<div class="rating-section bg-primary-1">
    <div class="main-container">
      <div class="container wide top-layer">
        <h1 class="display-heading-2 text-white">{payload.title}</h1>
        <p>{payload.description}</p>
        <a href="" class="button large w-inline-block">
            <div>Get Started</div>
        </a>
      </div>
    </div>
</div>
