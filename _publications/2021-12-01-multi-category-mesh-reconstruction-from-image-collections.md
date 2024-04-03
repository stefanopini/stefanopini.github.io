---
title: "Multi-Category Mesh Reconstruction From Image Collections"
collection: publications
permalink: /publication/2021-12-01-multi-category-mesh-reconstruction-from-image-collections
excerpt: ''
date: 2021-12-01
venue: 'International Conference on 3D Vision (3DV)'
paperdoi: '10.1109/3DV53792.2021.00139'
paperurl: 'https://arxiv.org/abs/2110.11256'
paperpdf: 'https://drive.google.com/file/d/1KuYjyf85yM4jigBS-QQpelodgFYJQp3V/view?usp=sharing'
paperpdfsupp: 'https://drive.google.com/file/d/1eRgl__F4Z8x_2rnfIe_XJLmLNLWw7Q0S/view?usp=sharing'
authors: "Alessandro Simoni*, Stefano Pini*, Roberto Vezzani, Rita Cucchiara"
projectpage: 'https://github.com/aimagelab/mcmr'
code: 'https://github.com/aimagelab/mcmr'
selected: true
---
&#42; Denotes equal contribution.

### Abstract
Recently, learning frameworks have shown the capability of inferring the accurate shape, pose, and texture of an object from a single RGB image.
However, current methods are trained on image collections of a single category in order to exploit specific priors, and they often make use of category-specific 3D templates.
In this paper, we present an alternative approach that infers the textured mesh of objects combining a series of deformable 3D models and a set of instance-specific deformation, pose, and texture.
Differently from previous works, our method is trained with images of multiple object categories using only foreground masks and rough camera poses as supervision.
Without specific 3D templates, the framework learns category-level models which are deformed to recover the 3D shape of the depicted object.
The instance-specific deformations are predicted independently for each vertex of the learned 3D mesh, enabling the dynamic subdivision of the mesh during the training process. 
Experiments show that the proposed framework can distinguish between different object categories and learn category-specific shape priors in an unsupervised manner.
Predicted shapes are smooth and can leverage from multiple steps of subdivision during the training process, obtaining comparable or state-of-the-art results on two public datasets.
Models and code are publicly released.

### Recommended citation
{% raw %}
```
@inproceedings{simoni2021multi,
  title={Multi-Category Mesh Reconstruction From Image Collections},
  author={Simoni, Alessandro and Pini, Stefano and Vezzani, Roberto and Cucchiara, Rita},
  booktitle={9th International Conference on 3D Vision},
  publisher={{IEEE}},
  year={2020}
}
```
{% endraw %}
