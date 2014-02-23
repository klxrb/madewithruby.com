---
layout: default
title: Made With Ruby
---

Hi and welcome to Made With Ruby. A community driven project that aims to promote the adoption of Ruby frameworks.

<div id="home">
  <h1>Projects</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>