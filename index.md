---
title: Chen Wang 
subtitle: I research Spatial AI and Robotics
layout: page
show_sidebar: false
hide_footer: false
hero_height: is-medium
hero_image: /img/chen-back.jpg
hero_link: /research/
hero_link_text: See My Research

hero_link2: /publications
hero_link_text2: See My Publication
---

# About Me

I am a Project Scientist with the [Robotics Institute](https://www.ri.cmu.edu/) at [Carnegie Mellon University](https://www.cmu.edu/). My research goal is to achieve human-level spatial awareness on robot systems. I am particularly interested in robot perception, vision, and machine learning.

I am also engaged in delivering simple and efficient [source code](https://github.com/wang-chen).

# Highlights

{% assign posts = site.posts | where:"categories","highlights" %}
<div class="columns is-multiline">
    {% for post in posts %}
    <div class="column is-4-desktop is-6-tablet">
        {% include post-card.html %}
    </div>
    {% endfor %}
</div>
