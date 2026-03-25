---
layout: default
title: "testpath"
---

이 카테고리에 포함된 전체 수학 노트 목록입니다. 🌱

<ul style="margin-top: 20px; line-height: 1.8;">
{% assign current_dir = page.dir %}
{% for p in site.pages %}
  {% if p.dir == current_dir and p.name != "index.md" and p.title %}
    <li>
      <a href="{{ site.baseurl }}{{ p.url }}" style="font-size: 1.1em; font-weight: bold;">{{ p.title }}</a>
    </li>
  {% endif %}
{% endfor %}
</ul>
