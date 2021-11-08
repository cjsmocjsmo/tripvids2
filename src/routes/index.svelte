<script context="module">
	export const prerender = true;
</script>


<svelte:head>
	<title>Videos</title>
</svelte:head>

<h1>Texas Trip</h1>
<a href="https://frontpage-czi.pages.dev/" ><button>Back</button></a>
<div class="vidWrapper">
	<iframe 
		class="iframeWrapper"
		src="https://www.youtube.com/embed/Wy2818Jq2Nw" 
		title="Texas Trip video player" 
		frameborder="0" 
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
		allowfullscreen>
	</iframe>
</div>
<div class="vidWrapper">
	<iframe 
		class="iframeWrapper"
		src="https://www.youtube.com/embed/Qp8EZr5hyrs" 
		title="Texas Trip video player" 
		frameborder="0" 
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
		allowfullscreen>
	</iframe>
</div>
<div class="vidWrapper">
	<iframe 
		class="iframeWrapper"
		src="https://www.youtube.com/embed/0Tgv2y_qVNQ" 
		title="Texas Trip video player" 
		frameborder="0" 
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
		allowfullscreen>
	</iframe>
</div>
<div class="vidWrapper">
	<iframe  
		class="iframeWrapper"
		src="https://www.youtube.com/embed/_b2oRXJPR_A" 
		title="Texas Trip video player" 
		frameborder="0" 
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
		allowfullscreen>
	</iframe>
</div>
<a href="https://frontpage-czi.pages.dev/" ><button>Back</button></a>

<style>
	button {
        width: 25%;
		padding: 8px;
		border-radius: 7px;
		background-color: white;
		font-size: 1.25em;
		color: black;
    }

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
