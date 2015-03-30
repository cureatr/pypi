---
title: Cureatr PyPi Links
---
{% for file in site.static_files %}{% if file.extname == '.gz' %}
[{{ site.baseurl }}{{ file.path }}]({{ site.baseurl }}{{ file.path }})
{% endif %}{% endfor %}
