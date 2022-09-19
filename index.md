---
layout: default
---

## Abstract

This paper presents a LiDAR odometry estimation framework called Generalized LOAM.
Our proposed method is generalized in that it can seamlessly fuse various local geometric shapes around points to improve the position estimation accuracy compared to the conventional LiDAR odometry and mapping (LOAM) method.
To utilize continuous geometric features for LiDAR odometry estimation, we incorporate tiny neural networks into a generalized iterative closest point (GICP) algorithm.
These neural networks improve the data association metric and the matching cost function using local geometric features.
Experiments with the KITTI benchmark demonstrate that our proposed method reduces relative trajectory errors compared to the GICP and LOAM methods.


## Movie 

- [movie](https://drive.google.com/file/d/10BO2BmWQwt0p7ao4xP1SLsmaTrpIYZdZ/view?usp=sharing)


## Supplementally Results

[PDF](./materials/SupplementaryResults.pdf)

## Links

- Paper(WIP)