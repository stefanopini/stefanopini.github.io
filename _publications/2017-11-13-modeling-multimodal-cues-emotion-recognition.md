---
title: "Modeling Multimodal Cues in a Deep Learning-based Framework for Emotion Recognition in the Wild"
collection: publications
permalink: /publication/2017-11-13-modeling-multimodal-cues-emotion-recognition
excerpt: ''
date: 2017-11-13
venue: 'Proceedings of the 19th ACM International Conference on Multimodal Interaction (ICMI)'
paperdoi: '10.1145/3136755.3143006'
paperurl: 'https://dl.acm.org/doi/10.1145/3136755.3143006'
paperpdf: 'https://iris.unimore.it/retrieve/handle/11380/1144999/186266/2017-icmi.pdf'
authors: 'Stefano Pini, Olfa Ben Ahmed, Marcella Cornia, Lorenzo Baraldi, Rita Cucchiara, Benoit Huet'
presentation: '/files/icmi2017.pdf'
---
### Abstract
In this paper, we propose a multimodal deep learning architecture for emotion recognition in video regarding our
participation to the audio-video based sub-challenge of the Emotion Recognition in the Wild 2017 challenge. 
Our model combines cues from multiple video modalities, including static facial features, motion patterns related to
the evolution of the human expression over time, and audio information.
Specifically, it is composed of three sub-networks trained separately: the first and second ones extract static visual
features and dynamic patterns through 2D and 3D Convolutional Neural Networks (CNN), while the third one consists in a 
pretrained audio network which is used to extract useful deep acoustic signals from video. 
In the audio branch, we also apply Long Short Term Memory (LSTM) networks in order to capture the temporal evolution of 
the audio features. To identify and exploit possible relationships among different modalities, we propose a fusion 
network that merges cues from the different modalities in one representation.
The proposed architecture outperforms the challenge baselines (38.81% and 40.47%): we achieve an accuracy of 50.39% 
and 49.92% respectively on the validation and the testing data.

### Recommended citation
```
@inproceedings{pini2017modeling,
  title={Modeling multimodal cues in a deep learning-based framework for emotion recognition in the wild},
  author={Pini, Stefano and Ahmed, Olfa Ben and Cornia, Marcella and Baraldi, Lorenzo and Cucchiara, Rita and Huet, Benoit},
  booktitle={Proceedings of the 19th ACM International Conference on Multimodal Interaction},
  pages={536--543},
  year={2017}
}
```
