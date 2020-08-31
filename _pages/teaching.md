---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

Under construction...

-----
Past Teaching Assistant Experience
------
- ECE-GY 6143: Machine Learning, NYU Tandon, Spring 19
- ECE-UY 4563: Introduction to Machine Learning, NYU Tandon, Fall 18
- ECE-GY 8233: Optimal Control Theory, NYU Tandon, Spring 18
- ECE-GY 6233: System Optimization Method, NYU Tandon, Fall 15
{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
