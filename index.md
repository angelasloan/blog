---
layout: default
---

# Blog (index)

> Just getting something started

Welcome to {{ site.github.project_title }} - {{ site.github.project_tagline }}

## My GitHub Repos

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

## My Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
