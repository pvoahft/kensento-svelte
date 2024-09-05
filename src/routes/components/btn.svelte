<script>
	// @ts-nocheck

	export let btnName = '';
	export let linkUrl = '';
	export let btnType = 'primary';

	let clickUrl = (linkUrl) => {
		window.open(linkUrl);
	};
</script>

<button class={btnType} on:click={clickUrl(linkUrl)}> {btnName}</button>

<style>
	button {
		display: inline-flex;
		padding: 8px 16px;
		justify-content: center;
		align-items: center;
		gap: 6px;
		border-radius: 6px;
		box-shadow: 0px 1px 2px 0px rgba(105, 81, 255, 0.05);
		border-width: 0px;
		font-family: Poppins;
		font-size: 14px;
		font-style: normal;
		font-weight: 500;
		line-height: 20px;
		
	}

	button.primary {
		background: #ffa216;
		color: var(--Primary-050, var(--baseColor-green-50, #f0fdf4));
	}
	button.secondary {
		display: inline-flex;
		padding: 8px 16px;
		justify-content: center;
		align-items: center;
		gap: 6px;
		border-radius: 6px;
		background: #FFFFFF;
		box-shadow: 0px 1px 2px 0px rgba(105, 81, 255, 0.05);
		border-width: 1px;
		border-radius: 8px;
		color: #333f51;
		font-family: Poppins;
		font-size: 14px;
		font-style: normal;
		font-weight: 500;
		line-height: 20px;
	}

	button.primary-lg {
		width: 193px;
		height: 51px;
		border-radius: 8px;
		background: #ffa216;
		color: var(--Primary-050, var(--baseColor-green-50, #f0fdf4));
		/* typography/large/title */
		font-family: 'Poppins';
		font-size: 18px;
		font-style: normal;
		font-weight: 600;
		line-height: normal;
		letter-spacing: 0.4px;
		border-width: 0px;
	}
</style>
