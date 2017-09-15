# **Udacity Self-Driving Car Nanodegree - Finding Lane Lines on the Road** 
---

### About this project
The P1.ipynb notebook implements the pipeline which includes the following functions:
* **grayscale** turns images into grayscale
* **gaussian_blur** applies Gaussian blur to gray images
* **canny** applies edge detection using Canny transformation
* **region_of_interest** eliminates the unimportant region 
* **hough_lines** applies Hough transformation to find lines on the masked iamge
* **weighted_img** combines the Hough lines and the original images to create annotated images

### Potential shortcomings
Potential shortcomings can be found by applying the process to the 'challenge.mp4' video. The noise in the video and the curves of the road are not handled well by the process.

### Possible improvements 
Possible improvements include quadratic fit to annotate the lines with curves. Another improvement could be a way to filter out noise.
