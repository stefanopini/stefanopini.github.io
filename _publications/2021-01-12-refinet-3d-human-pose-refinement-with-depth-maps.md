---
title: "RefiNet: 3D Human Pose Refinementwith Depth Maps"
collection: publications
permalink: /publication/2021-01-12-refinet-3d-human-pose-refinement-with-depth-maps
excerpt: ''
date: 2020-12-31
venue: '25th International Conference of Pattern Recognition (ICPR)'
paperdoi: '10.1109/ICPR48806.2021.9412451'
paperurl:
paperpdf: 'https://iris.unimore.it/retrieve/handle/11380/1212262/282582/ICPR_2020_Human_Pose_Estimation_compressed.pdf'
authors: "Andrea D'Eusanio, Stefano Pini, Guido Borghi, Roberto Vezzani, Rita Cucchiara"
projectpage: 'https://aimagelab.ing.unimore.it/go/3d-human-pose-refinement'
code: 'https://github.com/aimagelab/RefiNet'
selected: true
---
***Winner of the Best Scientific Paper Award***  
(Track 2: Biometrics, Human Analysis and Behavior Understanding)

### Abstract
Human Pose Estimation is a fundamental task for many applications in the Computer Vision community and it has been 
widely investigated in the 2D domain, i.e. intensity images. Therefore, most of the available methods for this task are 
mainly based on 2D Convolutional Neural Networks and huge manually-annotated RGB datasets, achieving stunning results. 
In this paper, we propose RefiNet, a multi-stage framework that regresses an extremely-precise 3D human pose estimation 
from a given 2D pose and a depth map. The framework consists of three different modules, each one specialized in a 
particular refinement and data representation, i.e. depth patches, 3D skeleton and point clouds. Moreover, we collect a 
new dataset, namely Baracca, acquired with RGB, depth and thermal cameras and specifically created for the automotive 
context. Experimental results confirm the quality of the refinement procedure that largely improves the human pose 
estimations of off-the-shelf 2D methods. 

### Recommended citation
{% raw %}
```
@inproceedings{d2020refinet,
  title={{RefiNet}: 3D Human Pose Refinementwith Depth Maps},
  author={D'Eusanio, Andrea and Pini, Stefano and Borghi, Guido and Vezzani, Roberto and Cucchiara, Rita},
  booktitle={25th International Conference of Pattern Recognition},
  year={2020}
}
```
{% endraw %}
