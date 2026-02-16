---
layout: archive
title: "Research Hub"
permalink: /research/
author_profile: true
header:
  overlay_color: "#0a192f"
  overlay_filter: "0.5"
  overlay_image: /assets/images/train-hero-wide.jpg
---

Collection of deep dives into India's high-speed rail projects.

{% for post in site.posts %}
  {% if post.categories contains 'research' %}
    <!-- Will auto-populate when you add posts -->
  {% endif %}
{% endfor %}

Start with:  
- [BEML B28 Full Analysis](/research/beml-b28/)
