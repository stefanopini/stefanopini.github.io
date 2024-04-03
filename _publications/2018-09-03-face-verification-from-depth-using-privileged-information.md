---
title: "Face Verification from Depth using Privileged Information"
collection: publications
permalink: /publication/2018-09-03-face-verification-from-depth-using-privileged-information
excerpt: ''
date: 2018-09-03
venue: 'British Machine Vision Conference (BMVC)'
paperdoi:
paperurl: 'http://bmvc2018.org/contents/papers/0410.pdf'
paperpdf: 'http://bmvc2018.org/contents/papers/0410.pdf'
authors: 'Guido Borghi, Stefano Pini, Filippo Grazioli, Roberto Vezzani, Rita Cucchiara'
---
### Abstract
In this paper, a deep Siamese architecture for depth-based face verification is presented.
The proposed approach efficiently verifies if two face images belong to the same person while handling a great variety 
of head poses and occlusions. The architecture, namely JanusNet, consists in a combination of a depth, a RGB and a 
hybrid Siamese network. During the training phase, the hybrid network learns to extract complementary mid-level 
convolutional features which mimic the features of the RGB network, simultaneously leveraging on the light invariance 
of depth images. At testing time, the model, relying only on depth data, achieves state-of-art results and real time 
performance, despite the lack of deep-oriented depth-based datasets.

### Recommended citation
```
@inproceedings{borghi2018face,
  title={Face Verification from Depth using Privileged Information},
  author={Borghi, Guido and Pini, Stefano and Grazioli, Filippo and Vezzani, Roberto and Cucchiara, Rita},
  booktitle={British Machine Vision Conference (BMVC)},
  pages={303},
  year={2018}
}
```
