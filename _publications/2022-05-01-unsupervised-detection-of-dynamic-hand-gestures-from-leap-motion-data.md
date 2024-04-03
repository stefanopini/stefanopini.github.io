---
title: "Unsupervised Detection of Dynamic Hand Gestures from Leap Motion Data"
collection: publications
permalink: /publication/2022-05-01-unsupervised-detection-of-dynamic-hand-gestures-from-leap-motion-data
excerpt: ''
date: 2022-05-01
venue: 'International Conference on Image Analysis and Processing (ICIAP)'
paperdoi: 10.1007/978-3-031-06427-2_35
paperurl:
paperpdf: https://drive.google.com/file/d/1YNNn3LyrvfdCrYmcCQ869S2aLqOYT6Cc/view?usp=sharing
paperpdfsupp: 
authors: "Andrea D'Eusanio, Stefano Pini, Guido Borghi, Alessandro Simoni, Roberto Vezzani"
projectpage: 'https://aimagelab.ing.unimore.it/imagelab/researchActivity.asp?idActivity=032'
code: 
---

### Abstract
The effective and reliable detection and classification of dynamic hand gestures is a key element for building Natural User Interfaces, 
systems that allow the users to interact using free movements of their body instead of traditional mechanical tools. 
However, methods that temporally segment and classify dynamic gestures usually rely on a great amount of labeled data, 
including annotations regarding the class and the temporal segmentation of each gesture. 
In this paper, we propose an unsupervised approach to train a Transformer-based architecture that learns to detect dynamic hand gestures in a continuous temporal sequence. 
The input data is represented by the 3D position of the hand joints, along with their speed and acceleration, collected through a Leap Motion device. 
Experimental results show a promising accuracy on both the detection and the classification task and that only limited computational power is required, 
confirming that the proposed method can be applied in real-world applications.

### Recommended citation
{% raw %}
```
@inproceedings{deusanio2022unsupervised,
  title={Unsupervised Detection of Dynamic Hand Gestures from Leap Motion Data},
  author={D’Eusanio, Andrea and Pini, Stefano and Borghi, Guido and Simoni, Alessandro and Vezzani, Roberto},
  booktitle={International Conference on Image Analysis and Processing},
  pages={414--424},
  year={2022},
  organization={Springer}
}
```
{% endraw %}
