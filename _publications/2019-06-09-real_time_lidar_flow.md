---
title: 'Real-time 3D LiDAR Flow for Autonomous Vehicles'
collection: publications
permalink: /publication/2019-06-09-real_time_lidar_flow
excerpt: 'Real-time 3D LiDAR Flow using Range Images'
date: 2019-06-09
venue: ' 2019 IEEE Intelligent Vehicles Symposium (IV)'
paperurl: 'https://ieeexplore.ieee.org/document/8814094'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Autonomous vehicles require an accurate understanding of the underlying motion of their surroundings.
Traditionally this understanding is acquired using optical flow algorithms on camera images, RADAR sensors which measure velocity directly or by object tracking through various sensors.
We propose a novel method to estimate point-wise 3D motion vectors from LiDAR point clouds using fully convolutional networks trained and evaluated on the KITTI dataset.
Besides, we show how this motion information can be used to efficiently estimate odometry.
We demonstrate that our approach achieves significant speed ups over the current state of the art.

<!-- [Download paper here](http://academicpages.github.io/files/paper1.pdf) -->

```lang-tex
@inproceedings{DBLP:conf/ivs/BaurMWR19,
  author    = {Stefan A. Baur and
               Frank Moosmann and
               Sascha Wirges and
               Christoph B. Rist},
  title     = {Real-time 3D LiDAR Flow for Autonomous Vehicles},
  booktitle = {2019 {IEEE} Intelligent Vehicles Symposium, {IV} 2019, Paris, France,
               June 9-12, 2019},
  pages     = {1288--1295},
  publisher = {{IEEE}},
  year      = {2019},
  url       = {https://doi.org/10.1109/IVS.2019.8814094},
  doi       = {10.1109/IVS.2019.8814094},
  timestamp = {Wed, 16 Oct 2019 14:14:57 +0200},
  biburl    = {https://dblp.org/rec/conf/ivs/BaurMWR19.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```
