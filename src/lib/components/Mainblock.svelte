<div class="container">
	<h1><slot name="heading" /></h1>
	<p><slot name="tagline" /></p>
</div>

<style>
	h1 {
		font-family: 'Reem Kufi', sans-serif;
		font-style: normal;
		font-weight: 500;
		font-size: 10em;
		line-height: 250px;
		text-align: left;
		margin: auto;
		color: #fff0e2;
		cursor: default;
		user-select: none;
	}

	.container {
		max-width: 1920px;
	}
</style>
