# **Finding Lane Lines on the Road**
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />


# Overview

In this project I develop a pipeline to  detect lane lines in images and videos using Python and OpenCV. OpenCV means "Open-Source Computer Vision", which is a package that has many useful tools for analyzing images. The package Moviepy helps analyze the video snippets.

The project requirements can be found [here](https://review.udacity.com/#!/rubrics/322/view) . Find below an example of expected results :

<img src="./test_images/solidYellowCurve2.jpg" width="400"/> <img src="./Results/new_s_solidYellowCurve2.jpg" width="400"/>

# Structure of the project

Two file are submitted for this project: a file containing project :

- **[code](./P1.ipynb)**

  The code is contained in a jupyter notebook and written  in python 3.0. The jupyter notebook was developed using Anaconda version 1.6.12. To run the code the following packages must be installed :
    1. OpenCV 3.4
    2. ffmpeg 3.4
    3. Moviepy

- **[writeup](./writeup.md)**

   This file contains a brief write up explaining the solution. This is a markdown file that can be visualized using any markdown viewer/reader (E.g github markdown). The markdown can also be converted into HTML or PDF for better portability and more viewing options.

# Dependencies
  The code and the writeup depend on the content of the following folders :

  1. test_images : contain sample images used for testing
  2. test_videos : contain sample videos used for testing
  3. results : Aggregate intermediate and final results of images and videos processing.
  4. test_videos_out : contain final result of processed video
  5. test_images_out : contain final result of processed images 

# Selft-Driving-Car-Udacity
