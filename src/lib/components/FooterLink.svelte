<script>
	let { link, imgSrc, siteName, at } = $props();
</script>

<a href={link} target="_blank">
	<img src={imgSrc} alt="Metrobots Github" />
	<span class="horizontal-spacer"></span>
	<p>{siteName}: {at}</p>
</a>

<style>
	a {
		height: 100%;

		text-decoration: none;

		display: flex;
		align-items: center;
	}

	img {
		width: 50px;
		background-color: white;
		border-radius: 10px;
	}

	p {
		color: white;
	}

	.horizontal-spacer {
		width: 2vw;
	}
</style>
