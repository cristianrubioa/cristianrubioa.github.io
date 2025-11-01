---
title: "LiDAR SLAM Algorithms Comparison"
excerpt: "Open-source implementation and benchmarking of A-LOAM, ISCLOAM, and LeGO-LOAM using KITTI dataset<br/><img src='/images/portfolio/03-lidar-slam-comparison.png'>"
collection: portfolio
date: 2021-12-13
---

## Overview

Open-source implementation and comprehensive comparison of three state-of-the-art LiDAR SLAM algorithms using the complete KITTI dataset. This project addresses the computational challenges of real-time 3D mapping with high data-rate laser scanners.

## Project Description

Benchmarking of LiDAR Odometry and Mapping (LOAM) derivatives for autonomous navigation:
- **A-LOAM:** Advanced LiDAR Odometry and Mapping
- **FLOAM** Fast LOAM
- **ISCLOAM:** Intensity Scan Context LOAM
- **LeGO-LOAM:** Lightweight and Ground-Optimized LOAM

Evaluated across 11 KITTI sequences (00-10) covering urban, highway, and country environments with Velodyne HDL-64E sensor data.

## Key Features

- Complete ROS implementation of three SLAM algorithms
- Automated testing pipeline for KITTI dataset sequences
- Comparative analysis on computational cost and positioning accuracy
- Visualization tools for trajectory and map generation
- Ready-to-use launch scripts for reproducibility

## Evaluation Metrics

- **Computational Cost:** Processing time and resource usage
- **Absolute Trajectory Error (ATE):** Overall positioning accuracy
- **Relative Pose Error (RPE):** Frame-to-frame consistency
- **Robustness:** Performance across diverse environments (urban, highway, country)

## Technologies Used

- **[ROS](https://www.ros.org/)** (Kinetic/Melodic)
- **[Point Cloud Library (PCL)](https://pointclouds.org/)**
- **[Ceres Solver](http://ceres-solver.org/)**
- **[GTSAM](https://gtsam.org/)**
- **[KITTI Dataset](http://www.cvlibs.net/datasets/kitti/)**
- **C++/Python**

## Impact

Provides robotics researchers and practitioners with empirical data to select the most appropriate SLAM algorithm for their specific applications, balancing accuracy and computational efficiency.

## Publication

**H. F. Murcia and C. F. Rubio**, "A Comparison of LiDAR Odometry and Mapping Techniques," *2021 IEEE 5th Colombian Conference on Automatic Control (CCAC)*, Ibagué, Colombia, 2021, pp. 192-197, doi: 10.1109/CCAC51819.2021.9633299

## Links

- **GitHub Repository:** [https://github.com/HaroldMurcia/LOaM-comparison](https://github.com/HaroldMurcia/LOaM-comparison)
- **IEEE Xplore:** [https://ieeexplore.ieee.org/document/9633299](https://ieeexplore.ieee.org/document/9633299)
- **Demo Video:** [A-LOAM Demonstration](https://youtu.be/demo-link)

## Acknowledgement

This work was supported by Universidad de Ibagué under research project 19-489-INT.