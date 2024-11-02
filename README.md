# Weather Condition Classifier Using Deep Learning
## Introduction

The **Weather Condition Classifier** is a deep learning project designed to identify real-time weather conditions through image classification. Using a camera to capture surrounding images, the classifier determines the current weather condition as either **Rainy, Sunny, Foggy,** or **Dark**. The classification result is displayed through four distinct LEDs, each representing a different weather condition, providing a quick and clear visual indication.

## Key Features

- **High Accuracy:** Capable of accurately classifying various weather conditions.
- **Cost-Effective:** Designed with budget constraints in mind, making it accessible.
- **Real-Time Detection:** Ideal for applications requiring immediate feedback, such as smart vehicles or weather monitoring systems.

## Components Used

- **Camera Module** - Captures real-time images for classification.
- **Deep Learning Model** - Trained to classify weather conditions.
- **Microcontroller (e.g., Arduino)** - Processes classification results and controls LED indicators.
- **LED Indicators**:
  - **Yellow** for **Sunny** (S)
  - **Blue** for **Rainy** (R)
  - **Red** for **Foggy** (F)
  - **Green** for **Dark** (D)
- **Power Supply** - Supports the microcontroller and LED circuit.
  
## Working Principle

The camera module continuously captures images, which are processed by a deep learning model trained to classify the weather conditions. Based on the classification output, the corresponding LED lights up, providing a clear and simple indication of the detected weather condition.

## Model Calibration and Setup

The model was trained using a labeled dataset containing images of various weather conditions. Calibration involves fine-tuning the model to achieve the highest accuracy possible, ensuring it effectively distinguishes between the weather categories.

![Design Lab](https://raw.githubusercontent.com/Roverbk/Design-Lab-/main/design_lab.jpg)

## Applications

This system can be used in automotive safety applications, where detecting weather conditions in real time is essential for driver assistance. It can also be utilized in weather monitoring stations or as an educational project for students learning about image classification and embedded systems.

