---
title: Cureatr PyPi Packages
---
{% for page in site.pages %}{% if page.tags contains 'package' %}
[{{ page.dir }}]({{site.baseurl }}{{ page.dir }})
{% endif %}{% endfor %}
