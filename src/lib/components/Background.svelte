<script>
	export let path;

	function setColor(p) {
		return {
			'/': 'grey',
			'/visuals': 'blue',
			'/stories': 'pink',
			'/experiences': 'yellow'
		}[p];
	}
</script>

<div class="background {setColor(path)}">
	<slot />
</div>

<style>
	.background {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		background-position: center;
		position: fixed;
		top: 0;
		bottom: 0;
		right: 0;
		left: 0;
		z-index: -1;
		transition: all 2s;
	}
	.grey {
		background: #18242b;
	}
	.blue {
		background: #00404f;
	}
	.pink {
		background: #830076;
	}
	.yellow {
		background: #926632;
	}
</style>
