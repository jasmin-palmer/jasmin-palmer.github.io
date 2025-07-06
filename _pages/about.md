---
title: "About"
permalink: /about/
categories:
  - Post Formats
tags:
  - image
  - Post Formats
---

author_profile: true

{% capture fig_img %}
![Foo]({{ '/assets/images/EvieGrad2.jpg' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Photo from Evie.</figcaption>
</figure>