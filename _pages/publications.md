---
layout: archive
title: "Research & Publications"
permalink: /publications/
author_profile: true
---

My doctoral research focused on statistical and machine learning methods for understanding neural population dynamics from large-scale recordings. I worked on methods for estimating neural population burst timing, cross-area coupling, trial-level variability, denoising, and interpretable timing motifs across brain regions.

This work reflects a broader interest in developing models that are statistically principled, computationally practical, and useful for interpreting complex biological and time-dependent systems.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Selected Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
