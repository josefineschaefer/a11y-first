<script>
	import desktop_illustration from '$lib/images/desktop-illustration.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<img src={desktop_illustration} class="desktop"/>
	<h2>Svelte - a shortcut to A11y?</h2>

	<h1>Web Accessibility benefits ALL of us</h1>
	<div>
		<a href="https://www.w3.org/WAI/standards-guidelines/wcag/" class="button">WCAG</a>
		<a tabindex="1" href="https://webaim.org/techniques/keyboard/" class="button">Keyboard Accessibility</a>
		<a href="https://www.w3schools.com/html/html5_semantic_elements.asp" class="button">Semantic HTML</a>
		<a class="button">Color Contrast</a>
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h2 {
		width: 100%;
	}

	.desktop {
		width: 300px;
	}
	.button {
		display: inline-block;
		border-radius: 5px;
		box-shadow: 0 6px 13px 2px rgb(0 0 0 / 11%);
		text-decoration: none;
		border: 0;
		box-sizing: border-box;
		text-align: center;
		padding: 9px 26px;
		margin: 10px 10px 0;
		background-color: var(--color-theme-2);
		color: #fff;
	}
</style>
