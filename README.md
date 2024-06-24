# Autonomous Driving Car Detection with YOLO 🚙

This project focuses on implementing an **object detection** system for autonomous driving using the powerful **YOLO (You Only Look Once)** model. The main goal is to build a car detection system that identifies cars in images captured by a camera mounted on the hood of a self-driving car.
<center> <img src="nb_images\dataset-card.png" style="width:400px;"></center>

![Object Detection](https://img.shields.io/badge/Skill-Object%20Detection-yellow)
![YOLO model](https://img.shields.io/badge/Skill-YOLO%20Model-blueviolet)
![Image Preprocessing](https://img.shields.io/badge/Skill-Image%20Preprocessing-green)
![TensorFlow](https://img.shields.io/badge/Skill-TensorFlow-orange)
![Keras](https://img.shields.io/badge/Skill-Keras-yellow)
![Computer Vision](https://img.shields.io/badge/Skill-Computer%20Vision-brightblue)
![Bounding Box Visualization](https://img.shields.io/badge/Skill-Bounding%20Box%20Visualization-brightblue)
![Python Programming](https://img.shields.io/badge/Skill-Python%20Programming-orange)

## Frameworks and Libraries
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.16.1-orange.svg?style=flat&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-3.3.3-red.svg?style=flat&logo=keras)
![NumPy](https://img.shields.io/badge/NumPy-1.26.4-blue.svg?style=flat&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.6.2-green.svg?style=flat&logo=matplotlib)

## Project Architecture
1. **Data Labeling**:
   - `Bounding boxes` drawn around cars in the images.

2. **Model Loading**:
   - Pre-trained `YOLO model` loaded.

3. **Image Preprocessing**:
   - Preparing images for the model.

4. **Model Prediction**:
   -  Running the model to detect cars.

5. **Result Visualization**:
   - Drawing bounding boxes on detected cars.

## Key Features
- Implementation of the `YOLO object detection model`.
- Efficient `image preprocessing pipeline`.
- Accurate `car detection in real-time` images.
- Visualization of detection results with `bounding boxes`.

## Usage
- Download the pre trained model data from [here](https://drive.google.com/file/d/1ozWxLf-JY6Qe6Ik6-KLVCOdayGipYj-T/view?usp=drive_link) and put it in the root directory.
- Ensure all dependencies are installed (TensorFlow, Keras, PIL, etc.).
- Load the pre-trained YOLO model.
- Preprocess input images.
- Run the YOLO model to detect cars.
- Visualize the results with bounding boxes drawn on detected cars.

## Results

The project successfully detects cars in images taken from a car-mounted camera. The detected cars are highlighted with bounding boxes, demonstrating the effectiveness of the YOLO model in real-time object detection.
<center>
<img src="nb_images\result.png" style="width:400px;"></center>
