<script>
// @ts-nocheck

	let tabActive = 'Quick Setup';
	
</script>

<img class="wave-up" src="/graphics/bg_wave_up.svg" alt="wave up" />
<section>
	<div class="container">
		<div class="feature-tagline">
			<h1 class="text-tagline">Simple and effective</h1>
			<p>
				This is the heart of our system. Therefore, The use is not difficult and easy to understand.
			</p>
		</div>
		<div class="tab">
			<button
				class="btn-secondary {tabActive === 'Quick Setup' ? 'active' : ''}"
				on:click={() => (tabActive = 'Quick Setup')}>Quick Setup</button
			>
			<button
				class="btn-secondary {tabActive === 'Full Custom' ? 'active' : ''}"
				on:click={() => (tabActive = 'Full Custom')}>Full Custom</button
			>
			<button
				class="btn-secondary {tabActive === 'Powerful Reporting' ? 'active' : ''}"
				on:click={() => (tabActive = 'Powerful Reporting')}>Powerful Reporting</button
			>
		</div>
		<div class="tab-content-container">
			<div
				class="tab-content"
				id="quick-setup"
				style="display: {tabActive === 'Quick Setup' ? 'flex' : 'none'};"
			>
				<div class="content">
					<h2>QUICK SET-UP</h2>
					<p>
						Can be set up by anyone by just updating a few lines of HTML code. This then can be done
						quickly and with less hassle.
					</p>
				</div>
				<div class="video" id="quick-setup">
					<!-- svelte-ignore a11y-media-has-caption -->
					<video class="video-frame" src="/video/quick_setup.mp4" loop="loop" autoplay="autoplay" />
				</div>
			</div>

			<div
				class="tab-content"
				id="full-custom"
				style="display: {tabActive === 'Full Custom' ? 'flex' : 'none'};"
			>
				<div class="content">
					<h2>FULL CUSTOM</h2>
					<p>
						We tailor the solution to your consent management needs by experienced developers and
						marketing consultants
					</p>
				</div>
				<div class="video" id="full-custom">
					<!-- svelte-ignore a11y-media-has-caption -->
					<video class="video-frame" src="/video/full_custom.mp4" loop="loop" autoplay="autoplay"/>
				</div>
			</div>
			<div
				class="tab-content"
				id="powerful-reporting"
				style="display: {tabActive === 'Powerful Reporting' ? 'flex' : 'none'};"
			>
				<div class="content">
					<h2>POWERFUL REPORTING</h2>
					<p>Powerful dashboard and data visualisation to help analyse and improve consent form.</p>
				</div>
				<div class="video" id="powerful-reporting">
					<!-- svelte-ignore a11y-media-has-caption -->
					<video class="video-frame" src="/video/powerful_reporting.mp4" loop="loop" autoplay="autoplay" />
				</div>
			</div>
		</div>
	</div>
</section>
<img class="wave-down" src="/graphics/bg_wave_down.svg" alt="wave up" />

<style>
	* {
		display: block;
		margin-block-start: 0px;
		margin-block-end: 0px;
		margin-inline-start: 0px;
		margin-inline-end: 0px;
		font-weight: bold;
	}
	.wave-up {
		width: 100%;
	}
	.wave-down {
		width: 100%;
	}
	section {
		background-color: #f7f8f9;
	}
	.container {
		width: 1276px;
		margin: auto;
	}
	.feature-tagline {
		display: flex;
		flex-direction: column;
		align-items: center;
		font-family: Poppins;
		padding-bottom: 44px;
	}

	.tab {
		display: flex;
		gap: 20px;
		justify-content: center;
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
	h2 {
		font-family: Poppins;
		font-size: 32px;
		padding-bottom: 24px;
	}

	.tab-content-container {
		width: 1000px;
		background-color: #fff;
		padding: 108px;
		margin: auto;
	}
	.tab-content {
		display: flex;
		flex-direction: row;
		gap: 100px;
		justify-content: space-between;
		align-items: center;
	}
	.content {
		width: 50%;
		width: 312px;
		display: flex;
		flex-direction: column;
	}

	.btn-secondary {
		color: #636384;
		background-color: #e3e6f5;
		width: 196px;
		height: 48px;
		font-size: 18px;
		font-style: normal;
		font-weight: 600;
		line-height: normal;
		letter-spacing: 0.4px;
		border-width: 0;
		border-radius: 12px 12px 0px 0px;
	}

	.btn-secondary.active {
		background-color: #ffa216;
		color: #ffffff;
	}
	.video-frame{
		width: 628px;
	}
</style>
