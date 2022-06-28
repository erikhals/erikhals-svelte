<script>
	let bggradient = 'grey';
	export let path;
</script>

{@debug bggradient}

<div class="background {path === '/visuals' ? 'blue' : 'grey'}">
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
		background: radial-gradient(
			66.41% 66.41% at 50% 33.59%,
			#19313f 0%,
			#18242b 67.19%,
			#161616 100%
		);
	}
	.blue {
		background: radial-gradient(
			66.41% 66.41% at 50% 33.59%,
			#00829e 0%,
			#00404f 67.19%,
			#003642 100%
		);
	}
	.pink {
		background: radial-gradient(
			66.41% 66.41% at 50% 33.59%,
			#b0006a 0%,
			#830076 67.19%,
			#4f1749 100%
		);
	}
	.yellow {
		background: radial-gradient(
			66.41% 66.41% at 50% 33.59%,
			#dbb800 0%,
			#926632 67.19%,
			#7a4e1a 100%
		);
	}
</style>
