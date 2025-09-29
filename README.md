# Mapping and Perception for an Autonomous Robot – Course Projects

This repository contains four projects completed as part of the *Mapping and Perception for an Autonomous Robot* course (M.Sc. program, Tel Aviv University).  
Each project focuses on a different fundamental component of mapping, localization, and perception in autonomous systems.

## Projects

1. **Project 1 – Geodetic Coordinates and Occupancy Grids**  
   - Worked with the KITTI dataset, analyzing GPS signals, vehicle trajectories (ENU/NED), and sensor integration.  
   - Implemented probabilistic **Occupancy Grid Mapping** using LiDAR and camera data.  
   - [Report PDF](project1_geodetic_occupancy/report/report.pdf)

2. **Project 2 – Kalman and Extended Kalman Filters**  
   - Implemented **Kalman Filter (KF)** and **Extended Kalman Filter (EKF)** for vehicle trajectory estimation.  
   - Added Gaussian noise to GPS/IMU signals and evaluated filtering accuracy (RMSE, maxE).  
   - [Report PDF](project2_kalman_filters/report/report.pdf)

3. **Project 3 – EKF-SLAM and ICP**  
   - Developed **EKF-SLAM** for simultaneous localization and mapping with odometry and landmark data.  
   - Implemented **Iterative Closest Point (ICP)** for aligning point clouds.  
   - Analyzed uncertainty reduction and accuracy metrics (RMSE, error bounds).  
   - [Report PDF](project3_slam_icp/report/report.pdf)

4. **Project 4 – Visual Odometry, 3D Object Detection, and Multi-Object Tracking**  
   - Built a **Visual Odometry pipeline** (feature extraction, matching, pose estimation, trajectory reconstruction).  
   - Applied **PointPillars network** for 3D object detection from LiDAR point clouds.  
   - Implemented **BoT-SORT** for multi-object tracking.  
   - [Report PDF](project4_visual_odometry_3d/report/report.pdf)

---

## Repository Structure
