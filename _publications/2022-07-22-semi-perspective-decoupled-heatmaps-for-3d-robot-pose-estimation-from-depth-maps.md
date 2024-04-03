---
title: "Semi-Perspective Decoupled Heatmaps for 3D Robot Pose Estimation from Depth Maps"
collection: publications
permalink: /publication/2022-10-23-semi-perspective-decoupled-heatmaps-for-3d-robot-pose-estimation-from-depth-maps
excerpt: ''
date: 2022-07-22
venue: 'IEEE Robotics and Automation Letters (RA-L) and IROS 2022'
paperdoi: '10.1109/LRA.2022.3193225'
paperurl: 'https://arxiv.org/abs/2207.02519'
paperpdf: 'https://iris.unimore.it/retrieve/handle/11380/1281858/431701/SPDH_RA-L_2022.pdf'
paperpdfsupp:
authors: "Alessandro Simoni, Stefano Pini, Guido Borghi, Roberto Vezzani"
projectpage: 'https://aimagelab.ing.unimore.it/go/rpe'
code: 'https://github.com/aimagelab/rpe_spdh'
selected: true
---

### Abstract
Knowing the exact 3D location of workers and robots in a collaborative environment enables several real applications, 
such as the detection of unsafe situations or the study of mutual interactions for statistical and social purposes. 
In this letter, we propose a non-invasive and light-invariant framework based on depth devices and deep neural networks to estimate the 3D pose of robots from an external camera. 
The method can be applied to any robot without requiring hardware access to the internal states. 
We introduce a novel representation of the predicted pose, namely Semi-Perspective Decoupled Heatmaps (SPDH), to accurately compute 3D joint locations in world coordinates adapting efficient deep networks designed for the 2D Human Pose Estimation. 
The proposed approach, which takes as input a depth representation based on XYZ coordinates, can be trained on synthetic depth data and applied to real-world settings without the need for domain adaptation techniques. 
To this end, we present the SimBa dataset, based on both synthetic and real depth images, and use it for the experimental evaluation. 
Results show that the proposed approach, made of a specific depth map representation and the SPDH, overcomes the current state of the art.

### Recommended citation
{% raw %}
```
@article{simoni2022semi,
  title={Semi-Perspective Decoupled Heatmaps for 3D Robot Pose Estimation from Depth Maps},
  author={Simoni, Alessandro and Pini, Stefano and Borghi, Guido and Vezzani, Roberto},
  journal={IEEE Robotics and Automation Letters},
  volume={7},
  number={4},
  pages={11569--11576},
  year={2022},
  publisher={IEEE}
}
```
{% endraw %}
