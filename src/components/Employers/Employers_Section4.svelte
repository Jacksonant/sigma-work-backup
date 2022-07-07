<script>
	export let payload = {
		img: '',
		card1_title: '',
		card2_title: '',
		card3_title: '',
		card1_description: '',
		card2_description: '',
		card3_description: '',
	};
</script>

<div class="contained-section-wrapper">
	<div class="w-layout-grid contained-section grid">
		<div class="section align-content-center bg-primary-4">
			<div class="container align-center">
				<h1 class="medium-heading">{payload.card1_title}</h1>
				<p>
					{payload.card1_description}
				</p>
				<h1 class="medium-heading">{payload.card2_title}</h1>
				<p>
					{payload.card2_description}
				</p>
				<h1 class="medium-heading">{payload.card3_title}</h1>
				<p>
					{payload.card3_description}
				</p>

				<!-- <div class="w-layout-grid checklist-grid">
                    <div class="checklist-item">
                        <div class="checklist-circle bg-primary-2"><img
                                src="./Optic - Webflow HTML Website Template_files/5f0cff2dd22b58d53af66737_icon-check-small.svg"
                                alt="" class="checklist-circle-image"></div>
                        <div class="checklist-text">Peace of mind purchasing, no regrets.</div>
                    </div>
                    <div class="checklist-item">
                        <div class="checklist-circle bg-primary-2"><img
                                src="./Optic - Webflow HTML Website Template_files/5f0cff2dd22b58d53af66737_icon-check-small.svg"
                                alt="" class="checklist-circle-image"></div>
                        <div class="checklist-text">A combination of methods</div>
                    </div>
                    <div class="checklist-item">
                        <div class="checklist-circle bg-primary-2"><img
                                src="./Optic - Webflow HTML Website Template_files/5f0cff2dd22b58d53af66737_icon-check-small.svg"
                                alt="" class="checklist-circle-image"></div>
                        <div class="checklist-text">Back-up support when you need it.</div>
                    </div>
                </div> -->
			</div>
		</div>
		<img
			src="./Optic - Webflow HTML Website Template_files/5f0fa0e3261e396035e26d93_Square-Large-02.jpg"
			srcset={payload.img}
			sizes="(max-width: 991px) 100vw, (max-width: 1063px) 94vw, 1000px"
			id="w-node-_1557efee-7136-6828-7a54-3b95cfec7519-16dc1696"
			alt=""
			class="contained-section-image"
		/>
	</div>
</div>
