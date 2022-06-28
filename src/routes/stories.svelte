<svelte:head>
	<title>Erik Hals Stories</title>
</svelte:head>

<div class="background">
	<h1>
		Crafting <br />
		<span>stories</span>
	</h1>
</div>

<style>
	h1 {
		font-family: 'Reem Kufi', sans-serif;
		font-style: normal;
		font-weight: 400;
		font-size: 10rem;
		line-height: 12rem;
		text-align: center;

		color: var(--tertiary-color);
	}
	h1 span {
		font-size: 15rem;
		text-transform: uppercase;
	}
	.background {
		display: flex;
		justify-content: center;
		align-items: center;
		background: radial-gradient(
			66.41% 66.41% at 50% 33.59%,
			#b0006a 0%,
			#830076 67.19%,
			#4f1749 100%
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
