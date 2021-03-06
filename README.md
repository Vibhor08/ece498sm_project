# ece498sm_project
Road Detection by combining camera and LIDAR
## Files and folders:
* fcn_detector: code for fully convolutional network (FCN) in Tensorflow
* fcn_output: testing results of FCN
* knn_output: testing results of k-nearest neighbor
* runs: training results of FCN
* runs_fusion: sensor fusion results
* 498_LidarRead: code for LIDAR heatmap method
* find_iou.py: calculates the Intersection over Union (IoU) of the result images
* knn.py: code for k-nearest neighbor
* road_detection.py: PyTorch implementation of FCN, has errors and doesn't work

## Resources and references: 
### Vision-based lane detection: 
#### papers: 
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8500547 
Road detection using KITTI dataset:https://ieeexplore.ieee.org/abstract/document/7759717

#### Dataset: 
https://github.com/TuSimple/tusimple-benchmark/wiki
#### Code: https://github.com/MaybeShewill-CV/lanenet-lane-detection

### LIDAR-base road detection:
##### code: https://github.com/LidarPerception/kitti_ros

### Sensor fusion approach:
#### papers:
https://arxiv.org/pdf/1809.07941.pdf

https://velodynelidar.com/lidar/hdlpressroom/pdf/Articles/Lidar-based%20lane%20marker%20detection%20and%20mapping.pdf

http://www.cs.toronto.edu/~slwang/lane_detect.pdf

https://www.researchgate.net/publication/260522418_A_Sensor-Fusion_Drivable-Region_and_Lane-Detection_System_for_Autonomous_Vehicle_Navigation_in_Challenging_Road_Scenarios

#### Dataset: 
A good summary of all avaliable datasets: https://mighty.ai/blog/top_open_source_lidar_driving_datasets/
http://www.cvlibs.net/datasets/kitti/eval_road.php

