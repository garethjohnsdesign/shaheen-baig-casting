---
title: Projects
date: 2015-11-10 15:17:00 Z
permalink: "/projects/"
layout: default
---

<div class="row">
{% for project in site.projects %}
<div class="small-12 medium-4 columns">
{% include excerpt.html %}
</div>
{% endfor %}
</div>