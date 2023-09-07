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
	}

	ul {
		margin-block: var(--size-7);
	}

	a {
		color: inherit;
		text-decoration: none;
	}
</style>
