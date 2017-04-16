---
layout: page
title: Doma
---

# Doma

Tady bude něco děsně důležitýho!

## Příspěvky

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Stránky

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>
