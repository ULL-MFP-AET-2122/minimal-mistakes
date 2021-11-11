---
layout: single
title: MIS PUBLICACIONES SOBRE DOCENCIA
permalink: /docencia
toc: true
---

{%- for post in site.categories["docencia"]  %}
* [{{post.title}}]({{post.url}})
{% endfor %}