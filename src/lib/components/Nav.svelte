<nav>
	<a sveltekit:prefetch href="/">Home</a>
	<ul>
		<li><a class="primary" sveltekit:prefetch href="/visuals">Visuals</a></li>
		<li><a class="secondary" sveltekit:prefetch href="/stories">Stories</a></li>
		<li><a class="tertiary" sveltekit:prefetch href="/experiences">Experiences</a></li>
	</ul>
</nav>

<style>
	nav {
		display: flex;
		justify-content: space-between;
		width: 100%;
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
	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		padding: 0 1em;
		color: var(--color-strongest);
		font-weight: 700;
		font-size: 0.8rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		transition: color 0.2s linear;
	}
	nav a:before {
		content: '';
		display: inline-block;
		width: 15px;
		height: 15px;
		border-radius: 15px;
	}
	a.primary:before {
		background-color: var(--primary-color);
	}
	a.secondary:before {
		background-color: var(--secondary-color);
	}
	a.tertiary:before {
		background-color: var(--tertiary-color);
	}
</style>
