<script>
    export let payload={
      title: "",
      description: ""
    }
</script>

<div class="section bg-primary-1">
    <div class="main-container top-layer">
      <div class="w-layout-grid grid-halves">
        <div class="grid-text-content">
          <div class="container align-center">
            <h1 class="display-heading-1 text-white">{payload.title}</h1>
            <p class="text-large">{payload.description}</p>
          </div>
        </div>
        <div class="container align-center">
          <div class="hero-form-container shadow">
            <div class="form-block w-form">
              <form id="wf-form-Sign-Up-Form" name="wf-form-Sign-Up-Form" data-name="Sign Up Form"
                class="form-grid-vertical">
                <!-- <div class="label-form"><label for="name">First Name</label> <label for="name">Last Name</label></div> -->
                <div class="name-form" ><label style="width:246px" for="firstname">First Name</label>  
                    <input type="text" class="form-input w-input" maxlength="256"
                    name="firstname" data-name="FirstName" placeholder="" id="firstname">
                </div><div><label style="left: 0;" for="lastname">Last Name</label>
                    <input type="text" class="form-input w-input" maxlength="256"
                    name="lastname" data-name="LastName" placeholder="" id="lastname"></div>
                <div><label for="phone">Phone Number</label><input type="tel" class="form-input w-input"
                    maxlength="256" name="phone" data-name="Phone" placeholder="" id="phone" required=""></div>
                <div><label for="email">Email Address</label><input type="email" class="form-input w-input"
                    maxlength="256" name="email" data-name="Email" placeholder="" id="email" required=""></div>
                <a href="./signup-talents"><input type="submit" value="Get Started" data-wait="Please wait..." class="button w-button"></a>
              </form>
              <div class="w-form-done">
                <div>Thank you! Your submission has been received!</div>
              </div>
              <div class="w-form-fail">
                <div>Oops! Something went wrong while submitting the form.</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="hero-form-decoration">
      <div class="decoration-bg bg-primary-3 round-top-left"></div>
      <div class="decoration-tall-inner bg-primary-5 round-top-right"></div>
    </div>
</div>

