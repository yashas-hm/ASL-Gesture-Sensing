# ASL Gesture Sensing 

This projects detects ASL gestures and then predicts the output in realtime.<br>
For the time being we have only added two signs ie. Hello and Thank you, more actions can be trained and added.

## Team Details
College Name : Indus University Ahmedabad<br>
Mentor       : Sejal Thakkar<br>
Students     : 
| Name | Role |
| :---: | :---: |
| **Yashas H Majmudar** | Model Generation and Dataset Creation | 
| Saumya Ramolia | Training Data |
| Khushi Manek | Design |
| Ritika Dhall | Research |

## Technologies Used

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)<br>
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)<br>
![MediaPipe](https://raw.githubusercontent.com/google/mediapipe/master/docs/images/mediapipe_small.png)

## Requirements
| Name | Version |
| :---: | :--- |
| Python | 3.9.5 | 
| mediapipe | 0.8.9.1 |
| tensorflow | 2.5.0 |
| pyttsx3 | 2.90 |
| numpy | 1.19.5 |
| opencv-python | 4.5.5.62 |
| matplotlib | 3.4.2 |

## Project Description
This Project uses mediapipe to detect hands, pose and face to predict actions and gestures. The project takes 30 frames, 30 times for a single action. We have used an Sequential Model with LTSM and Dense Layers.<br>
Once the action is predicted the action is converted to speech.

**Harpocrates** is a device that uses an in-built camera to take action inputs and uses this ASL_Gesture_Sensing Algorithm to predict the actions and convert them to text. The text is then converted to speech and played through the in-built speaker.<br>

This Project can be used by the people that sign, to explain themselves to the people who do not understand sign language.

## Categorical Accuracy Graph While Training Data
![Categorical Accuracy Graph](Media/accuracy.png)

## Confusion Matrix for the Predictions
![Confusion Matrix](Media/confusion_matrix.png)

## Screenshots
![ScreenShot](Media/Screenshot%20(10).png)

**Face, Pose and Hands Detection**

![Video](Media/detector.gif)

**Real Time Gesture Prediction**

![Model Image 1](Media/1.png)
![Model Image 2](Media/2.png)

**Harpocrates 3D Model**

## References
This project is made using the help of [Nicholas Renotte](https://www.youtube.com/watch?v=doDUihpj6ro).

## Liscense
[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)
