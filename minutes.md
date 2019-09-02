---
layout: default
title: Minutes
permalink: /minutes/
---

{% for minute in site.data.minutes %}
<p><a target="_blank" href="{{ site.base_url }}/assets/files/{{ minute.file}}">{{ minute.title}}</a></p>
{% endfor %}