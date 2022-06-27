---
title: "Deep Neuromorphic Controller with Dynamic Topology for Aerial Robots"
layout: project-pagelay
excerpt: "Project Page"
sitemap: false
permalink: /2021/Deep-Neuromorphic-Controller/
---

*This work has been accepted at ICRA 2021!*

<div align = "center">
# Deep Neuromorphic Controller with Dynamic Topology for Aerial Robots
</div>

<div align = "center">
#### B.B. Kocer<sup>1</sup>, M.A. Hady<sup>2</sup>, K. Harikumar<sup>3</sup>, M. Pratama<sup>4</sup> and M. Kovac<sup>1</sup>
<sup>1</sup> Imperial College, London <br>
<sup>2</sup> ITS-Surabaya, Indonesia <br>
<sup>3</sup> IIIT Hyderabad <br>
<sup>4</sup> NTU, Singapore <br>
</div>

<hr>

### Abstract

Current aerial robots are increasingly adaptive; they can morph to enable operation in changing conditions to
complete diverse missions. Each mission may require the robot to conduct a different task. A conventional learning approach can handle these variations when the system is trained for similar tasks in a representative environment. However, it may result in overfitting to the new data stream or the failure to adapt, leading to degradation or a potential crash. These problems can be mitigated with an excessive amount of data and embedded model, but the computational power and the memory of the aerial robots are limited. In order to address the variations in the model, environment as well as the tasks within onboard computation limitations, we propose a deep neuromorphic controller approach with variable topologies to handle each different condition and the data stream with a feasible computation and memory allocation. The proposed approach is based on a deep neuromorphic (multi and variable layered neural network) controller with dynamic depth and progressive layer adaptation for each new data stream. This adaptive structure is combined with a switching function to form a sliding mode controller. The network parameter update rule guarantees the stability of the closed loop system by the convergence of the error dynamics to the sliding surface. Being the first implementation on an aerial robot in this context, the results illustrate the adaptation capability, stability, computational efficiency as well as the realtime validation.

### Citation

Please cite our work if you use it

```
@inproceedings{Kocer:2021,
author = {Kocer, B and Hady, A and Kandath, H and Pratama, M and Kovac, M},
publisher = {IEEE},
title = {Deep neuromorphic controller with dynamic topology for aerial robots},
url = {http://hdl.handle.net/10044/1/88763},
year = {2021}
}
```

<!-- You find the past job openings here:
[Opening 1]({{ site.baseurl }}/downloads/GeneralPostdoc_2019_v01.pdf),
[Opening 2]({{ site.baseurl }}/downloads/PPMS_PhD_2019_v01.pdf),
[Opening 3]({{ site.baseurl }}/downloads/PD.pdf),
[Opening 4]({{ site.baseurl }}/downloads/PHD1.pdf), 
[Opening 5]({{ site.baseurl }}/downloads/PHD2.pdf). -->

<!-- <figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/DSC_0696.jpg" width="95%">
</figure> -->
