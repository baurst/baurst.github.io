---
title: 'PillarFlowNet: A Real-time Deep Multitask Network for LiDAR-based 3D Object Detection and Scene Flow Estimation'
collection: publications
permalink: /publications/2020-10-01-pillarflownet
excerpt: 'Multitask Network for LiDAR-based 3D Object Detection and Scene Flow Estimation.'
date: 2020-10-25
venue: '2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: 'https://ras.papercept.net/proceedings/IROS20/1208.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Mobile robotic platforms require a precise under-standing about other agents in their surroundings as well as their respective motion in order to operate safely.
Scene flow in combination with object detection can be used to achieve this understanding.
Together, they provide valuable cues for behavior prediction of other agents and thus ultimately are a good basis for the ego-vehicle’s behavior planning algorithms.
Traditionally, scene flow estimation and object detection are handled by separate deep networks requiring immense computational resources.
In this work, we propose PillarFlowNet, a novel method for simultaneous LiDAR scene flow estimation and object detection with low latency and high precision based on a single network.
In our experiments on the KITTI dataset, PillarFlowNet achieves a 16.3 percentage points higher average precision score as well as a 21.4% reduction in average endpoint error for scene flow compared to the state-of-the-art in multitask LiDAR object detection and scene flow estimation.
Furthermore, our method is significantly faster than previous methods, making it the first to be applicable for real-time systems.

[Download paper here](https://ras.papercept.net/proceedings/IROS20/1208.pdf)
{% raw %}
```lang-tex
@inproceedings{DBLP:conf/iros/DuffhaussB20,
  author    = {Fabian Duffhauss and
               Stefan A. Baur},
  title     = {PillarFlowNet: {A} Real-time Deep Multitask Network for LiDAR-based
               3D Object Detection and Scene Flow Estimation},
  booktitle = {{IEEE/RSJ} International Conference on Intelligent Robots and Systems,
               {IROS} 2020, Las Vegas, NV, USA, October 24, 2020 - January 24, 2021},
  pages     = {10734--10741},
  publisher = {{IEEE}},
  year      = {2020},
  url       = {https://doi.org/10.1109/IROS45743.2020.9341002},
  doi       = {10.1109/IROS45743.2020.9341002},
  timestamp = {Wed, 17 Feb 2021 09:26:30 +0100},
  biburl    = {https://dblp.org/rec/conf/iros/DuffhaussB20.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```
{% endraw %}