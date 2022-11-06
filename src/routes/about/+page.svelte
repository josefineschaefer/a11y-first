<script>
	import disabilities from '$lib/images/disabilities.png';
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>About A11y</h1>

	<p>
		Svelte is said to be 'a11y first' - but what does that mean? Before we dive in, let's explore in
		a little bith more depth what web accessibility means and who benefits from it.
	</p>
	<figure>
	<blockquote>
		"Access to information and communications technologies including the web is defined as a basic
		Human Right."
	</blockquote>
	<figcaption>
		&mdash; United Nations Convention on the Rights of Persons with Disabilities
	</figcaption>
</figure>
<p>
	Web Accessibility means that websites, tools and technologies are designed and implemented so that people with disabilities can use them and participate equally on the web. 
As stated in the quote, it is also a basic human right, as defined by the United Nations. According to the world report on disability by the world health organization it is estimated that over 15% of the global population experience some form of disability - and that's over 1 billion people. 

</p>
	<img src={disabilities} alt="overview table of different kinds of disabilities and impairments" />
	<figcaption>
		Fig. 1 Table of different kinds of disabilities, including permant, temporary and situational
		impairments
	</figcaption>
</div>

<style>

	img{
		width: 100%;
  		height: auto;
	}
</style>
