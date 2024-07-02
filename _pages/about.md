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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
