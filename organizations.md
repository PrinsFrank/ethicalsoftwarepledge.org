---
layout: page
title: Organizations
permalink: /organizations
---

## Organizations

These organizations have signed the Ethical Software Pledge:

{% for pledge in site.data.organizations | sort: "date" %}
- {: #{{ pledge.name | slugify }} } [{{ pledge.name }}]({{ pledge.url }}) - {{ pledge.description }} - {{ pledge.date }}
{% endfor %}
