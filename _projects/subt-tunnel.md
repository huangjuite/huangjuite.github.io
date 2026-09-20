---
layout: page
title: DARPA SubT Challenge — Tunnel Circuit
description: Tunnel Circuit, Pittsburgh, 2019
img: /assets/img/subt-tunnel-bg.jpg
importance: 1
category: Robotics Challenge
---

The DARPA Subterranean (SubT) Challenge aims to develop innovative technologies that would augment operations underground. The SubT Challenge explores new approaches to rapidly map, navigate, search, and exploit complex underground environments, including human-made tunnel systems, urban underground, and natural cave networks.

<div class="mt-2">
  <a href="https://www.subtchallenge.com/" class="btn btn-sm z-depth-0" role="button">SubT Challenge web page</a>
</div>

### Our work

In the SubT Tunnel Circuit, my work was to make sure the communication between our robot and base station worked reliably. We used multiple frequencies of radio communication including 2.4/5 GHz WiFi and a 915 MHz LoRa module. We designed our transmission packets and mechanisms to be able to monitor our robot in an underground tunnel through limited communication.

<div class="mt-2">
  <a href="https://arg-nctu.github.io/SubT/" class="btn btn-sm z-depth-0" role="button">Team web page</a>
  <a href="https://arxiv.org/abs/1910.14275" class="btn btn-sm z-depth-0" role="button">arXiv</a>
</div>

<div class="row">
    <div class="col-sm-6 mt-3">
        <iframe style="width: 100%; aspect-ratio: 16 / 9; border: 0;" src="https://www.youtube.com/embed/ySDXnvPQILY" allowfullscreen></iframe>
    </div>
    <div class="col-sm-6 mt-3">
        <iframe style="width: 100%; aspect-ratio: 16 / 9; border: 0;" src="https://www.youtube.com/embed/sBujR2XJSSY" allowfullscreen></iframe>
    </div>
    <div class="col-sm-6 mt-3">
        <iframe style="width: 100%; aspect-ratio: 16 / 9; border: 0;" src="https://www.youtube.com/embed/UovOCe-2xr4" allowfullscreen></iframe>
    </div>
</div>

<div class="row">
{% for i in (1..10) %}
    <div class="col-sm-4 mt-3">
        <img src="/images/subt-tunnel/subt-tunnel{{ i }}.jpg" alt="SubT Tunnel Circuit" class="img-fluid rounded z-depth-1" />
    </div>
{% endfor %}
</div>
<div class="caption">Tunnel Circuit — Pittsburgh — 2019</div>
