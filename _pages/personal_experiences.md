---
layout: archive
title: "Personal Experiences"
permalink: /personal_experiences/
author_profile: true
---

{% include base_path %}

Activities
======
{% for post in site.activities reversed %}
  {% include archive-single-activities.html %}
{% endfor %}

Talks
======
{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}