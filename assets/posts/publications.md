Publications
========
### Kimera: an Open-Source Library for Real-Time Metric-Semantic Localization and Mapping (ICRA 2019)
Kimera is a C++ library for real-time metric-semantic simultaneous localization and mapping, which uses camera images and inertial data to build a semantically annotated 3D mesh of the environment. Kimera is modular, ROS-enabled, and runs on a CPU. My part in this project was the robust pose graph optimization backend, which is a genral library that can also be used for other frontends. 

[github](https://github.com/MIT-SPARK/Kimera), [pdf](https://arxiv.org/pdf/1910.02490.pdf)

### DOOR-SLAM: Distributed, Online, and Outlier Resilient SLAM for Robotic Teams (ICRA 2019)
DOOR-SLAM is a fully distributed SLAM system with an outlier rejection mechanism that can work with less conservative parameters. DOOR-SLAM is based on peer-to-peer communication and does not require full connectivity among the robots. My part in this project is the adaptation of the pipeline for a lidar frontend, and conducting experiments using the DARPA SubT tunnel circuit dataset collected by team CoSTAR. 

[github](https://github.com/MISTLab/DOOR-SLAM), [pdf](https://arxiv.org/pdf/1909.12198.pdf)

### LAMP: Large-Scale Autonomous Mapping and Positioning for Exploration of Perceptually-Degraded Subterranean Environments (ICRA 2019)
Implementation and testing of a lidar-based multi-robot SLAM system developed in the context of the DARPA Subterranean Challenge with extensive evaluation in large-scale, challenging subterranean environments, including the results obtained in the Tunnel Circuit of the DARPA Subterranean Challenge.