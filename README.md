# Vehicle Detection and Tracking
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

Created a vehicle detection and tracking pipeline with OpenCV, histogram of oriented gradients (HOG), and support vector machines (SVM). Optimized and evaluated the model on video data from a automotive camera taken during highway driving.

[//]: # (Image References)

[im01]: ./test1017x_5_large.jpg "Vehicle Detection"

![alt text][im01]

<img src="./test1017x_5_large.jpg" width="946" height="522" />

The Project
---

The goals / steps of this project are the following:

* Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images and train a classifier Linear SVM classifier
* Apply a color transform and append binned color features, as well as histograms of color, to the HOG feature vector. 
* Normalize features and randomize selections for training and testing.
* Implement a sliding-window technique and use the trained classifier to search for vehicles in images.
* Run software pipeline on a video stream and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.
* Estimate a bounding box for vehicles detected.

[Project Code](https://github.com/jquickgh/CarND-Vehicle-Detection/blob/master/P5_Final.ipynb)

[Project Video](https://www.youtube.com/watch?v=7h1iv-9sqys)

[Project Writeup](https://github.com/jquickgh/self-driving-car-engineer-nd/blob/master/p5-vehicle-detection-and-tracking/README.ipynb)