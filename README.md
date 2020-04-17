# PyKinect2 Mapper Functions
***

## Description
Documentation and description on how to use the ICoordinateMapper of Microsoft Kinect 2 using [PyKinect2](https://github.com/Kinect/PyKinect2) and [python](https://www.python.org).

## Instructions

Simply import the mapper.py in your file and use the functions. The reason I have the 
kinect instance as the first argument is to avoid any segmentation errors by multiple access points to 
the the kinect device. Most of the function work pretty well, just remember to give time to kinect to open 
and have at least one depth frame and color frame to use most of the functions without errors. Feel free to modify and use
and if you like it give it a star. Most of the documentation is inside the mapper.py file, if you cannot understand how to use
any of the function feel free to open an issue and ask me.

## Requirements
Install all requirements from requirements.txt using the following command
```
pip install -r requirements.txt --no-index --find-links file:///tmp/packages
```
Full list of **all** requirements
```
* ctypes
* numpy==1.18.1
* pykinect2==0.1.0
```
