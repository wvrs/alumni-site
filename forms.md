---
layout: default
title: Forms
permalink: /forms/
---

{% for form in site.data.forms %}
<p><a target="_blank" href="{{ form.file | prepend: '/assets/files/' | relative_url}}">{{ form.title}}</a></p>
{% endfor %}