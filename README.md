# Brain-Tumor-Classification-using-MRI-Decision-Tree-HOG-Streamlit

Python
Decision Tree
Streamlit

website Link : https://brain-tumor-classification-using-mri-8060.onrender.com/

This project is a Machine Learning based web application that classifies MRI brain scan images into different tumor categories using HOG (Histogram of Oriented Gradients) features and a Decision Tree classifier.
The application is built with Streamlit, allowing users to upload an MRI image and instantly receive a predicted tumor type along with confidence scores.

## Features

Upload MRI images (.jpg, .jpeg, .png)
Automatic image preprocessing
HOG feature extraction
Brain tumor classification using Decision Tree
Prediction confidence score
Probability breakdown for all classes
Interactive Streamlit interface

## Project Structure

brain-tumor-classification/
│
├── dataset/
│   ├── train/
│   └── test/
│
├── train_model.py          # Model training script
├── app.py                  # Streamlit web app
├── decision_tree_model.pkl # Saved trained model
├── scaler.pkl              # Saved scaler
├── label_encoder.pkl       # Saved label encoder
└── requirements.txt






## Feature Extraction
HOG (Histogram of Oriented Gradients)
Web Framework
Streamlit
Model Persistence

	

## Joblib

How It Works

Load MRI image

Convert image to grayscale

Resize to 128×128

Extract HOG features

Scale features using StandardScaler

Predict tumor class using Decision Tree

Display prediction and confidence score

## Installation
Step 1

Clone the repository

Copy
Step 2

Install dependencies

Copy
Step 3

Train the model

Copy
Step 4

Run the Streamlit app

Copy


Example Output

Prediction: Glioma

Confidence: 92.45%

Class Probabilities:

Glioma: 92.45%

Meningioma: 4.12%

Pituitary: 2.01%

No Tumor: 1.42%

## Model Details
Algorithm :  Decision Tree Classifier
Feature Extraction :
HOG
Image Size
   128 × 128
Max Depth
   20
Min Samples Split
   10
Scaling
StandardScaler


## Future Improvements
Replace Decision Tree with CNN / Transfer Learning
Add Grad-CAM visualization
Deploy on Streamlit Cloud
Add support for DICOM images
Improve accuracy with data augmentation

## Author

KHUSHI
Aspiring Data Analyst & AI/ML Enthusiast
Building practical projects in Machine Learning, NLP, and Data Analytics.
