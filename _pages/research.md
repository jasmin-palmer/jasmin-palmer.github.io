---
title: "Research"
layout: splash
permalink: /research/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/EvieGrad2.jpg
  actions:
    - label: "Learn More"
      url: "/terms/"
  caption: "J. E. Palmer, et al., 2024"
excerpt: "This is Jasmin's Research Page!"
intro: 
  - excerpt: "These are my research projects. Aren't they the coolest?!"
feature_row:
  - image_path: /assets/images/EvieGrad2.jpg
    image_caption: "Image courtesy of Dr. Evie"
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/EvieGrad.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/EvieGrad2.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="left" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}