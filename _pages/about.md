---
title: "About"
permalink: /about/
author_profile: true
categories:
  - Post Formats
tags:
  - image
  - Post Formats
---


{% capture fig_img %}
![Foo]({{ '/assets/images/EvieGrad2.jpg' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Photo from Evie.</figcaption>
</figure>


Testing writing a post....