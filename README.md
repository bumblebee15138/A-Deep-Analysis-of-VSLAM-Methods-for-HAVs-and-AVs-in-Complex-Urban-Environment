# A Deep Analysis of Visual SLAM Methods for Highly Automated (HAVs) and Autonomous Vehicles (AVs) in Complex  Urban Environment
A review to serve as a timely update on recent progresses and advances in VSLAM which are applicable to HAVs or AVs.

## Table of Contents
- [At a Glance](#at-a-glance)
- [Learning Materials](#learning-materials)
- [Some Representative Relevant Papers](#some-representative-relevant-papers)
- [Datasets related to VSLAM and autonomous driving in urban environments](#datasets-related-to-vslam-and-autonomous-driving-in-urban-environments)
- [Future challenges of autonomous driving and VSLAM](#future-challenges-of-autonomous-driving-and-vslam)
- [Citation](#citation)
  
## At a Glance
An imprecise localization can greatly impact subsequent decision-making to manage an HAV or AV’s motion (planning and control tasks). In recent years, visual simultaneous localization and mapping (VSLAM) has shown substantial progress and equipping it can lead to handling non-standardized situations of real-world scenes and achieving higher localization and mapping accuracy. In this article, we present a comprehensive analysis of the current research status of VSLAM and its potential application to HAVs or AVs operating in complex urban environments. We will publish our article in the future, and more details can be found in our article.
<br/>

![what VSLAM can achieve](https://github.com/bumblebee15138/A-Deep-Analysis-of-VSLAM-Methods-for-HAVs-and-AVs-in-Complex-Urban-Environment/blob/main/assets/what%20VSLAM%20can%20achieve.png)

<br/>
<p align="right">(<a href="#top">back to top</a>)</p>

## Learning Materials
We provide some review articles on VSLAM/SLAM and autonomous driving for researchers' reference.
- [A review of visual SLAM methods for autonomous driving vehicles](https://www.sciencedirect.com/science/article/pii/S0952197622001853), J. Cheng, L. Zhang, Q. Chen, X. Hu, and J. Cai
- [Stereo Visual SLAM for Autonomous Vehicles: A Review](https://ieeexplore.ieee.org/abstract/document/9283161), Boyu Gao, Haoxiang Lang, and Jing Ren
- [A Comprehensive Survey of Visual SLAM Algorithms](https://www.mdpi.com/2218-6581/11/1/24), A Macario Barros, M Michel, and Y Moline
- [A survey of state-of-the-art on visual SLAM](https://www.sciencedirect.com/science/article/pii/S0957417422010156), IA Kazerouni, L Fitzgerald, G Dooly, and D Toal
<p align="right">(<a href="#top">back to top</a>)</p>

## Some Representative Relevant Papers
As shown in the image in [At a Glance](#at-a-glance) section, VSLAM can provide effective solutions to the difficulties encountered by HAVs or AVs in complex urban environments. In this section, we provide links to some representative papers on these solutions.

**Multi-dynamic processing ability**
- [DE‐SLAM: SLAM for highly dynamic environment](https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.22062)
- [Edge assisted mobile semantic visual slam](https://ieeexplore.ieee.org/abstract/document/9155438)
- [DOT: Dynamic object tracking for visual SLAM](https://ieeexplore.ieee.org/abstract/document/9561452)
- [DP-SLAM: A visual SLAM with moving probability towards dynamic environments](https://www.sciencedirect.com/science/article/abs/pii/S0020025520311841)
- [VDO-SLAM: a visual dynamic object-aware SLAM system](https://arxiv.org/abs/2005.11052)
- [DynaSLAM II: Tightly-coupled multi-object tracking and SLAM](https://ieeexplore.ieee.org/abstract/document/9385844)

**Large-scale mapping ability**
- [Camvox: A low-cost and accurate lidar-assisted visual slam system](https://ieeexplore.ieee.org/abstract/document/9561149)
- [A light-weight semantic map for visual localization towards autonomous driving](https://ieeexplore.ieee.org/abstract/document/9561663)
- [Probabilistic semantic mapping for urban autonomous driving applications](https://ieeexplore.ieee.org/abstract/document/9341738)
- [Towards open world nerf-based slam](https://ieeexplore.ieee.org/abstract/document/10229827)
- [Lightweight semantic mesh mapping for autonomous vehicles](https://ieeexplore.ieee.org/abstract/document/9560996)
- [A semantic SLAM-based dense mapping approach for large-scale dynamic outdoor environment](https://www.sciencedirect.com/science/article/abs/pii/S0263224122011976)

**Scene recognition ability**
- [A novel lidar-assisted monocular visual SLAM framework for mobile robots in outdoor environments](https://ieeexplore.ieee.org/abstract/document/9826793)
- [Improving visual SLAM in car-navigated urban environments with appearance maps](https://ieeexplore.ieee.org/abstract/document/9341451)
- [Learning whole-image descriptors for real-time loop detection and kidnap recovery under large viewpoint difference](https://www.sciencedirect.com/science/article/abs/pii/S0921889021000981)
- [Gn-net: The gauss-newton loss for multi-weather relocalization](https://ieeexplore.ieee.org/abstract/document/8954808)
- [Tight integration of feature-based relocalization in monocular direct visual odometry](https://ieeexplore.ieee.org/abstract/document/9561217)

**Long-term operation ability and crowd-sourced mapping**
- [Continual slam: Beyond lifelong simultaneous localization and mapping through continual learning](https://link.springer.com/chapter/10.1007/978-3-031-25555-7_3)
- [Airloop: Lifelong loop closure detection](https://ieeexplore.ieee.org/abstract/document/9811658)
- [Sharing visual-inertial data for collaborative decentralized simultaneous localization and mapping](https://www.sciencedirect.com/science/article/abs/pii/S0921889021002177)
- [Crowdsourced Road Semantics Mapping Based on Pixel-Wise Confidence Level](https://link.springer.com/article/10.1007/s42154-021-00173-x)
- [Graph optimization methods for large-scale crowdsourced mapping](https://ieeexplore.ieee.org/abstract/document/9190292)
- [Hierarchical Loop Closure Detection for Long-term Visual SLAM with Semantic-Geometric Descriptors](https://ieeexplore.ieee.org/abstract/document/9564866)

<p align="right">(<a href="#top">back to top</a>)</p>

## Datasets related to VSLAM and autonomous driving in urban environments
- [KITTI Dataset](https://www.cvlibs.net/)
- [KAIST Day/Night Dataset](https://sites.google.com/view/multispectral/home)
- [Complex Urban Dataset](http://irap.kaist.ac.kr/dataset/)
- [Zurich Urban Micro Aerial Vehicle Dataset](http://rpg.ifi.uzh.ch/zurichmavdataset.html)
- [CityScapes Dataset](https://www.cityscapes-dataset.com/)
- [Oxford Robotcar Dataset](http://robotcar-dataset.robots.ox.ac.uk/)
- [Cambridge Landmark Dataset](http://mi.eng.cam.ac.uk/projects/relocalisation/)
- [Multi-Robot Cooperative Localization and Mapping Dataset](http://asrl.utias.utoronto.ca/datasets/mrclam/)
- [Nuscenes Dataset](https://www.nuscenes.org/)

<p align="right">(<a href="#top">back to top</a>)</p>

## Future challenges of autonomous driving and VSLAM
We have provided links to articles about the future development and challenges of autonomous driving and VSLAM for your reference.
- [Recent advancements in end-to-end autonomous driving using deep learning: A survey](https://ieeexplore.ieee.org/abstract/document/10258330)
- [Collaborative perception in autonomous driving: Methods, datasets and challenges](https://arxiv.org/abs/2301.06262)
- [Present and future of SLAM in extreme environments: The DARPA subT challenge](https://ieeexplore.ieee.org/abstract/document/10286080/)
- [Robust SLAM systems: Are we there yet?](https://ieeexplore.ieee.org/abstract/document/9636814)

  <p align="right">(<a href="#top">back to top</a>)</p>

## The rest of the content will be updated continuously

## Citation
We will publish the citation information after the article is published.

<p align="right">(<a href="#top">back to top</a>)</p>
