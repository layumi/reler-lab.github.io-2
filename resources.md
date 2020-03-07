---
title: Reference
permalink: /resources/
---


## Datasets
<hr>

### University-1652
![](https://github.com/layumi/University1652-Baseline/raw/master/docs/index_files/Data.jpg)
University-1652 is a multi-view multi-source benchmark for drone-based geo-localization that contains 1652 buildings of 72 universities around the world. We provide images collected from the virtual drone, the satellite and the ground.

[[Paper]](https://arxiv.org/abs/2002.12186)
[[Dataset]](https://github.com/layumi/University1652-Baseline)

Task 1: Drone-view target localization. (Drone -> Satellite)} Given one drone-view image or video, the task aims to find the most similar satellite-view image to localize the target building in the satellite view.

Task 2: Drone navigation. (Satellite -> Drone)} Given one satellite-view image, the drone intends to find the most relevant place (drone-view images) that it has passed by. According to its flight history, the drone could be navigated back to the target place.
