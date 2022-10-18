<script>
	import desktop_illustration from '$lib/images/desktop-illustration.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<img src={desktop_illustration} alt="" class="desktop" />
	<h1>
		Svelte - a shortcut to A11y?
	</h1>

	<h2>
		Web Accessibility benefits ALL of us
	</h2>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.desktop {
		width: 300px;
	}
</style>
