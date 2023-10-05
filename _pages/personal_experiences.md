---
layout: archive
title: "Personal Experiences"
permalink: /personal_experiences/
author_profile: true
---

{% include base_path %}

Activities Talks and Lectures
======
  <ul>{% for post in site.activities reversed %}
{% include archive-single-activity.html %}
  {% endfor %}

1
======
  <ul>{% for post in site.talks reversed %}
{% include archive-single-talk.html %}
  {% endfor %}