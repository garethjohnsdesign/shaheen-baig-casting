---
title: Projects
date: 2015-11-10 15:17:00 Z
permalink: "/projects/"
layout: default
---

Test 
<div class="row small-up-1 medium-up-2 large-up-3">

	<!-- Loop -->
	{% assign projects_documents = site.projects | sort:"position" %}
	{% for project in projects_documents %}
		<div class="columns text-center music-index">	
		<a href="{{ music.url }}"><img src="{{music.cover}}" class="cover"></a>		
		</div>
	{% endfor %}
	<!-- End Loop -->

</div>