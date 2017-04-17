---
layout: page
title: Doma
---

# Doma

Vítejte na webu pro lidi žijící vzájemně v sousedství a s přáním žít více v komunitě a vzájemné souhře.

Tento komunitní web je určen jako nástroj pro vzájemné zápůjčky nářadí, nástrojů, atd., abyste nemuseli kupovat nic, co nevyužijete častěji. Vzájemně si zde pomůžete, nabídněte, co máte či umíte a naopak. Sdílejte zde rady, návody, hodnocení výrobků v oblasti kutilství. Svolávejte skupinové a další možné aktivity.

## Příspěvky

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
