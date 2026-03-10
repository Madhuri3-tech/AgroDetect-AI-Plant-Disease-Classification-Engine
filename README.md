AgroDetect AI – Plant Disease Classification Engine

Project Overview

AgroDetect AI is an Artificial Intelligence based system designed to detect and classify plant diseases using leaf images. The system uses Deep Learning and Convolutional Neural Networks (CNN) to analyze plant leaf images and identify diseases at an early stage.
This project helps farmers and agricultural experts detect crop diseases quickly, enabling timely treatment and improving crop productivity.

Objectives

To develop an AI-based plant disease detection system.
To classify plant diseases from leaf images using deep learning.
To assist farmers in early disease identification.
To improve agricultural productivity and crop health monitoring.

Features

Automatic plant disease detection
Image-based classification system
Deep learning model for high accuracy
User-friendly interface for image upload
Disease prediction with possible solutions

System Architecture

User Upload Leaf Image
        │
        ▼
Image Preprocessing
(Resize, Normalize)
        │
        ▼
Feature Extraction
(CNN Layers)
        │
        ▼
Deep Learning Model
(Disease Classification)
        │
        ▼
Prediction Result
(Disease Name + Treatment)

 Technology Stack
 
 Programming Language

Python
Libraries

TensorFlow / Keras
OpenCV
NumPy
Pandas
Matplotlib

Frameworks

Flask / FastAPI (Backend)
Streamlit (Frontend)

Dataset

PlantVillage Dataset

Project Structure

AgroDetect-AI/
│
├── dataset/
│   ├── train/
│   └── test/
│
├── model/
│   └── plant_disease_model.h5
│
├── app.py
├── train_model.py
├── predict.py
├── requirements.txt
└── README.md
