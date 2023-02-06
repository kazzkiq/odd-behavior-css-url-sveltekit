<div class="c_ad_slot">
	<slot />
</div>

<style lang="scss">
	.c_ad_slot {
		width: 100%;
		min-height: 200px;
		border: 1px solid rgba(#000, 0.1);
		border-radius: 10px;
		overflow: hidden;
		background: url('/svelte-logo.svg') repeat #fdfdfd;
		background-size: 20px;
		position: relative;
		display: flex;
		align-items: center;
		justify-content: center;
	}
</style>
