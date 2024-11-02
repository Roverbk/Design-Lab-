#Weather Condition Classifier Using Deep Learning
Introduction

The Weather Condition Classifier is a project that leverages deep learning to identify different weather conditions in real-time. By using a camera to capture images of the surroundings, the model classifies the current weather condition as one of four categories: Rainy, Sunny, Foggy, or Dark. The classification result is indicated by four LEDs of different colors, each corresponding to one of the four weather conditions.

Key Features

High accuracy in weather condition classification.
Cost-effective setup (completed the project within budget constraints).
Real-time weather classification, suitable for various applications like smart vehicles or weather monitoring systems.
Components Used

Camera module to capture real-time images.
Deep learning model for weather classification.
Microcontroller (e.g., Arduino) to process classification results and control LEDs.
LEDs of four different colors to indicate the weather condition:
Yellow for Sunny (S)
Blue for Rainy (R)
Red for Foggy (F)
Green for Dark (D)
Power supply to support the microcontroller and LED circuit.
Working Principle

The camera module continuously captures images, which are processed by a deep learning model trained to classify the weather conditions. Based on the classification output, the corresponding LED lights up, providing a clear and simple indication of the detected weather condition.

Model Calibration and Setup

The model was trained using a labeled dataset containing images of various weather conditions. Calibration involves fine-tuning the model to achieve the highest accuracy possible, ensuring it effectively distinguishes between the weather categories.
![Design Lab](https://raw.githubusercontent.com/Roverbk/Design-Lab-/main/design_lab.jpg)

Applications

This system can be used in automotive safety applications, where detecting weather conditions in real-time is essential for driver assistance. It can also be utilized in weather monitoring stations or as an educational project for students learning about image classification and embedded systems.
