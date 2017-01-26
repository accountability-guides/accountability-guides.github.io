---
title: Organization guides
layout: page
---

{{ site.data.general.org-guides-name }} {{ site.data.general.about-org-guides }}

Choose the guide below that best represents your organization. If none of the guides work for you, [open an issue or pull request](https://github.com/accountability-guides/accountability-guides.github.io/) to suggest one that will.

<ul>
{% for org_guide in site.organization-guides %}
  {% if org_guide.title != "Organization guides" %}
    <li><a href="{{ org_guide.url }}">{{ org_guide.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
