{: align="center"}
**Kohei Honda (1), Kenji Koide (2), Masashi Yokozuka (2), Shuji Oishi (2), and Atuhiko Banno (2)**

{: align="center"}
**IEEE Robotics and Automation Letters, 2022**

(1): Nagoya University
(2): National Institute of Advanced Industrial Science and Technology

This work will be presented at ICRA 2023

## Abstract

This paper presents a LiDAR odometry estimation framework called Generalized LOAM.
Our proposed method is generalized in that it can seamlessly fuse various local geometric shapes around points to improve the position estimation accuracy compared to the conventional LiDAR odometry and mapping (LOAM) method.
To utilize continuous geometric features for LiDAR odometry estimation, we incorporate tiny neural networks into a generalized iterative closest point (GICP) algorithm.
These neural networks improve the data association metric and the matching cost function using local geometric features.
Experiments with the KITTI benchmark demonstrate that our proposed method reduces relative trajectory errors compared to the GICP and LOAM methods.


## Video

{% include youtube.html id="6ksAjTQ3fCY" %}

## Supplementally Results

[PDF](./materials/SupplementaryResults.pdf)

## Links

- Paper in print
