# 🤚 ASL Gesture Sensing Device (Harpocrates)

Welcome to **Harpocrates**, an innovative device designed to detect American Sign Language (ASL) gestures and provide real-time predictions. Currently, it supports basic signs like "Hello" and "Thank you," with the potential for expanding its repertoire through further training.

## 🔧 Technologies Used
`Python` `TensorFlow` `MediaPipe`

## 📝 Project Description
**Harpocrates** employs MediaPipe for hand, pose, and face detection, utilizing a Sequential Model with LSTM and Dense Layers for prediction. It captures 30 frames per action, ensuring accurate recognition. Once a gesture is predicted, it is converted to speech, making communication seamless.

**Harpocrates** serves as a bridge between sign language users and those unfamiliar with it, facilitating communication and understanding.

## 📊 Categorical Accuracy Graph
![Categorical Accuracy Graph](Media/accuracy.png)

This graph illustrates the categorical accuracy's progression with increasing epochs during model training.

## 🔄 Confusion Matrix for Predictions
![Confusion Matrix](Media/confusion_matrix.png)

## 📸 Screenshots
![Face, Pose, and Hands Detection](Media/Screenshot%20(10).png)

Face, pose, and hands detection in action.

![Real-Time Gesture Prediction](Media/detector.gif)

Real-time gesture prediction.

![Model Image 1](Media/1.png)
![Model Image 2](Media/2.png)

3D model of **Harpocrates**.

## 🔗 References
This project draws inspiration and guidance from [Nicholas Renotte's tutorial](https://www.youtube.com/watch?v=doDUihpj6ro).

## 📜 License
[![License](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)

Feel free to explore and contribute to **Harpocrates**! 🚀
