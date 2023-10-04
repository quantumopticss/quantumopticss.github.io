---
layout: archive
title: "Personal Experiences"
permalink: /personal_experiences/
author_profile: true
---

{% include base_path %}

Activities
======
* <a href="{{Wu li chuang xin shi jian huo dong}}">
  * Nanjing University
  * Duties included: Tagging issues
  * Supervisor: Professor Git



Talks
======

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}