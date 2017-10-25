---
layout: default
title: "Home"
---

## About Me
Hi, I'm Markus, software developer and student at
[Technische Universität Ilmenau](https://www.tu-ilmenau.de).

This page is currently under construction.

## Recent Activity

<ul>
  {% for post in site.posts offset: 0 limit: 5  %}
    <li>
      {{ post.date | date: '%Y-%m-%d' }} <a href="{{ post.url }}"> {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
