<h1>Keep navigating on deep routes and see CSS url() stop working.</h1>
<h2>How to reproduce:</h2>
<ol>
	<li>Click a link below.</li>
	<li>Hit CMD+R/F5 (full reload)</li>
	<li>Check if Svelte Logo still appears in the background.</li>
	<li>Repeat until you reach the route level where it stops working.</li>
</ol>
<ul>
	<li><a href="/depth1">Depth 1</a></li>
	<li><a href="/depth1/depth2">Depth 2</a></li>
	<li><a href="/depth1/depth2/depth3">Depth 3</a></li>
	<li><a href="/depth1/depth2/depth3/depth4">Depth 4</a></li>
	<li>
		<a href="/depth1/depth2/depth3/depth4/depth5">Depth 5 (hint: stop working from now on!)</a>
	</li>
	<li><a href="/depth1/depth2/depth3/depth4/depth5/depth6">Depth 6</a></li>
</ul>

<slot />
