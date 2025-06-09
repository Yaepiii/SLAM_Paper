# SLAM_Paper
This repository is a collection of SLAM papers that I read during my research, which I think are of value to read for both beginners and experienced researchers.

The research areas I am most interested in in SLAM tend to be 3D LiDAR SLAM, dynamic SLAM, offline dynamic map maintenance, so the papers in the related area may be updated more frequently.

The structure of the entire repository is as follows:

```
SLAM_Paper
├─Lidar SLAM
│   ├─Dynamic SLAM
│   ├─Learning-based SLAM
│   ├─Mapping
│   ├─Mesh SLAM
│   ├─Multi-Session & Multi-Agent SLAM
│   ├─NeRF SLAM
│   ├─Object SLAM
│   └─Traditional SLAM
|      ├─2D
|      └─3D
|─Long-term Localization and Mapping
|   ├─Dynamic Map Maintenance
|   └─Long-term Relocalization and Place Recognition
|─Multi-sensor SLAM
|─Related Method
|   ├─Classsification
|   ├─Datasets
|   ├─Feature Detection
|   ├─MOS
|   ├─MVS
|   ├─NeRF
|   ├─Object Detection
|   └─Semantic Segmentation
└─Visual SLAM
    ├─Dynamic SLAM
    ├─Learning-based SLAM
    ├─NeRF SLAM
    ├─Objects SLAM
    └─Traditional SLAM
       ├─Direct-based
       └─Feature-based


```

## [LiDAR SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM)

This folder mainly stores various SLAM algorithms based on LiDAR, and is divided into the following parts according to different application fields or research methods:

- [Dynamic SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM/Dynamic%20SLAM): The application of SLAM algorithm in dynamic scenarios, including dynamic object detection and removal, etc.

- [Learning-based SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM/Learning-based%20SLAM): Estimate the odometry of robot by using deep learning method.

- [Mapping](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM/Mapping): LiDAR Mapping module and some interesting mapping methods in SLAM.

- [Mesh SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM/Mesh%20SLAM): A novel method that builds the mesh map and solve the pose by point-to-mesh for SLAM.

- [Multi-Session & Multi-Agent SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM/Multi-Session%20%26%20Multi-Agent%20SLAM): There are some methods about Multi-Session & Multi-Agent SLAM, which may become my future research topic.
  
- [NeRF SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM/NeRF%20SLAM): This is a relatively new SLAM algorithm, which mainly integrates [NeRF](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/NeRF) ideas(very hot in 2020) into LiDAR SLAM. At present, there are few reasches, but it is a very hot and concerned direction.

- [Object SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM/Object%20SLAM): There are some methods with estimate both self-pose and object's pose, using object pose to impose the constrains to the odometry.
  
- [Traditional SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM/Tranditional%20SLAM): Without the use of advanced algorithms (such as neural networks, etc.), the pose of the robot is usually calculated by feature extraction and feature matching algorithms such as ICP. It is further divided into 2D and 3D application scenarios:
  
  - [2D](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM/Tranditional%20SLAM/2D): Just includes some classic paper, such as gmapping, cartographer, etc.
    
  - [3D](https://github.com/Yaepiii/SLAM_Paper/tree/main/LiDAR%20SLAM/Tranditional%20SLAM/3D): Some typical and classic LiDAR LO or SLAM systems, which is my main research directions.

## [Related Method](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method)

This folder mainly stores algorithms that assist SLAM:

- [Classification](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/Classsification): Some classic papers about classification method.

- [Datasets](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/Datasets): Some classic datasets paper, including LiDAR, cameras, IMU, wheel odometry etc.

- [MOS](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/MOS): Some classic papers about Moving Object Segmentation, which will make some contributions to Dynamic SLAM and Long-term map maintenance.

- [MVS](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/MVS): Some classic papers about Motion-from-Structure, which will be similar to SLAM.

- [Feature Detection](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/Feature%20Detection): is used to extract feature points before SLAM.

- [NeRF](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/NeRF): Some classic papers about NeRF's principle.

- [Object Detection](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/Network): Some classic object detection neural networks atchitectures that may be used in SLAM pipeline, whose main feature is real-time in order to be more suitable for SLAM.

- [Semantic Segmentation](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/Semantic%20Segmentation): Some classic semantic segmentation neural networks atchitectures that may be used in SLAM pipeline, whose main feature is real-time in order to be more suitable for SLAM.


or are similar to the SLAM pipeline

## [Visual SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM)

This folder mainly stores various SLAM algorithms based on Camera, and is divided into the following parts according to different application fields or research methods:

- [Dynamic SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/Dynamic%20SLAM): The application of SLAM algorithm in dynamic scenarios, including dynamic object detection and removal, etc.

- [Learning-based SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/Learning-based%20SLAM): Some deep learning networks are used in SLAM to improve their localization performance.
  
- [NeRF SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/NeRF%20SLAM): This is a relatively new SLAM algorithm, which mainly integrates [NeRF](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/NeRF) ideas(very hot in 2020) into Visual SLAM. At present, it is a very hot and concerned direction.

- [Object SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/Objects%20SLAM): There are some methods integrating object detection into SLAM pipeline to improve the accuracy of location by regarding objects as feature or providing semantic understanding to the agent.
  
- [Traditional SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/Traditional%20SLAM): Without the use of advanced algorithms (such as neural networks, etc.), the pose of the robot is usually calculated by classic feature extraction and feature matching algorithms. It is further divided into  and 3D application scenarios:
  
  - [Direct-based](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/Traditional%20SLAM/Direct-based): SLAM with using a direct method to calculate errors to locate agent, such as photometric errors.
    
  - [Feature-based](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/Traditional%20SLAM/Feature-based): SLAM with usng a feature extraction and feature matching method to calculate errors to locate agent, the most classic method being ORB-SLAM series.
 
## [Long-term Localization and Mapping](https://github.com/Yaepiii/SLAM_Paper/tree/main/Long-term%20Localization%20and%20Mapping)

This folder mainly stores various methods on long-term localization and mapping and is divided into the following parts according to different application fields or research methods:

- [Long-term Relocalization and Place Recognition](https://github.com/Yaepiii/SLAM_Paper/tree/main/Long-term%20Localization%20and%20Mapping/Long-term%20Relocalization%20and%20Place%20Recognition): There are some methods about Place Recognition and Loop Closure.

- [Dynamic Map Maintenance](https://github.com/Yaepiii/SLAM_Paper/tree/main/Long-term%20Localization%20and%20Mapping/Dynamic%20Map%20Maintenance): There are some methods about map maintaince through dynamic removal.

## [Multi-sensor SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Multi-sensor%20SLAM)

This folder mainly stores various methods focusing on multi-sensor fusion SLAM.

This repo is updating...















