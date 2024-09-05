<script>
	import Btn from '../btn.svelte';
	
</script>


<section class="hero">
	<div class="container">
		<div class="content-hero">
			<div class="hero-tagline">
				<h1>Taking you beyond <span class="consent">consent management.</span></h1>
			</div>
			
			<p class="content-body">
				consent management platform from a team of specialists who understand the demands of every
				marketer and are ready to assist and advise at every step to provide you with more business
				opptunitues.
			</p>
			
			<div class="Btn">
				<Btn btnName={'Request Demo'} linkUrl={'https://www.google.com/'} btnType={'primary-lg'} />
			</div>
			<div class="check-feature">
				<div class="quick-setup">
					<img src="/graphics/checkbox.svg" alt="Checkbok-quick-setup" />
					<p>Quick Setup</p>
				</div>
				<div class="full-custom">
					<img src="/graphics/checkbox.svg" alt="Checkbok-full-custom" />
					<p>Full Custom</p>
				</div>
				<div class="powerful-report">
					<img src="/graphics/checkbox.svg" alt="Checkbok-powerful-report" />
					<p>Powerful Report</p>
				</div>
			</div>
		</div>
	
		<div class="image-hero">
			<img class="hero" src="/images/modal.png" alt="hero-img" />
		</div>
	</div>
</section>
<div class="wave-up">
	<img class="wave-down" src="/graphics/bg_wave_down.svg" alt="wave up" />
</div>

<style>
	.hero {
		padding-top: 60px;
		background-color: #f7f8f9;
	}
	.container {
		width: 1276px;
		display: flex;
		flex-direction: row;
		align-items: flex-start;
		margin: auto;
		gap: 32px;
	}

	.content-hero {
		width: 50%;
	}

	/* Hero tagline */
	.hero-tagline {
		width: 554px;
		font-family: Poppins;
	}
	h1 {
		color: var(--Gray-900, #2a3342);
		font-size: 60px;
		font-style: normal;
		font-weight: 700;
		line-height: 72px;
		letter-spacing: -1.2px;

		margin-block-start: 0px;
		margin-block-end: 0px;
		margin-inline-start: 0px;
		margin-inline-end: 0px;
	}
	span.consent {
		color: #ffa216;
	}

	.wave-down {
		width: 100%;
	}
	p {
		color: var(--Gray-500, #556987);
		font-family: 'Poppins';
		font-size: 20px;
		font-style: normal;
		font-weight: 500;
		line-height: 30px;
		margin-block-start: 0px;
		margin-block-end: 0px;
		margin-inline-start: 0px;
		margin-inline-end: 0px;
	}
	.content-body {
		margin-top: 24px;
	}

	.check-feature {
		margin-top: 32px;
		display: flex;
		padding: var(--lightTheme-variable-0, 0px);
		flex-direction: column;
		align-items: flex-start;
		gap: 8px;
	}
	.quick-setup {
		display: flex;
		padding: 0px;
		align-items: center;
		gap: 12px;
	}

	.full-custom {
		display: flex;
		padding: 0px;
		align-items: center;
		gap: 12px;
	}
	.powerful-report {
		display: flex;
		padding: 0px;
		align-items: center;
		gap: 12px;
	}

	.image-hero {
		width: 50%;
	}
	img.hero {
		width: 80%;
	}
	.Btn {
		margin-top: 40px;
	}
</style>
