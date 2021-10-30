---
layout: default
title: Blog
---

# Blog

> Just getting something started

Welcome to {{ site.github.project_title }} - {{ site.github.project_tagline }}

## My GitHub Repos

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>