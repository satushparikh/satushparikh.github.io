---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

Welcome to my website! Below you'll find the main pages of my site. For search engines, an [XML version]({{ base_path }}/sitemap.xml) is also available.

## Main Pages
{% for post in site.pages %}
  {% if post.title == "Research" or post.title == "Home" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Publications
{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}

## Teaching
{% for post in site.teaching %}
  {% include archive-single.html %}
{% endfor %}

## Talks & Presentations
{% for post in site.talks %}
  {% include archive-single.html %}
{% endfor %}

## Portfolio
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

## Blog Posts
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
