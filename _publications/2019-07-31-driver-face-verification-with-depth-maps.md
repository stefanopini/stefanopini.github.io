---
title: "Driver Face Verification with Depth Maps"
collection: publications
permalink: /publication/2019-07-31-driver-face-verification-with-depth-maps
excerpt: ''
date: 2019-07-31
venue: 'Sensors'
paperdoi: '10.3390/s19153361'
paperurl: 'https://www.mdpi.com/1424-8220/19/15/3361'
paperpdf: 'https://www.mdpi.com/1424-8220/19/15/3361/pdf'
authors: 'Guido Borghi, Stefano Pini, Roberto Vezzani, Rita Cucchiara'
---
### Abstract
Face verification is the task of checking if two provided images contain the face of the same person or not. In this 
work, we propose a fully-convolutional Siamese architecture to tackle this task, achieving state-of-the-art results on 
three publicly-released datasets, namely Pandora, High-Resolution Range-based Face Database (HRRFaceD), and 
CurtinFaces. The proposed method takes depth maps as the input, since depth cameras have been proven to be more 
reliable in different illumination conditions. Thus, the system is able to work even in the case of the total or 
partial absence of external light sources, which is a key feature for automotive applications. From the algorithmic 
point of view, we propose a fully-convolutional architecture with a limited number of parameters, capable of dealing 
with the small amount of depth data available for training and able to run in real time even on a CPU and embedded 
boards. The experimental results show acceptable accuracy to allow exploitation in real-world applications with 
in-board cameras. Finally, exploiting the presence of faces occluded by various head garments and extreme head poses 
available in the Pandora dataset, we successfully test the proposed system also during strong visual occlusions. The 
excellent results obtained confirm the efficacy of the proposed method. 

### Recommended citation
```
@article{borghi2019driver,
  title={Driver face verification with depth maps},
  author={Borghi, Guido and Pini, Stefano and Vezzani, Roberto and Cucchiara, Rita},
  journal={Sensors},
  volume={19},
  number={15},
  pages={3361},
  year={2019},
  publisher={Multidisciplinary Digital Publishing Institute}
}
```
