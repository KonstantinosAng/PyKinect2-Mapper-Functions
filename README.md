# PyKinectV2 Mapper Functions
***

## Description
Documentation and description on how to use the ICoordinateMapper of Microsoft Kinect V2 using PyKinectV2 and python.

## Instructions

Simply import the mapper.py in your file and use the functions. The reason I have the 
kinect instance as the first argument is to avoid any segmentation errors by multiple access points to 
the the kinect device. Most of the function work pretty well, just remember to give time to kinect to open 
and have at least on depth frame and color frame to use most of the functions without errors. Feel free to modify and use
and if you like it give it a star.

## Requirements
Full list of **all** requirements
```
* ctypes
* numpy==1.18.1
* pykinect2==0.1.0
```
