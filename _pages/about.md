---
permalink: /
title: About
---
I work on identity and security.

## Blog
A space for notes and longer thoughts. [All posts]({{ '/blog/' | relative_url }}).

{% if site.posts.size == 0 %}No posts yet.{% else %}{% for post in site.posts limit:3 %}{% include archive-single.html %}{% endfor %}{% endif %}

## Personal projects
Things I’m making and exploring. [All projects]({{ '/projects/' | relative_url }}).

{% if site.portfolio.size == 0 %}No projects to share yet.{% else %}{% for post in site.portfolio limit:3 %}{% include archive-single.html %}{% endfor %}{% endif %}
