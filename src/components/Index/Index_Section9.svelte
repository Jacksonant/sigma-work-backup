<script>
    export let payload={
      img1: "",
      img2: "",
      talent_link: "",
      employer_link: ""

    }
</script>

<div class="section no-top-padding bg-primary-4 wf-section">
    <div class="main-container narrow">
      <div class="container-large wide align-center" />
      <div class="w-layout-grid card-grid-halves">
        <div
          id="w-node-_8dd7e4ae-ad6b-292e-9cb9-46419229042e-afd984ac"
          class="container card-container"
        >
          <img
            src="./Optic - Webflow HTML Website Template_files/5f0fa0e1ee20ce60b4425a49_landscape-03.jpg"
            srcset={payload.img1}
            sizes="(max-width: 479px) 91vw, (max-width: 767px) 88vw, 497px"
            alt=""
          />
          <div class="card-body border-bottom">
            <h4 class="large-heading">Talent</h4>
            <p>
              
            </p>
            <a
              href={payload.talent_link}
              class="button bg-primary-3 w-inline-block"
            >
              <div>Visit the page</div>
            </a>
          </div>
        </div>
        <div
          id="w-node-a58986c9-be44-adf7-0389-e2709379f357-afd984ac"
          class="container card-container"
        >
          <img
            src="./Optic - Webflow HTML Website Template_files/5f0fa0e15d293a96bd61006c_landscape-02.jpg"
            srcset={payload.img2}
            sizes="(max-width: 479px) 91vw, (max-width: 767px) 88vw, 497px"
            alt=""
          />
          <div class="card-body border-bottom border-primary-2">
            <h4 class="large-heading">Employer</h4>
            <p>
             
            </p>
            <a
              href={payload.employer_link}
              class="button bg-primary-2 w-inline-block"
            >
              <div>Visit the page</div>
            </a>
          </div>
        </div>
      </div>
    </div>
</div>
