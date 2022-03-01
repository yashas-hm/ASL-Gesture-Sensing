# ASL Gesture Sensing 

This projects detects ASL gestures and then predicts the output in realtime.

## Technologies Used

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)<br>
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)<br>
![MediaPipe](https://raw.githubusercontent.com/google/mediapipe/master/docs/images/mediapipe_small.png)

## Project Description
This Project uses mediapipe to detect hands, pose and face to predict actions and gestures. The project takes 30 frames, 30 times for a single action. I have used an Sequntial Model with LTSM and Dense Layers.<br>
This Project can also be used for people that sign, to explain themselves to the people who do not understand sign language.<br>

## Screenshots
![ScreenShot](Media/Screenshot%20(10).png)

**Face, Pose and Hands Detection**

![Video](Media/detector.gif)

**Real Time Gesture Prediction**

## Reference
This project is made using the help of [Nicholas Renotte](https://www.youtube.com/watch?v=doDUihpj6ro).

## Liscense
[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)
