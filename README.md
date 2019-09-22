# Policeman-Gesture-Recognition-with-Spatial-Temporal-Graph-Convolution-Network
By using skeleton data for pose recognition and video understanding,
* Skeleton recognition systems, like OpenPose, act as an excellent noise removal utility
* Low dimensional skeleton representation allows the fine-tuning of feature extraction works with little data.

## Approach  
* [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose): extract 18 keypoints from the human body.
* [Spatial Temporal Graph Convolutional Networks(ST-GCN)](https://arxiv.org/pdf/1801.07455.pdf): a dynamic skeleton based approach to classify the actions in the video.

## Features
* Functionality:
  * 2D real-time single-person keypoint detection
  * 2D/3D pose estimation
  * Skeleton-based action generation and recognition

## Result
To visualize how ST-GCN exploit local correlation and local pattern, the feature vector magnitude of each node in the final spatial temporal graph is computed, and being overlayed on the original video.

<img src="https://github.com/WeijiaGao49/Policeman-Gesture-Recognition-with-Spatial-Temporal-Graph-Convolution-Network/raw/master/demo/left.gif" width=30% height=30%> <img src="https://github.com/WeijiaGao49/Policeman-Gesture-Recognition-with-Spatial-Temporal-Graph-Convolution-Network/raw/master/demo/parallel.gif" width=30% height=30%> <img src="https://github.com/WeijiaGao49/Policeman-Gesture-Recognition-with-Spatial-Temporal-Graph-Convolution-Network/raw/master/demo/result.gif" width=30% height=30%>
