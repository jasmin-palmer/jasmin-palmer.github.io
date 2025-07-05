---
title: "News"
layout: splash
permalink: /news/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash-image.jpg
  actions:
    - label: "Check out my ORCiD"
      url: "https://orcid.org/0009-0004-5337-8143"
  caption: "J. E. Palmer, et al., 2024"
excerpt: "This is Jasmin's Research Page!"
intro: 
  - excerpt: "This is my research. It's revolutionary!"
feature_row:
  - image_path: /assets/images/EvieGrad2.jpg
    image_caption: "Image courtesy of Dr. Evie"
    alt: "placeholder image 2"
    title: "Stanford Reserach"
    excerpt: 'My PhD work at Stanford University. '
    url: "/research_Stanford/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/EvieGrad.png
    alt: "placeholder image 2"
    title: "JHU Research"
    excerpt: "My work at Johns Hopkins University"
    url: "/research_JHU/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/EvieGrad2.jpg
    alt: "placeholder image 2"
    title: "MIT UROP Research"
    excerpt: "My UROP projects at MIT"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="left" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}