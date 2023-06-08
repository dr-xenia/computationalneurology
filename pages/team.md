---
layout              : page-fullwidth
show_meta           : false
title               : "Getting Started in 10 Steps"
subheadline         : "A Step-by-Step Guide"
teaser              : "This step-by-step guide helps you to customize Feeling Responsive to your needs."
header:
   image_fullwidth  : "header_homepage_13.jpg"
permalink           : "/team/"
---

<style>
.media {
	list-style-type: none;
	width: 30em;
}

.media li {
	display: grid;
	grid-template-columns: 7em 1fr;
	grid-template-rows: 2em 3em;
	gap: 1em;
	margin-bottom: 1em;
}

.media li>img {
	grid-row: 1 / 3;
	width: 6em;
}

.media h3 {
	font: bold 1.2em/1.5 Helvetica, Verdana, sans-serif;
	margin-top: 0;
}

.media p {
	font: 100 0.75em/1.5 Georgia, Times New Roman, serif;
	margin: 0;
}

li:hover {
	background: #F1F3F4;
	cursor: pointer;
}

</style>


<h1>kMedia-Objekt im Grid Layout</h1>
<ul class="media">
	<li> <img src="https://wiki.selfhtml.org/images/f/f1/Fr%C3%BChling.png" alt="Bild einer Narzisse, Quelle Wikipedia">
		<h3>Frühling</h3>
		<p>Endlich wird es wieder ein bisschen sonniger und wärmer. Wer jetzt spazieren geht,
			sieht schon die ersten grünen Knospen sprießen. </p>
		<footer> optionaler Footer </footer>
	</li>
	<li> <img src="https://wiki.selfhtml.org/images/8/8f/Sommer.png" alt="Sonnenuntergang am Strand, Quelle Wikipedia">
		<h3>Sommer</h3>
		<p>Abends bleibt es länger hell und man kann draußen sitzen und die Abkühlung von
			der Tageshitze genießen. </p>
	</li>
	<li> <img src="https://wiki.selfhtml.org/images/5/59/Herbst.png" alt="Bild eines Ahorns im Herbst, Quelle Wikipedia">
		<h3>Herbst</h3>
		<p>Hier kommt noch Text hin. ein ganzer Satz oder vielleicht auch mehr. In die zweite
			Zeile könnte auch noch etwas.</p>
	</li>
	<li> <img src="https://wiki.selfhtml.org/images/a/a7/Winter.png" alt="Schneelandschaft, Quelle Wikipedia">
		<h3>Winter</h3>
		<p>Hier kommt noch Text hin. ein ganzer Satz oder vielleicht auch mehr. In die zweite
			Zeile könnte auch noch etwas.</p>
	</li>
</ul>

<a class="radius button small" href="{{ site.url }}{{ site.baseurl }}/documentation/">Check out the documentation for all the tricks ›</a>


 [1]: {{ site.url }}{{ site.baseurl }}/documentation/
