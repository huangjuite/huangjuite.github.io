---
layout: page
title: "Space Oddity"
description: Java project - Universe Simulator
img: /assets/img/space-teaser.png
importance: 4
category: Projects
---

This is my final project for the Java programming class. We built a simulator that can build your own universe and explore the effect of gravity.

<div class="mt-2">
  <a href="https://github.com/huangjuite/Space-Oddity" class="btn btn-sm z-depth-0" role="button">Github</a>
</div>

<div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 1rem; margin-top: 1rem;">
{% for i in (1..13) %}
  {% assign n = i | prepend: '00' | slice: -2, 2 %}
  <img src="/images/space/space{{ n }}.png" alt="Space Oddity" style="width: 100%; border-radius: 6px;" />
{% endfor %}
</div>
