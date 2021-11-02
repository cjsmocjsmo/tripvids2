<script context="module">
	export const prerender = true;
</script>


<svelte:head>
	<title>Videos</title>
</svelte:head>

<h1>Texas Trip</h1>
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
<!-- <h1>USS Rosevelt</h1>
<p>The USS Rosevelt entering Puget Sound for refit</p>
<div class="vidWrapper">
	<iframe 
		class="iframeWrapper"
		src="https://www.youtube.com/embed/HQv-tpgzBCI" 
		title="USS Rosevelt" 
		frameborder="0" 
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
		allowfullscreen>
	</iframe>
</div>
<div  class="vidWrapper">
	<iframe 
		class="iframeWrapper" 
		src="https://www.youtube.com/embed/gthpd2HNus8" 
		title="USS Rosevelt"
		frameborder="0"
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
		allowfullscreen>
	</iframe>
</div> -->

<!-- <h1>Grandma</h1>
<div  class="vidWrapper">
	
	<iframe 
		class="iframeWrapper"
		src="https://www.youtube.com/embed/I3e04TJ-Ses" 
		title="Grandma" 
		frameborder="0"
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
		allowfullscreen>
	</iframe>
</div> -->

<style>

	h1, p {
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
