---
layout: single
title: "LAMP"
blob: "Robust multi-robot Lidar-base SLAM System designed for Team CoSTAR for the DARPA Subterranean Challenge<br/><img src='/images/projects/lamp.png'>"
collection: SLAM
last_updated: 2022-06-30
---

LAMP (Large-Scale Autonomous Mapping and Positioning for Exploration of Perceptually-Degraded Subterranean Environments)
multi-robot LiDAR SLAM solution we deployed during the [DARPA Subterranean Challenge](https://www.darpa.mil/program/darpa-subterranean-challenge).
It is a computationally efficient and outlier-resilient centralized multi-robot SLAM system that is adaptable to different
input odometry sources for operation in large-scale environments.

We open sourced the code along with raw and processed multi-robot datasets from scenarios we tested in when preparing for the challenge.

Please check out our [repo](https://github.com/NeBula-Autonomy/LAMP).

The initial version of the system is described in {% cite Ebadi20icra-LAMP %} and the final system is detailed in {% cite Chang22ral-LAMP2 %}.

<p align="center">
  <img src="/images/projects/lamp.png" />
</p>

{% bibliography --cited %}