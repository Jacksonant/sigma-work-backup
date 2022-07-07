<script>
    export let payload={

    }
</script>

<div class="section bg-primary-4">
    <div class="main-container">
        <div class="w-layout-grid grid-halves reverse-direction">

            <div class="container align-center">
                <div class="section-heading">
                    <h4 class="large-heading">Register here</h4>
                    <!-- <div class="text-large">Use these handy action cards to help direct users around your site.
                    </div> -->
                </div>
                <div class="form-block w-form">
                    <form id="email-form" name="email-form" data-name="Email Form" class="form-grid-vertical">
                        <div><label for="First-Name">First Name <span class="text-red">*</span></label><input
                                type="text" class="form-input w-input" maxlength="256" name="First-Name"
                                data-name="First Name" placeholder="" id="First-Name" required=""></div>
                        <div><label for="Last-Name">Last Name</label><input type="text" class="form-input w-input"
                                maxlength="256" name="Last-Name" data-name="Last Name" placeholder=""
                                id="Last-Name"></div>
                        <div><label for="Phone">Phone Number</label><input type="tel" class="form-input w-input"
                                maxlength="256" name="Phone" data-name="Phone" placeholder="" id="Phone"></div>
                        <div><label for="email">Email Address <span class="text-red">*</span></label><input
                                type="email" class="form-input w-input" maxlength="256" name="email"
                                data-name="Email" placeholder="" id="email" required=""></div>
                        
                        <a href='./signup-employers'><input type="submit" value="Get Started" data-wait="Please wait..."
                                id="w-node-f065cde2-d5a0-2588-f727-f93b87c82880-16dc1696" class="button w-button"></a>

                        
                    </form>
                    <div class="form-success w-form-done">
                        <div>Thank you! Your submission has been received!</div>
                    </div>
                    <div class="form-error w-form-fail">
                        <div>Oops! Something went wrong while submitting the form.</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>