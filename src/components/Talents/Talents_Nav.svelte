<script>
    export let payload={
        main_page: " ",
        employers_page: " ",
        talents_page: " ",
        about_page: " ",
        jobs_page: " ",
        mainpage_link: "",
        employerspage_link: "",
        talentspage_link: "",
        aboutpage_link: "",
        jobspage_link: ""
    }
</script>

<div class="navbar-container sticky-top bg-primary-1">
    <div class="main-container navbar-container">
        <div data-collapse="medium" data-animation="default" data-duration="400" data-easing="ease"
            data-easing2="ease" role="banner" class="navbar w-nav">
            <div class="navbar-row">   
                <a href="/"
                    class="mobile-brand w-nav-brand"><a href={payload.mainpage_link}
                    class="nav-link text-white w-nav-link">{payload.main_page}</a></a>
                <nav role="navigation" class="nav-menu-wide w-nav-menu" style="transform: translateY(0px) translateX(0px);"><a href="/"
                        class="desktop-brand w-nav-brand"><a href={payload.mainpage_link}
                        class="nav-link text-white w-nav-link">{payload.main_page}</a></a>
                    <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                        <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-0"
                            aria-controls="w-dropdown-list-0" aria-haspopup="menu" aria-expanded="false"
                            role="button" tabindex="0">
                            <a href={payload.employerspage_link}>
                            <div class="text-white">{payload.employers_page}</div></a><img
                                src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                                alt="" class="dropdown-arrow">
                        </div>
                    </div>
                    <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                        <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-1"
                            aria-controls="w-dropdown-list-1" aria-haspopup="menu" aria-expanded="false"
                            role="button" tabindex="0">
                            <a href={payload.talentspage_link}><div class="text-white">{payload.talents_page}</div></a><img
                                src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                                alt="" class="dropdown-arrow">
                        </div>
                    </div>
                    <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                        <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-2"
                            aria-controls="w-dropdown-list-2" aria-haspopup="menu" aria-expanded="false"
                            role="button" tabindex="0">
                            <a href={payload.aboutpage_link}><div class="text-white">{payload.about_page}</div></a><img
                                src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                                alt="" class="dropdown-arrow">
                        </div>
                    </div>
                    <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                        <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-3"
                            aria-controls="w-dropdown-list-3" aria-haspopup="menu" aria-expanded="false"
                            role="button" tabindex="0">
                            <a href={payload.jobspage_link}><div class="text-white">{payload.jobs_page}</div></a><img
                                src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                                alt="" class="dropdown-arrow">
                        </div>
                    </div>
                </nav>
                <!-- <div class="menu-button w-nav-button w--open" style="-webkit-user-select: text;" aria-label="menu" role="button"
                    tabindex="0" aria-controls="w-nav-overlay-0" aria-haspopup="menu" aria-expanded="false">
                    <img 
                    src="http://127.0.0.1:5500/web3x/page3/Optic%20-%20Webflow%20HTML%20Website%20Template_files/5f0e4e7cd7cb084980b643c7_icon-menu-white.svg" alt=""
                    class="menu-button-image"> 
                    
                  <ul>
                      <li class="dropdown menu-button w-nav-button w--open" style="-webkit-user-select: text;" aria-label="menu" role="button"
                      tabindex="0" aria-controls="w-nav-overlay-0" aria-haspopup="menu" aria-expanded="false">
                        <a href="javascript:void(0)" class="dropbtn">Dropdown</a>
                        <div class="dropdown-content">
                          <a href="./employers">Hire Talent</a>
                          <a href="./talents">Find a job</a>
                          <a href="./about">About us</a>
                          <a href="./jobs">View jobs</a>
                        </div>
                      </li>
                  </ul>
                </div> -->
                 

                  <ul>
                    <li class="dropdown">
                      <a href="javascript:void(0)" class="dropbtn">
                        <img
                        src="https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0e4e7cd7cb084980b643c7_icon-menu-white.svg"
                        alt=""
                        class="menu-button-image"
                        />
                      </a>
                      <div class="dropdown-content">
                        <a href={payload.employerspage_link}>{payload.employers_page}</a>
                        <a href={payload.talentspage_link}>{payload.talents_page}</a>
                        <a href={payload.aboutpage_link}>{payload.about_page}</a>
                        <a href={payload.jobspage_link}>{payload.jobs_page}</a>
                      </div>
                    </li>
                  </ul>
            </div>
            <div class="w-nav-overlay" data-wf-ignore="" id="w-nav-overlay-0" style="display: none;"></div>
        </div>
    </div>
</div>