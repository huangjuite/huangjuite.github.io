---
layout: page
title: "Virtual SubT"
description: deep reinforcement learning
img: /assets/img/virtual-subt-bg.png
importance: 0
category: Projects
---

Deep reinforcement learning (RL) has shown remarkable success on a variety of tasks to learn from mistakes. To learn collision-free policies for unmanned vehicles, deep RL has been trained with various data modalities including RGB, depth images, and LiDAR point clouds without the use of classic map-localize-plan approaches. However, to operate in constrained passages under subterranean environments, existing methods suffer from degraded sensing conditions, such as smoke and other obscurants, that impair observations from camera and LiDAR. We propose sim-to-real, LiDAR-to-mmWave (millimeter wave radar) input modality for deep RL to overcome these challenges. We show that the trained models generalize from simulation to the real world, as well as LiDAR-to-mmWave transferring, despite the low spatial resolution and noisy inputs. Evaluations are carried out in underground environments, including a basement floor and large-scale testbeds in the Tunnel and Urban Circuits of the DARPA Subterranean Challenge. We provide an open dataset of real-world data for further comparisons.

<div class="mt-2">
  <a href="https://arg-nctu.github.io/projects/deeprl-ugv.html" class="btn btn-sm z-depth-0" role="button">Web Page</a>
  <a href="/assets/pdf/virtual-subt-mvoa.pdf" class="btn btn-sm z-depth-0" role="button">Paper (PDF)</a>
</div>

<iframe style="width: 100%; aspect-ratio: 16 / 9; border: 0;" src="https://player.vimeo.com/video/396074962" allow="autoplay; fullscreen" allowfullscreen></iframe>

<div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 1rem; margin-top: 1rem;">
{% for i in (1..9) %}
  <img src="/images/virtual-subt/virtual-subt{{ i }}.png" alt="Virtual SubT" style="width: 100%; border-radius: 6px;" />
{% endfor %}
</div>
