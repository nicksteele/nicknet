---
permalink: /projects/
title: "Personal projects"
---

{% if site.portfolio.size == 0 %}
No projects to share yet.
{% else %}
{% for post in site.portfolio %}
{% include archive-single.html %}
{% endfor %}
{% endif %}
