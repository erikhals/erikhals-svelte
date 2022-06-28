<script>
	import { fly } from 'svelte/transition';
</script>

<div class="container" in:fly={{ y: 500 }} out:fly={{ y: -500 }}>
	<h1><slot name="heading" /></h1>
	<p><slot name="tagline" /></p>
</div>

<style>
	.container {
		position: absolute;
	}
	h1 {
		font-family: 'Hubballi', sans-serif;
		font-style: normal;
		font-weight: 500;
		font-size: 10em;
		text-transform: uppercase;
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
