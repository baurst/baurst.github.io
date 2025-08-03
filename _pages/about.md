---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi there! 👋 I'm Stefan, a ML Engineer working on autonomous driving at Mercedes-Benz.

I have obtained my PhD as part of the [Autonomous Vision Group at the University of Tübingen](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/autonomous-vision/team/), supervised by [Andreas Geiger](https://cvlibs.net/). You can find my thesis [here](https://publikationen.uni-tuebingen.de/xmlui/handle/10900/166495).

My research is at the intersection of machine learning and 3D Vision, especially motion-based self-supervised learning for 3D LiDAR sensors.

I strongly believe in the [Bitter Lesson](http://www.incompleteideas.net/IncIdeas/BitterLesson.html): In the long run, methods that can make better use of data and compute tend to outperform all the clever tricks we come up with as computer vision researchers.
That said, I think motion-based self-supervised learning in 3D is a practical shortcut for models to obtain a deeper world understanding: It scales with data and compute, while taking advantage of how things actually move and exist in 3D space.

Please check out my related publications below:

## Publications

* [PhD Thesis: Learning 3D LiDAR Object Detection without Human Annotations](https://publikationen.uni-tuebingen.de/xmlui/handle/10900/166495)
  * Stefan Baur 2025, Faculty of Science, University of Tubingen

* [LISO: Lidar-only Self-Supervised 3D Object Detection](https://baurst.github.io/liso)
  * Stefan Baur, Frank Moosmann and Andreas Geiger
  * 2024 European Conference on Computer Vision (**ECCV**)
  * [Paper](https://arxiv.org/abs/2403.07071)

* [SLIM: Self-Supervised LiDAR Scene Flow and Motion Segmentation](https://baurst.github.io/slim)
  * Stefan Baur<sup>\*</sup>, David Emmerichs<sup>\*</sup>, Frank Moosmann, Peter Pinggera, Bjorn Ommer and Andreas Geiger (<sup>\*</sup>: equal conribution)
  * 2021 International Conference on Computer Vision (**ICCV**), Oral
  * [Paper](http://www.cvlibs.net/publications/Baur2021ICCV.pdf)

* [Quantifying point cloud realism through adversarially learned latent representations](https://arxiv.org/pdf/2109.11775.pdf)
  * Larissa T. Triess, David Peter, Stefan Baur and J. Marius Zöllner
  * 2021 Proc. of the German Conference on Pattern Recognition (**GCPR**)

* [PillarFlowNet: A Real-time Deep Multitask Network for LiDAR-based 3D Object Detection and Scene Flow Estimation](https://ras.papercept.net/proceedings/IROS20/1208.pdf)
  * Fabian Duffhaus; Stefan Baur
  * 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (**IROS**)

* [Real-time 3D LiDAR Flow for Autonomous Vehicles](https://ieeexplore.ieee.org/document/8814094) (Oral)
  * Stefan A. Baur; Frank Moosmann; Sascha Wirges; Christoph B. Rist
  * 2019 IEEE Intelligent Vehicles Symposium (**IV**)

## Misc

* Co-chair of the session "Range Sensing and Deep Learning" @ [2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)](https://www.iros2020.org/)

## Software Projects

* [RBRT](https://github.com/baurst/rbrt): A lightweight Ray Tracer that I wrote to dive into raytracing and Rust.
  * fast: supports Intel AVX & SSE SIMD instructions
  * meshes can be loaded from .obj files
* [Sudoku Solver](https://github.com/baurst/sudoku_solver):
  * uses constraint propagation and backtracking
  * Rust compiled to WebAssembly with React Frontend
  * [try it out](https://baurst.github.io/sudoku_solver/) (runs completely in the browser)
* [Snake](https://github.com/baurst/rs_snake): A terminal based snake game
  * no window manager or GUI required
  * cross platform: [Latest Release (Windows & Linux)](https://github.com/baurst/rs_snake/releases).
