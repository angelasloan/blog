---
layout: default
---

# Blog (index)

> Just getting something started

Welcome to {{ site.github.project_title }} - {{ site.github.project_tagline }}

## My Repos

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

## Pages

<ul>
  {% for p in site.pages %}
    <li>
      <a href="{{ p.url }}">{{ p.title }}</a>
    </li>
  {% endfor %}
</ul>

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Contact

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeOs85eMiF4b2MlAVc-N6SWb8MxlP8s0K02U1pcRYg5cI7iiA/viewform?embedded=true" width="640" height="1082" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>