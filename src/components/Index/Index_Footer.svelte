<script>
    export let payload={
		addressline1: "",
		addressline2: "",
		addressline3: "",
		phone: "",
		email: "",
		copyright: "",
		company: "",
		companylink: ""

    }
</script>

<div class="footer-2 border-bottom wf-section">
	<div class="main-container">
		<div class="w-layout-grid footer-2-grid">
			<div class="footer-2-contact-details">
				<!-- <a href="" class="footer-2-logo w-inline-block"><img src="" alt="" class="logo-large" /></a> -->
				<p>{payload.addressline1}<br />{payload.addressline2}<br />{payload.addressline3}</p>
				<div class="w-layout-grid menu-vertical-grid">
					<a href="tel:+60183915232" class="hover-link icon-link w-inline-block">
						<div>{payload.phone}</div>
					</a><a href="mailto:hello@talentloop.co" class="hover-link icon-link w-inline-block">
						<div>{payload.email}</div>
					</a>
				</div>
			</div>

			<div class="w-layout-grid footer-menus-grid footer-2-menus">
				<div>
					<div class="text-uppercase footer-menu-title">Company</div>
					<div class="w-layout-grid menu-vertical-grid">
						<a href="./about" class="hover-link">About Us</a><a href="./faq" class="hover-link"
							>FAQ</a
						><a href="./jobs" class="hover-link">Careers</a><a
							href="./blogs"
							aria-current="page"
							class="hover-link w--current">Blogs</a
						>
					</div>
				</div>
				<div>
					<div class="text-uppercase footer-menu-title">
						<a href="./talents" class="hover-link">Jobseekers</a>
					</div>
				</div>

				<div>
					<div class="text-uppercase footer-menu-title">
						<a href="./employers" class="hover-link">Employers</a>
					</div>
				</div>
			</div>
		</div>

		<div class="text-center">
			<div class="text-small muted">
				© {payload.copyright} • Powered by <a href={payload.companylink} target="_blank">{payload.company}</a>
			</div>
		</div>
	</div>
</div>