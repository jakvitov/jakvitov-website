---
layout: page
title: My projects
permalink: /projects/
---

# About my afterwork pell-mells

Each time I learn something new in terms of software engineering, I always tend to create some small project and test it out. My little projects aren't ambitous businesslike side hustless, but rather set of attempts to play with programming and software architecture like child with pieces of Lego building kit.

I focus almost entirely on backend or some sort of mathematical computing, frontend or UX design were never really my thing, as you can see on this website :D

All my after work programming is entirely versioned in my repositories on [GitHub](https://github.com/jakvitov).

# Projects:

<div>
  {% for project in site.projects %}
    <hr>
    <h2>{{ project.title }}</h2>
    <img src="{{ project.image }}" alt="{{ project.title }}" style="max-width: 300px; height: auto;">
    <p>{{ project.description }}</p>
    <p><a href="{{ project.url }}">Project URL.</a></p>
    <p><small>{{ project.date | date: "%B %d, %Y" }}</small></p>
  {% endfor %}
</div>
