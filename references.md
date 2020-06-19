---
layout: default
---

{% for r in site.data.citations %}
	{% assign cur_id = r[0] %}
	{% include reference.html id=cur_id %}
{% endfor %}
