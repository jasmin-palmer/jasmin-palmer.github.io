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

image_path: /assets/images/EvieGrad2.jpg

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Photo from Evie.</figcaption>
</figure>