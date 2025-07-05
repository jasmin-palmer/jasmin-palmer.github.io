---
title: "News"
layout: splash
permalink: /news/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/EvieGrad2.jpg
  actions:
    - label: "learn more"
      url: "/terms/"
  caption: "j. e. palmer, et al., 2024"
excerpt: "this is jasmin's projects page!"
intro: 
  - excerpt: "these are my projects. aren't they the coolest?!"
feature_row:
  - image_path: /assets/images/EvieGrad2.jpg
    image_caption: "image courtesy of dr. evie"
    alt: "placeholder image 2"
    title: "placeholder image left aligned"
    excerpt: 'this is some sample content that goes here with **markdown** formatting. left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "read more"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/eviegrad.png
    alt: "placeholder image 2"
    title: "placeholder image right aligned"
    excerpt: 'this is some sample content that goes here with **markdown** formatting. right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "read more"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/EvieGrad2.jpg
    alt: "placeholder image 2"
    title: "placeholder image center aligned"
    excerpt: 'this is some sample content that goes here with **markdown** formatting. centered with `type="center"`'
    url: "#test-link"
    btn_label: "read more"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="left" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}