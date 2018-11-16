---
title: Cureatr package PyPi Links
tags: package
---
{% for file in site.static_files %}{% if file.extname == '.gz' and file.path contains page.dir %}
[{{ file.name }}]({{ site.baseurl }}{{ file.path }})
{% endif %}{% endfor %}
