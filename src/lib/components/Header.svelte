<script lang="ts">
	import * as config from '$lib/config';
</script>

<nav>
	<a href="/" class="title">
		<b>
			{config.title}
		</b>
	</a>

	<ul>
		<li>
			<a href="/about"> About </a>
		</li>
		<li>
			<a href="/contact"> Contact </a>
		</li>
	</ul>

	<button>Toggle</button>
</nav>

<style>
	nav {
		padding-block: var(--size-7);
		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	ul {
		margin-block: var(--size-7);
		display: flex;
		list-style: none;
		gap: var(--size-7);
		margin-left: auto;
		margin-right: var(--size-8);
		padding: 0;
	}

	a {
		color: inherit;
		text-decoration: none;
	}
</style>
