<script context="module">
	import { browser, dev } from '$app/env';

	// we don't need any JS on this page, though we'll load
	// it in dev so that we get hot module replacement...
	export const hydrate = dev;

	// ...but if the client-side router is already loaded
	// (i.e. we came here from elsewhere in the app), use it
	export const router = browser;

	// since there's no dynamic data here, we can prerender
	// it so that it gets served as a static asset in prod
	export const prerender = true;
</script>

<svelte:head>
	<title>About</title>
</svelte:head>

<h1>Grandma</h1>
<div  class="vidWrapper">
	<iframe 
		class="iframeWrapper"
		src="https://www.youtube.com/embed/I3e04TJ-Ses" 
		title="Grandma" 
		frameborder="0"
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
		allowfullscreen>
	</iframe>
</div>

<style>

	h1 {
		color: white;
	}

	.vidWrapper {
		text-align: center;
		position: relative;
        overflow: hidden;
        padding-top: 56.25%;
		margin-top: 10px;
		
	}

	.iframeWrapper {
		position: absolute;
		top: 0;
		left: 0;
		bottom: 0;
		right: 0;
		width: 100%;
		height: 100%;
		
	}
</style>
