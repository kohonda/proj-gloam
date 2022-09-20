---
layout: default
---

## Abstract

This paper presents a LiDAR odometry estimation framework called Generalized LOAM.
Our proposed method is generalized in that it can seamlessly fuse various local geometric shapes around points to improve the position estimation accuracy compared to the conventional LiDAR odometry and mapping (LOAM) method.
To utilize continuous geometric features for LiDAR odometry estimation, we incorporate tiny neural networks into a generalized iterative closest point (GICP) algorithm.
These neural networks improve the data association metric and the matching cost function using local geometric features.
Experiments with the KITTI benchmark demonstrate that our proposed method reduces relative trajectory errors compared to the GICP and LOAM methods.


## Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/6ksAjTQ3fCY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Supplementally Results

[PDF](./materials/SupplementaryResults.pdf)

## Links

- Paper(WIP)
