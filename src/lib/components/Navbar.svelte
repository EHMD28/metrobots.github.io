<script>
	// TODO: Move logo to appropriate directory.
	import metrobotsLogo from '$lib/assets/gdb.png';
</script>

<nav>
	<img id="metrobots-logo" src={metrobotsLogo} alt="Metrobots Logo" />
	<div id="page-links">
		<p>About Us</p>
		<p>Our Season</p>
		<p>Our Community</p>
		<p>Resources</p>
	</div>
</nav>

<style>
	nav {
		background-color: lightblue;
		min-height: 20vh;
		padding: 0 2vw;

		display: flex;
		flex-direction: row;
		justify-content: space-between;
		align-items: center;
	}

	#metrobots-logo {
		width: 10vw;
	}

	#page-links {
		display: flex;
		flex-direction: row;
		justify-content: space-around;

		width: 50%;
	}
</style>
