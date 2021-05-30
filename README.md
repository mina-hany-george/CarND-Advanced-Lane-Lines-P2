# **CarND-Advanced-Lane-Lines-P2**
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

## Project Writeup

---

**Advanced Lane Lines Detection on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on my work in a written report

---

### Reflection

Overview
---

In this project, your goal is to write a software pipeline to identify the lane boundaries in a video from a front-facing camera on a car. The camera calibration images, test road images, and project videos are available in the repository. Along with the final images uploaded.

### This project is about implementing an image pipeline to detect street's lane lines.

● Compute the camera calibration matrix and distortion coefficients given a set of
chessboard images.

● Apply a distortion correction to raw images.

● Use color transforms, gradients, etc., to create a thresholded binary image.

● Apply a perspective transform to rectify binary image ("birds-eye view").

● Detect lane pixels and fit to find the lane boundary.

● Determine the curvature of the lane and vehicle position with respect to center.

● Warp the detected lane boundaries back onto the original image.

● Output visual display of the lane boundaries and numerical estimation of lane curvature
and vehicle position.

### Discussion:

Although this architecture worked well for the provided video, honestly I found issues in the challenge videos.

Sometimes, it was very difficult to qualify/fit point or lane lines. Perhaps the lane lines did not appear in the region of interest or the road had some pavement color issues or very sudden curvatures.

Moreover, some countries may not have the proper infrastructure. So I am expecting in the next chapters to learn more techniques. I think it can get more complex
and depend on other input sources like radar for example along with the cameras.
