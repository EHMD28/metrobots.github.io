<script>
	import emailLogo from '$lib/assets/icons/other/email.svg';
	import githubLogo from '$lib/assets/icons/logos/github.svg';
	import instagramLogo from '$lib/assets/icons/logos/instagram.svg';
	import xLogo from '$lib/assets/icons/logos/x.svg';
	import youtubeLogo from '$lib/assets/icons/logos/youtube.svg';
	import FooterLink from './FooterLink.svelte';
</script>

<footer>
	<div id="links-container">
		<FooterLink
			link="mailto:metrobots3324@gmail.com"
			imgSrc={emailLogo}
			siteName="Email"
			at="team3324metrobots@gmail.com"
		/>
		<FooterLink
			link="https://github.com/metrobots"
			imgSrc={githubLogo}
			siteName="Github"
			at="metrobots"
		/>
		<FooterLink
			link="https://www.instagram.com/metrobots3324"
			imgSrc={instagramLogo}
			siteName="Instagram"
			at="@metrobots3324"
		/>
		<FooterLink
			link="https://twitter.com/metrobots3324?lang=en"
			imgSrc={xLogo}
			siteName="Twitter/X"
			at="@metrobots3324"
		/>
		<FooterLink
			link="https://www.youtube.com/@TeamMetrobots"
			imgSrc={youtubeLogo}
			siteName="YouTube"
			at="@TeamMetrobots"
		/>
	</div>
</footer>

<style>
	footer {
		background-color: var(--background-color);

		min-height: 15vh;

		padding: 4vh 5vw;
	}

	#links-container {
		display: flex;
		flex-direction: column;
		gap: 20px;
	}
</style>
