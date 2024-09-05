<script>
	import Btn from "./btn.svelte";

</script>

<header>
	<div class="container-header">
		<a href="/" class="logo-kensento">
			<img src="/graphics/logo-kensento.svg" alt="KENSENTO-Logo" />
		</a>
		<nav>
			<a href="/#">Home</a>
			<a href="/#">Service</a>
			<a href="/#">Pricing</a>
			<a href="/#">Contact</a>
		</nav>
		<div class="cta">
			<a href="https://kensento.com/" target="_blank" class="log-in">Log In</a>
			<Btn btnName={'Sign Up'} linkUrl={'https://www.google.com/'} btnType={'primary'} />
		</div>
	</div>
</header>

<style>
	header {
		justify-content: center;
		background-color: #f7f8f9;
	}
	.container-header {
		margin: auto;
		width: 1276px;
		height: 80px;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between;
	}

	nav {
		display: flex;
		flex-direction: row;
		gap: 48px;
	}
	a {
		color: var(--Gray-500, #556987);
		font-family: Poppins;
		font-size: 16px;
		font-style: normal;
		font-weight: 500;
		line-height: 24px;
		text-decoration: none;
	}

	.cta {
		display: flex;
		flex-direction: row;
		gap: 24px;
		align-items: center;
	}

	/* .sign-up {
		display: inline-flex;
		padding: 8px 16px;
		justify-content: center;
		align-items: center;
		gap: 6px;
		border-radius: 6px;
		background: #ffa216;
		box-shadow: 0px 1px 2px 0px rgba(105, 81, 255, 0.05);
		border-width: 0px;
		color: var(--Primary-050, var(--baseColor-green-50, #f0fdf4));
		font-family: Poppins;
		font-size: 14px;
		font-style: normal;
		font-weight: 500;
		line-height: 20px;
	} */
</style>
