---
layout: page
title: "Balanbot"
description: two-wheeled self-balanced vehicle
img: /assets/img/balanbot-teaser.png
importance: 3
category: Projects
---

This project is for a control systems and design class. We built a two-wheeled self-balancing bot that can be remote controlled through smartphones or navigate to designated locations. The balanbot has wheel encoders, an inertial measurement unit, and Bluetooth, integrated with an Arduino. We use mathematical control theory to write the program to balance and control the robot at the same time.

<div class="mt-2">
  <a href="https://github.com/huangjuite/Balanbot" class="btn btn-sm z-depth-0" role="button">Balanbot Github</a>
  <a href="https://github.com/huangjuite/control_app" class="btn btn-sm z-depth-0" role="button">App Github</a>
</div>

<div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 1rem; margin-top: 1rem;">
{% for i in (1..42) %}
  {% assign n = i | prepend: '00' | slice: -2, 2 %}
  <img src="/images/balanbot/meet{{ n }}.png" alt="Balanbot" style="width: 100%; border-radius: 6px;" />
{% endfor %}
</div>
