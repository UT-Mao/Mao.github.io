---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a research scientist at CyberAgent AI Lab, and a project researcher with the University of Tokyo, Japan.

My research interest is in Computer Vision, including image recognition, image generation and learning from synthetic images. 



Publications
------

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}


---
title: "Training-Free Location-Aware Text-to-Image Synthesis"
collection: publications
permalink: /publication/2023-10-08-ICIP-Layout
excerpt: 'Layout-to-Image Synthesis via cross-attention manipulation.'
date: 2023-10-08
venue: 'ICIP'
paperurl: 'https://arxiv.org/abs/2304.13427'
---
