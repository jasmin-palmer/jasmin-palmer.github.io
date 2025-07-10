---
layout: single
title: "Medical Augmented Reality Summer School (MARSS) 2024 Hacakthon"
permalink: /projects/marss2024Hackathon/
author_profile: true
header:
  overlay_color: "#8d64a3"
categories:
  - Projects
tags:
  - Mixed Reality
  - Medical Simluations
  - Haptics
toc: true
toc_sticky: true
toc_label: "Table of Contents"
toc_icon: "cog"
read_time: true
comments: false
share: false
related: true
---

## About MARSS

[MARSS 2024 Website](https://medicalaugmentedreality.org/mar2024.html){: .btn .btn--primary}

## About the Project

We were tasked with developing a medical mixed reality simulation integrating haptic and auditory augmentations for laproscopic procedures. The MARSS staff provided a demo Unity scene containing procine anatomy and the laparoscopic tools' pose were controlled by pre-recorded tracking data from an *in vivo* procedure on a pig abdomen.

### Background:

Human perception during minimally invasive surgery is often limited, making these procedures, despite their many advantages, less than optimal and highly challenging for surgeons. This project aims to improve surgical performance by providing comprehensive multimodal feedback on both the anatomical structures and the surgeon’s interaction with them through surgical tools.

### Goal:
* Develop an AR application for multimodal interaction with anatomical structures in AR laparoscopy.
* Design and implement multimodal feedback, particularly auditory and haptic, for enhancing tool-tissue interaction.

## My Contributions

I implemented the Finger-Proxy haptic rendering algorithm (Ruspini et al., 1997) in Unity and used the computed forces to control a custom servo-driven haptic device (["Palmer, et al., 2022](https://ieeexplore.ieee.org/document/9981392)) via serial communication, enabling real-time tactile interaction with virtual objects.

<!--
[MARSS Project GitHub](https://github.com/jpalms1/RAD206-FinalProject){: .btn .btn--primary}
-->

<figure class="full">
  <a href="/assets/images/MARSS2024_Project/MARSS2024-FingerProxy-Cropped.png"><img src="/assets/images/MARSS2024_Project/MARSS2024-FingerProxy-Cropped.png"></a>
  <figcaption>Screenshot of Virtual Porcine Anatomy in Unity Scene.</figcaption>
</figure>

## Skills

Mixed Reality, Medical Simulaitons, Unity, C#, Haptic Rendering, Arduino, C++, 3D Printing