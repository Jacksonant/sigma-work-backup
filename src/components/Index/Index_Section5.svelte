<script>
	export let payload = {
		title: '',
		card1_title: '',
		card2_title: '',
		card3_title: '',
		card4_title: '',
		card5_title: '',
		card1_description: '',
		card2_description: '',
		card3_description: '',
		card4_description: '',
		card5_description: ''
	};
</script>

<div class="section no-bottom-padding">
	<div class="main-container narrow">
		<h1 class="medium-heading section-heading">{payload.title}</h1>
		<div class="w-layout-grid checklist-grid-thirds">
			<div class="checklist-horizontal-item">
				<div class="checklist-circle bg-primary-3">
					<img
						src="./Optic - Webflow HTML Website Template_files/5f0cff2dd22b58d53af66737_icon-check-small.svg"
						alt=""
						class="checklist-circle-image"
					/>
				</div>
				<div class="checklist-horizontal-text">
					<h6>{payload.card1_title}</h6>
					<div>
						{payload.card1_description}
					</div>
				</div>
			</div>
			<div class="checklist-horizontal-item">
				<div class="checklist-circle bg-primary-3">
					<img
						src="./Optic - Webflow HTML Website Template_files/5f0cff2dd22b58d53af66737_icon-check-small.svg"
						alt=""
						class="checklist-circle-image"
					/>
				</div>
				<div class="checklist-horizontal-text">
					<h6>{payload.card2_title}</h6>
					<div>
						{payload.card2_description}
					</div>
				</div>
			</div>
			<div class="checklist-horizontal-item">
				<div class="checklist-circle bg-primary-3">
					<img
						src="./Optic - Webflow HTML Website Template_files/5f0cff2dd22b58d53af66737_icon-check-small.svg"
						alt=""
						class="checklist-circle-image"
					/>
				</div>
				<div class="checklist-horizontal-text">
					<h6>{payload.card3_title}</h6>
					<div>{payload.card3_description}</div>
				</div>
			</div>
			<div class="checklist-horizontal-item">
				<div class="checklist-circle bg-primary-3">
					<img
						src="./Optic - Webflow HTML Website Template_files/5f0cff2dd22b58d53af66737_icon-check-small.svg"
						alt=""
						class="checklist-circle-image"
					/>
				</div>
				<div class="checklist-horizontal-text">
					<h6>{payload.card4_title}</h6>
					<div>
						{payload.card4_description}
					</div>
				</div>
			</div>
			<div class="checklist-horizontal-item">
				<div class="checklist-circle bg-primary-3">
					<img
						src="./Optic - Webflow HTML Website Template_files/5f0cff2dd22b58d53af66737_icon-check-small.svg"
						alt=""
						class="checklist-circle-image"
					/>
				</div>
				<div class="checklist-horizontal-text">
					<h6>{payload.card5_title}</h6>
					<div>{payload.card5_description}</div>
				</div>
			</div>
		</div>
	</div>
</div>
