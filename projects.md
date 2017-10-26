---
layout: default
title: "Projects"
url: "projects"
---

## Current Work / Interests

* Refactoring an ALSA backend for an audio processing engine
* Testing of out-of-tree RME and MARIAN ALSA drivers and integration
  into a product
* Monitoring and configuration solutions for a linux based real time system
* Bringing this page up to date, integrating interesting older projects

## Past Projects
<ul>
  {% for post in site.posts %}
    {% if post.tags contains 'project' %}
      <li>
        {{ post.project_year }} <a href="{{ post.url }}"> {{ post.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>
