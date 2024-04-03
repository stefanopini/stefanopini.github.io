---
title: "Safe Real-World Autonomous Driving by Learning to Predict and Plan with a Mixture of Experts"
collection: publications
permalink: /publication/2022-11-03-safe-real-world-autonomous-driving-by-learning-to-predict-and-plan-with-a-mixture-of-experts
excerpt: ''
date: 2023-05-01
venue: '2023 IEEE International Conference on Robotics and Automation (ICRA) (previously presented at 2022 NeurIPS ML4AD workshop)'
paperdoi: 10.1109/ICRA48891.2023.10160992
paperurl: 'https://doi.org/10.1109/ICRA48891.2023.10160992'
paperpdf: 'https://arxiv.org/pdf/2211.02131'
paperpdfsupp:
authors: "Stefano Pini, Christian S. Perone, Aayush Ahuja, Ana Sofia Rufino Ferreira, Moritz Niendorf, Sergey Zagoruyko"
projectpage: 'https://woven.mobi/safepathnet'
code: 
selected: true
---

### Abstract
The goal of autonomous vehicles is to navigate public roads safely and comfortably. To enforce safety, 
traditional planning approaches rely on handcrafted rules to generate trajectories. 
Machine learning-based systems, on the other hand, scale with data and are able to learn more complex behaviors. 
However, they often ignore that agents and self-driving vehicle trajectory distributions can be leveraged to improve safety. 
In this paper, we propose modeling a distribution over multiple future trajectories for both the self-driving vehicle and other road agents, 
using a unified neural network architecture for prediction and planning. During inference, 
we select the planning trajectory that minimizes a cost taking into account safety and the predicted probabilities. 
Our approach does not depend on any rule-based planners for trajectory generation or optimization, 
improves with more training data and is simple to implement. 
We extensively evaluate our method through a realistic simulator and show that the predicted trajectory distribution corresponds to different driving profiles. 
We also successfully deploy it on a self-driving vehicle on urban public roads, confirming that it drives safely without compromising comfort. 
The code for training and testing our model on a public prediction dataset and the video of the road test are available 
at <a href="https://woven.mobi/safepathnet" target="_blank">this https URL</a>.

### Recommended citation
{% raw %}
```
@article{pini2022safe,
  title={Safe Real-World Autonomous Driving by Learning to Predict and Plan with a Mixture of Experts},
  author={Pini, Stefano and Perone, Christian S and Ahuja, Aayush and Ferreira, Ana Sofia Rufino and Niendorf, Moritz and Zagoruyko, Sergey},
  booktitle={2023 IEEE International Conference on Robotics and Automation (ICRA)},
  pages={10069--10075},
  year={2023},
  organization={IEEE}
}
```
{% endraw %}
