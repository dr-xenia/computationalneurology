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
        display: grid;
        grid-template-columns: fit-content(200px) 1fr;
        grid-template-rows:1fr auto;
        grid-template-areas:
            "image content"
            "image footer";
        grid-gap: 20px;
        margin-bottom: 4em;
    }

    .img {
        grid-area: image;
    }

    .content {
        grid-area: content;
    }

    .footer {
        grid-area: footer;
    }

</style>


<div class="media">
	<div class="img">
		<img src="https://wiki.selfhtml.org/images/f/f1/Fr%C3%BChling.png" alt="Balloons">
	</div>
	<div class="content">
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis vehicula vitae ligula sit amet maximus. Nunc auctor neque ipsum, ac porttitor elit lobortis ac. Vivamus ultrices sodales tellus et aliquam. Pellentesque porta sit amet nulla vitae luctus. Praesent quis risus id dolor venenatis condimentum.</p>
	</div>
	<div class="footer">
		An optional footer goes here.
	</div>
</div>




<a class="radius button small" href="{{ site.url }}{{ site.baseurl }}/documentation/">Check out the documentation for all the tricks ›</a>


 [1]: {{ site.url }}{{ site.baseurl }}/documentation/
