# Lane Line detection

**Lane Line detection is a critical component for self driving cars and also for computer vision in general. This concept is used to describe the path for self-driving cars and to avoid the risk of getting in another lane.**

**In this project, we build a machine learning project to detect lane lines in real-time. We will do this using the concepts of computer vision using OpenCV library. To detect the lane we have to detect the white markings on both sides on the lane.**

**Category:** Deep Learning, Machine Learning, Computer Vision

**Programming Language :** Python

**Tools & Libraries :** OpenCV

**IDE :** Google Colab

**Front End :** NA

**Back End :** Python

## Road Lane-Line Detection with Python & OpenCV

Using computer vision techniques in Python, we will identify road lane lines in which autonomous cars must run. This will be a critical part of autonomous cars, as the self-driving cars should not cross it’s lane and should not go in opposite lane to avoid accidents.

## Frame Masking and Hough Line Transformation

To detect white markings in the lane, first, we need to mask the rest part of the frame. We do this using frame masking. The frame is nothing but a NumPy array of image pixel values. To mask the unnecessary pixel of the frame, we simply update those pixel values to 0 in the NumPy array.

After making we need to detect lane lines. The technique used to detect mathematical shapes like this is called Hough Transform. Hough transformation can detect shapes like rectangles, circles, triangles, and lines.

## Summary

This is a Python project in machine learning, which is helpful for the data science aspirants to master machine learning and gain expertise.
