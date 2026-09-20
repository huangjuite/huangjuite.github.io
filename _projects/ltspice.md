---
layout: page
title: "Passive Component Circuit Simulator"
description: c/c++ project
img: /assets/img/ltspice-teaser.png
importance: 5
category: Projects
---

This is my final project for the Advanced Object Oriented Programming class. We built the simulator with a user interface using Qt. The simulator can solve the steady state of a passive component circuit.

<div class="mt-2">
  <a href="https://github.com/huangjuite/Electronic_Circuit_Simulation" class="btn btn-sm z-depth-0" role="button">Github</a>
</div>

<div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 1rem; margin-top: 1rem;">
{% for i in (1..20) %}
  {% assign n = i | prepend: '00' | slice: -2, 2 %}
  <img src="/images/ltspice/qt{{ n }}.png" alt="passive component circuit simulator" style="width: 100%; border-radius: 6px;" />
{% endfor %}
</div>
