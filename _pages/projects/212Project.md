---
layout: single
title: "2.12 Introduction to Robotics Final Project"
permalink: /projects/212Project/
author_profile: true
header:
  overlay_color: "#8d64a3"
categories:
  - Projects
tags:
  - Robotics
  - Solidworks
  - CAD
toc: true
toc_sticky: true
toc_label: "Table of Contents"
toc_icon: "cog"
read_time: true
comments: false
share: false
related: true
intro: 
  - excerpt: "Introduction to Robotics"
---

## Course Description (Excerpt)

Cross-disciplinary studies in robot mechanics and intelligence. Emphasizes physical understanding of robot kinematics and dynamics, differential motion and energy method, design and control of robotic arms and mobile robots, and actuators, drives, and transmission. Second half of course focuses on algorithmic thinking and computation, computer vision and perception, planning and control for manipulation, localization and navigation, machine learning for robotics, and human-robot systems. Weekly laboratories include brushless DC motor control, design and fabrication of robotic arms and vehicles, robot vision and navigation, and programming and system integration using Robot Operating System (ROS). Group term project builds intelligent robots for specific applications of interest. 

## About the Project

Our group was asked to develop an assistive robot that can work side by side with a patient for daily chores.

## My Contributions

I was responsible for the design and maufacture of the 1-DoF, servo-controlled gripper end effector for the robot arm. 

The scenario presented to us was:

* A hemiplegic patient is unable to move one arm
* The patient needs assistance in dressing and bed-making

The robot must be desinged in a way so that it can complte three tasks:

1. A robot arm assists the patient in pulling a drawer together with him/her, so the patient can take a garment out of the drawer
2. The robot arm also assists the patient in donning a garment
3. A mobile robot fetches a blanket and covers a bed with the blanket together with the patient

{% capture fig_img %}
![Foo]({{ '/assets/images/212_Project/Gripper Assembly with Motor.png' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Screenshot of Gripper CAD.</figcaption>
</figure>


{% capture fig_img %}
![Foo]({{ '/assets/images/212_Project/Gripper_Pose1.png' | relative_url }})
{% endcapture %}
{% capture fig_img %}
![Foo]({{ '/assets/images/212_Project/Gripper_Pose2.png' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>The gripper</figcaption>
</figure>


{% capture fig_img %}
![Foo]({{ '/assets/images/212_Project/2.12_Selfie.png' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Robot Selfie!!</figcaption>
</figure>

## Skills

Computer-Aided Design (Solidworks), Laser Cutting, 3D Printing, Arduino, C++