# AirDoodle
A **Virtual Whiteboard** created using **OpenCV** in Python which tracks the drawing marker using Webcam feed

An OpenCV project in Python which helps to **doodle on the screen by hovering a marker in the air**.

It uses Webcam as its input as a 2D matrix. It creates a color-filtered mask for any marker and thereby tracks that marker.
It stores the coordinates of all points the marker visits and stores in a data structure and simultaneously displays all stored points in each frame.

It even provides features like Clear and changing Colour of marker.

Concepts of **Colour Detection** and **Tracking** play the key role in this project.
