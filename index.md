---
layout: home
title: Home
---

# Welcome to Better Places For Humans

This site is dedicated to exploring and documenting projects and ideas that help create better places for humans.

## Latest Blog Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View all blog posts](/blog/)

## Featured Projects

{% for project in site.projects limit:3 %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}

[View all projects](/projects/)
