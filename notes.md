---
layout: page
title: 随笔
permalink: /notes/
kicker: Notes
description: 记录 AI 实践、赚钱项目、自动化工作流和长期思考。
---

<div class="post-list">
  {% for post in site.posts %}
  <article class="post-row">
    <div>
      <time>{{ post.date | date: "%Y-%m-%d" }}</time>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.description | default: post.excerpt | strip_html | truncate: 140 }}</p>
    </div>
    <a class="read-link" href="{{ post.url | relative_url }}">阅读</a>
  </article>
  {% endfor %}
</div>
