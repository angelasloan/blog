---
layout: default
title: Blog
---

# {{ page.title }} (README.md)

> Just getting something started

Welcome to {{ site.github.project_title }} - {{ site.github.project_tagline }}

## My GitHub Repos

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

