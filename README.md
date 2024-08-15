# Efficient Maritime Object Detection: YOLOv7 Tuning and Ghost Convolution Integration

## Overview
This repository contains a fork of the YOLOv7 object detection framework, with enhancements aimed at optimizing object detection in maritime environments. The project integrates Ghost Convolutions into the YOLOv7 architecture to reduce computational demands while maintaining high detection accuracy for objects like boats, jet skis, swimmers, and buoys.

### Project Background
In collaboration with Lookout, a company focused on maritime safety, we developed an object detection model optimized for deployment on resource-constrained maritime vessels. By replacing standard convolutional layers with Ghost Convolution modules, we significantly reduced the model’s parameters and floating point operations per second (FLOPS). These optimizations make the model more suitable for real-time processing on hardware with limited resources, such as high-end smartphones or embedded systems on smaller boats.

### Key Features
- **Ghost Convolution Integration**: Replaces all standard convolution layers in YOLOv7 with Ghost Convolutions, reducing parameters by 29.8% and FLOPS by 38.8%, while maintaining robust object detection performance.
- **Optimized for Maritime Environments**: Tuned specifically for maritime object detection, including classes like boats, jet skis, swimmers, buoys, and lifesaving appliances.
- **Hyperparameter Tuning**: Includes optimized hyperparameters that improve model stability and performance across different training runs.
- **Lightweight Deployment**: Designed for deployment in resource-constrained environments, making it suitable for smaller vessels and cost-effective applications.
