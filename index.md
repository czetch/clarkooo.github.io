---
layout: layout.njk
pageTitle: OOO
secondDeck: On the Origin and Observations of Clark Zhang
---
<ul>
{%- for post in collections.post -%}
  <li>{{ post.data.pageTitle }}</li>
  <em>{{ post.date | date: "%Y-%m-%d" }}</em>
{%- endfor -%}
</ul>
