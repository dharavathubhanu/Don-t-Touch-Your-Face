# Face Touch Detection using CNN

This project implements a deep learning model to detect whether a person touches their face or not, which can help reduce face-touching behavior in public health contexts like COVID-19 prevention. It uses Convolutional Neural Networks (CNNs) to classify input video/image data into different touch-related classes.

## Project Files

- Project_1_2_Qn2ModelTrainingCode.ipynb – Code for training the CNN model
- Testing(Don’t_Touch_Your_Face).ipynb – Code for testing the trained model
- face_touch_final_model.h5 – Final saved Keras model

## Objective

To automatically detect and classify facial touch events in real-time using image data and a deep learning classification model.

## Dataset Description

The dataset for this project was **self-collected from students in a classroom environment**. Images were manually categorized into three classes:
- **Touch** – Hand touching the face
- **No Touch without Hand** – Face visible, no hand
- **No Hand** – Neither face nor hand clearly visible

This real-world classroom dataset helped train the model with natural lighting, various face angles, and real human behavior, improving practical robustness.

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

## Requirements

Python 3.7+
TensorFlow 2.x
Keras
OpenCV
NumPy
Matplotlib

## Results
The model was trained on a classroom dataset and showed high accuracy on validation and test sets. It can make predictions on real-time webcam video frames.

## Future Scope
Real-time face-touch alert system

Mobile or web deployment

Integration with wearable devices

Enhanced dataset with more subjects and settings

## Author
Bhanu Prasad Dharavathu
