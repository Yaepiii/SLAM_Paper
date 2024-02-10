# SLAM_Paper
This repository is a collection of SLAM papers that I read during my studies, which I think are of value to read for both beginners and experienced researchers.

The research areas I am most interested in in SLAM tend to be semantic SLAM, dynamic SLAM, and object SLAM, so the papers in the related area may be updated more frequently.

The structure of the entire repository is as follows:

```
SLAM_Paper
├─Laser SLAM
│   ├─Dynamic SLAM
│   ├─NeRF SLAM
│   ├─Semantic SLAM
│   └─Traditional SLAM
|      ├─2D
|      └─3D
|─Related Method
|   ├─Feature Detection
|   ├─MVS
|   ├─NeRF
|   ├─Network
|   └─Semantic Segmentation
└─Visual SLAM
    ├─Dynamic SLAM
    ├─Learning-based SLAM
    ├─NeRF SLAM
    ├─Objects SLAM
    ├─Semantic SLAM
    └─Traditional SLAM
       ├─Direct-based
       └─Feature-based
```

## [Laser SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Laser%20SLAM)

This folder mainly stores various SLAM algorithms based on Laser, and is divided into the following parts according to different application fields or research methods:

- [Dynamic SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Laser%20SLAM/Dynamic%20SLAM): The application of SLAM algorithm in dynamic scenarios, including dynamic object detection and removal, etc.
  
- [NeRF SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Laser%20SLAM/NeRF%20SLAM): This is a relatively new SLAM algorithm, which mainly integrates [NeRF](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method/NeRF) ideas(very hot in 2020) into laser SLAM. At present, there are few reasches, but it is a very hot and concerned direction.
  
- [Semantic SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Laser%20SLAM/Semantic%20SLAM): Semantic segmentation of point cloud extracted by LiDAR is carried out, and the results of semantic segmentation are used in SLAM to improve location accuracy and build more high-level maps that are easier to be understood by people.
  
- [Traditional SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Laser%20SLAM/Tranditional%20SLAM): Without the use of advanced algorithms (such as neural networks, etc.), the pose of the robot is usually calculated by feature extraction and feature matching algorithms such as ICP. It is further divided into 2D and 3D application scenarios:
  
  - [2D](https://github.com/Yaepiii/SLAM_Paper/tree/main/Laser%20SLAM/Tranditional%20SLAM/2D): Just includes some classic paper, such as gmapping, cartographer, etc.
    
  - [3D](https://github.com/Yaepiii/SLAM_Paper/tree/main/Laser%20SLAM/Tranditional%20SLAM/3D): LOAM series algorithm is the main component(LOAM, LeGO-LOAM, LIO-SAM, etc.)

## [Related Method](https://github.com/Yaepiii/SLAM_Paper/tree/main/Related%20Method)

This folder mainly stores algorithms that assist SLAM:

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
  
- [Semantic SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/Semantic%20SLAM): Semantic segmentation of image or point cloud obtained by camera is carried out, and the results of semantic segmentation are used in SLAM to improve location accuracy and build more high-level maps that are easier to be understood by people.
  
- [Traditional SLAM](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/Traditional%20SLAM): Without the use of advanced algorithms (such as neural networks, etc.), the pose of the robot is usually calculated by classic feature extraction and feature matching algorithms. It is further divided into  and 3D application scenarios:
  
  - [Direct-based](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/Traditional%20SLAM/Direct-based): SLAM with using a direct method to calculate errors to locate agent, such as photometric errors.
    
  - [Feature-based](https://github.com/Yaepiii/SLAM_Paper/tree/main/Visual%20SLAM/Traditional%20SLAM/Feature-based): SLAM with usng a feature extraction and feature matching method to calculate errors to locate agent, the most classic method being ORB-SLAM series.

ongoing update...















