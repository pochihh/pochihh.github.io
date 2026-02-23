---
title: "Luxo Jr. - The Robotic Lamp (6-DoF Interactive Platform)"
excerpt: "A 6-DoF robotic lamp that senses and responds to human presence. Built on ROS 2 and powered by 3D perception, this project explores how expressive motion can emerge from minimal robotic embodiment.<br/><img src='/images/Luxo_Jr.jpg' width='350'  >"
collection: projects
---

Inspired by Kevin Gene V. Gim's [robotic work](https://www.researchgate.net/profile/Kevin-Gim?_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIn19), we built a **6-degree-of-freedom robotic lamp** that explores expressive, perception-driven interaction through minimalist embodiment.

Instead of using a full bipedal configuration, this design adopts a **single leg mechanism**, mounted upside-down to achieve a naturally stable base while preserving rich motion capability.

<!-- ![](/images/Luxo_Jr.jpg) -->
<img src="/images/Luxo_Jr.jpg" width="500">

### **System Overview**

The entire system runs on **ROS 2**, deployed on a Raspberry Pi.

It integrates:
- A 3D depth camera for spatial perception
- A smart light bulb for expressive feedback
This allows the lamp to **sense its surroundings and respond in real time**, transforming it from a passive object into an interactive agent.

<!-- ![](/images/open_chain.png) -->
<img src="/images/open_chain.png" width="350">

### **Current Capabilities**

At its current stage, the system supports:

- **Hand detection**
- **3D tracking**

This enables the lamp to react to nearby human presence and movement.

Future development will focus on:
- richer sensing modalities
- more expressive and vivid motion responses

— pushing the system beyond functional robotics toward character-like interaction.

<!-- ![](/images/hand_detection_xyz.jpg) -->
<img src="/images/hand_detection_xyz.jpg" width="500">

Don't forget to check out this [video demo](LINk)!

<iframe width="450" height="450" src="https://www.youtube.com/embed/YQmZfHJ2zCw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
