# Point-Cloud-Paper
点云论文阅读笔记

[TOC]



## no-DeepLearning

#### PointCloud semantic segmentation



#### PointCloudSegmentation

1. Efficient Online Segmentation for Sparse 3D Laser Scans，2017

   > github:https://github.com/PRBonn/depth_clustering
   >
   > 阅读笔记：https://www.cnblogs.com/li-yao7758258/p/9937704.html

   

   > 文章介绍了一种将点云转换为图片然后基于图片对点云进行聚类分割的方法。
   >
   > 
   >
   > - 通过相邻两行之间的角度增量，分割地面
   > - 通过相邻两列之间的角度，对点云聚类（对图像进行欧式聚类）
   >
   > 最终结果速度非常快（因为是基于图像进行处理的），但是对于聚类的步骤，会导致对一些物体造成过分割（比如对于一些和激光束接近平行的平面，会被分割成多个物体）

2.  

3.  

4.  

5.  

6. 

#### Lidar SLAM

---



## DeepingLearning-bsaed



#### PointCloud semantic segmentation

#### 