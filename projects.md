---
layout: page
title: Projects
permalink: /projects
---

## Developers

These projects have signed the Ethical Software Pledge:

{% for pledge in site.data.projects | sort: "date" %}
- [{{ pledge.name }}]({{ pledge.url }}) - {{ pledge.description }} - {{ pledge.date }}
{% endfor %}
