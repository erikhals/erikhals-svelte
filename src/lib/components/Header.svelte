<script>
	import Nav from '$lib/components/Nav.svelte';
	import ThemeSwitch from '$lib/components/ThemeSwitch.svelte';
</script>

<header>
	<Nav />
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
		background: var(--background);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
	}

	a.linkedin {
		display: flex;
		height: 100%;
		align-items: center;
		color: var(--color-strongest);
	}
</style>
