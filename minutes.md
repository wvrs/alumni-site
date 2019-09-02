---
layout: default
title: Minutes
permalink: /minutes/
---

{% for minute in site.data.minutes %}
<p><a target="_blank" href="{{ minute.file | prepend: /assets/files/' | relative_url'}}">{{ minute.title}}</a></p>
{% endfor %}