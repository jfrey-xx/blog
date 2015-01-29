---
layout: archive
permalink: /
---

<div class="index_excerpt">

<em>Beside my <a href="http://phd.jfrey.info">research activities</a> I may have some pieces of writing that could be worth reading. Or not, I let you decide.</em>

</div>

## Latest posts

<div class="tiles">
{% for post in site.posts %}
	{% include post-list.html %}
{% endfor %}
</div><!-- /.tiles -->
