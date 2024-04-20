# Driver-Drowsiness-Detection
Data set used for Haar Cascade model training is attached to : https://www.kaggle.com/datasets/serenaraju/yawn-eye-dataset-new/data

This code can detect your eyes and alert when the user is drowsy.

***Applications*** <br><br>
This can be used by riders who tend to drive for a longer period of time that may lead to accidents.
<br><br><br>
***Code Requirements***
The example code is in Python (version 2.7 or higher will work).

<h3>Libraries</h3>
<br>
<ul>
  <li>import OpenCv</li>
  <li>import Tensorflow</li>
  <li>import pygame</li>
  <li>import Keras</li>
  <li>import numpy</li>
  <li>import matplotlib</li>
</ul>
<br>
<h2>Description</h2>
<p>A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.</p>

<h4>Algorithm</h4>
<p>Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye.</p>

<p>It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.</p>
