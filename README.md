# Coffee vs Juice Image Classifier

## Project Overview

This project demonstrates a basic image classification system trained to distinguish between two categories: Coffee and Juice.  
The model was created using Google’s Teachable Machine, exported in TensorFlow (Keras) format, and tested using a Python script to verify its performance on new input images.

---

## Objectives

- Train an image classifier using Teachable Machine with at least two distinct classes.
- Export the trained model in Keras format.
- Develop a Python script to load the model, preprocess input images, and make predictions.
- Document all steps and test results clearly.

---

## Tools and Technologies

- Teachable Machine by Google
- Python 3
- TensorFlow / Keras
- Google Colab

---

## Implementation Details

### 1. Model Training
- Two classes were defined: Coffee and Juice.
- 15 images were collected for each class.
- The model was trained using Teachable Machine’s image project interface.
- Evaluation was done using the platform’s internal preview/testing tool.

### 2. Model Export
- The trained model was exported in TensorFlow → Keras format.
- Exported files:
  - keras_model.h5 — The trained model file.
  - labels.txt — Text file containing class names.

### 3. Prediction Script
- A Python script (`predict.py`) was created to:
  - Load the Keras model and class labels.
  - Preprocess the input image (`test.jpg`).
  - Perform prediction and display confidence score.

### 4. Testing & Evaluation
- A test image of a coffee cup was used.
- The model successfully identified the correct class.
- A screenshot of the output (`screenshot.png`) is included as evidence.

---

## Files Included

The project includes the following files:

- predict.py: Python script to test the model.
- keras_model.h5: Exported Keras model file.
- labels.txt: Text file containing class labels.
- test.jpg: Sample image used for testing.
- screenshot.png: Screenshot showing the prediction result.



