---
layout: page
title: Developers
permalink: /developers
---

## Developers

These developers have signed the Ethical Software Pledge:

{% for pledge in site.data.developers | sort: "date" %}
- [{{ pledge.name }}]({{ pledge.url }}) - {{ pledge.role }} - {{ pledge.date }}
{% endfor %}
