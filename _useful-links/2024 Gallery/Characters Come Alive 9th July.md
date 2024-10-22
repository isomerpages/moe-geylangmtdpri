---
title: Characters Come Alive 9th July
permalink: /characters-come-alive-9th-july/
variant: markdown
description: ""
third_nav_title: 2024 Gallery
---
---
layout: resources-alt
title: Event Album
---
\# Event Album

{% for image in site.data.event\_album %} 
<div class="row is-multiline"> 
	<div class="col is-one-third-desktop is-one-third-tablet"> 
		<a target="\_blank" href="{{- image.image\_url -}}"> 
			<img alt="{{- image.alt\_text -}}" src="{{- image.thumbnail\_url -}}"> 
		</a>
	</div> 
</div> 
{% endfor %}






