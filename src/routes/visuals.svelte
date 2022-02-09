<svelte:head>
	<title>Erik Hals Visuals</title>
</svelte:head>

<div class="background">
	<div class="container">
		<h1>Designing <br /> <span>visuals</span></h1>
	</div>
</div>

<style>
	h1 {
		font-family: 'Reem Kufi', sans-serif;
		font-style: normal;
		font-weight: 500;
		font-size: 10rem;
		line-height: 12rem;
		text-align: left;
		color: var(--primary-color);
	}
	h1 span {
		font-size: 15rem;
		text-transform: uppercase;
	}
	.container {
		max-width: 1920px;
		margin-left: 20vw;
	}
	.background {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: left;
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
