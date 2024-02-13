---
layout: single
title: "Kimera-Multi"
blob: "A System for Distributed Multi-Robot Metric-Semantic Simultaneous Localization and Mapping<br/><img src='/images/projects/kimera_multi.png'>"
collection: SLAM
last_updated: 2023-03-01
---

Kimera-Multi is a multi-robot system that was first presented in {% cite Chang21icra-KimeraMulti %}.
It is built to be robust to incorrect inter and intra-robot loop closures resulting from perceptual aliasing, 
fully distributed and only relies on local (peer-to-peer) communication to achieve distributed localization and mapping,
and builds a globally consistent metric-semantic 3D mesh model of the environment in real-time.
Kimera-Multi is field tested in many indoor and outdoor environments.
We not only open-source the code, but also release a few large-scale hybrid indoor/outdoor datasets collected on the MIT campus.

Please check out our [repo](https://github.com/MIT-SPARK/Kimera-Multi).

For a detailed description of the project, please refer to {% cite Tian22tro-KimeraMulti %}.
{% cite Tian23iros-KimeraMultiExperiments %} provide a deeper dive into the system and real world experiments.

<p align="center">
  <img src="/images/projects/kimera_multi.png" />
</p>

{% bibliography --cited %}