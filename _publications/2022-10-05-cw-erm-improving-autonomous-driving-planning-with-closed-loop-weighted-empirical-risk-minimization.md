---
title: "CW-ERM: Improving Autonomous Driving Planning with Closed-loop Weighted Empirical Risk Minimization"
collection: publications
permalink: /publication/2022-10-05-cw-erm-improving-autonomous-driving-planning-with-closed-loop-weighted-empirical-risk-minimization
excerpt: ''
date: 2022-10-05
venue: '2022 NeurIPS ML4AD workshop'
paperdoi: 
paperurl: 'https://arxiv.org/abs/2210.02174'
paperpdf: 'https://arxiv.org/pdf/2210.02174'
paperpdfsupp:
authors: "Eesha Kumar, Yiming Zhang, Stefano Pini, Simon Stent, Ana Sofia Rufino Ferreira, Sergey Zagoruyko, Christian S. Perone"
projectpage: 'https://woven.mobi/cw-erm'
code: 
selected: true
---

### Abstract
The imitation learning of self-driving vehicle policies through behavioral cloning is often carried out in an open-loop fashion, 
ignoring the effect of actions to future states. 
Training such policies purely with Empirical Risk Minimization (ERM) can be detrimental to real-world performance, 
as it biases policy networks towards matching only open-loop behavior, showing poor results when evaluated in closed-loop. 
In this work, we develop an efficient and simple-to-implement principle called Closed-loop Weighted Empirical Risk Minimization (CW-ERM), 
in which a closed-loop evaluation procedure is first used to identify training data samples that are important for practical driving performance and then we these samples to help debias the policy network. 
We evaluate CW-ERM in a challenging urban driving dataset and show that this procedure yields a significant reduction in collisions as well as other non-differentiable closed-loop metrics.

### Recommended citation
{% raw %}
```
@article{kumar2022cw,
  title={CW-ERM: Improving Autonomous Driving Planning with Closed-loop Weighted Empirical Risk Minimization},
  author={Kumar, Eesha and Zhang, Yiming and Pini, Stefano and Stent, Simon and Ferreira, Ana and Zagoruyko, Sergey and Perone, Christian S},
  journal={arXiv preprint arXiv:2210.02174},
  year={2022}
}
```
{% endraw %}
