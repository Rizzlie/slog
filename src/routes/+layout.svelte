<script lang="ts">
	import 'open-props/style';
	import 'open-props/normalize';
	import 'open-props/buttons';

	import Header from '$components/Header.svelte';
	import Footer from '$components/Footer.svelte';
</script>

<Header />

<slot />

<Footer />
