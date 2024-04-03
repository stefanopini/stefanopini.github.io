---
title: "A Systematic Comparison of Depth Map Representations for Face Recognition"
collection: publications
permalink: /publication/2021-01-31-a-systematic-comparison-of-depth-map-representations-for-face-recognition
excerpt: ''
date: 2021-01-31
venue: 'Sensors'
paperdoi: '10.3390/s21030944'
paperurl: 'https://www.mdpi.com/1424-8220/21/3/944'
paperpdf: 'https://www.mdpi.com/1424-8220/21/3/944/pdf'
authors: "Stefano Pini, Guido Borghi, Roberto Vezzani, Davide Maltoni, Rita Cucchiara"
selected: true
---
### Abstract
Nowadays, we are witnessing the wide diffusion of active depth sensors. However, the generalization capabilities and 
performance of the deep face recognition approaches that are based on depth data are hindered by the different sensor 
technologies and the currently available depth-based datasets, which are limited in size and acquired through the same 
device. In this paper, we present an analysis on the use of depth maps, as obtained by active depth sensors and deep 
neural architectures for the face recognition task. We compare different depth data representations (depth and normal 
images, voxels, point clouds), deep models (two-dimensional and three-dimensional Convolutional Neural Networks, 
PointNet-based networks), and pre-processing and normalization techniques in order to determine the configuration that 
maximizes the recognition accuracy and is capable of generalizing better on unseen data and novel acquisition settings. 
Extensive intra- and cross-dataset experiments, which were performed on four public databases, suggest that 
representations and methods that are based on normal images and point clouds perform and generalize better than other 
2D and 3D alternatives. Moreover, we propose a novel challenging dataset, namely MultiSFace, in order to specifically 
analyze the influence of the depth map quality and the acquisition distance on the face recognition accuracy.

### Recommended citation
```
@article{pini2021systematic,
  title={A Systematic Comparison of Depth Map Representations for Face Recognition},
  author={Pini, Stefano and Borghi, Guido and Vezzani, Roberto and Maltoni, Davide and Cucchiara, Rita},
  journal={Sensors},
  volume={21},
  number={3},
  pages={944},
  year={2021},
  publisher={Multidisciplinary Digital Publishing Institute}
}
```
