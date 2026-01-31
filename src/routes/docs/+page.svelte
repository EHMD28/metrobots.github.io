<script>
	import { resolve } from '$app/paths';
</script>

<svelte:head>
	<title>Documentation | Metrobots</title>
</svelte:head>

<main>
	<p>TODO: Add documentation</p>
	<br />
	<a href={resolve('/docs/mechanical')}>Mechanical Documentation</a>
	<br />
	<a href={resolve('/docs/electrical')}>Electrical Documentation</a>
	<br />
	<a href={resolve('/docs/mechanical')}>Programming Documentation</a>
</main>

<style>
	main {
		padding: 2vh 5vw;
	}
</style>
