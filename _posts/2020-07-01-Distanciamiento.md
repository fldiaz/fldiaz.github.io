---
layout: post
title: Social Distancing Detection, a computer vision example.
---
In this example, I wanted to implement concepts of Computer Vision.
This work is inspired by Andrew Ng’s Landing AI team who created a Social Distancing Tool.
I’ll be using the YOLO v3 Object Detection Algorithm and OpenCV library.


This tool has the following features:
1. Transform the perspective of view to a bird’s-eye (top-down) view.
2. Detect persons in the frame with yolov3 and projected the points in bird’s eye view.
2. Calculated Euclidean distance between every points.
3. Calculated the percentage of persons that are no respecting the social distancing.



![_config.yml]({{ site.baseurl }}/images/video_restricciones.avi)

The complete code can be viewed at [here](https://github.com/fldiaz/flask)
