<svelte:head>
	<title>Erik Hals Visuals</title>
</svelte:head>

<div class="background"><h1>I design <br /> <span>visuals</span></h1></div>

<style>
	h1 {
		font-family: Megrim;
		font-style: normal;
		font-weight: 500;
		font-size: 246px;
		line-height: 150px;
		text-align: right;
		text-transform: lowercase;
		color: var(--primary-color);
	}
	h1 span {
		font-size: 150px;
	}
	.background {
		display: flex;
		justify-content: center;
		align-items: center;
		background: radial-gradient(
			66.41% 66.41% at 50% 33.59%,
			#00829e 0%,
			#00404f 67.19%,
			#003642 100%
		);
		background-position: center;
		position: fixed;
		top: 0;
		bottom: 0;
		right: 0;
		left: 0;
		z-index: -1;
	}
</style>
