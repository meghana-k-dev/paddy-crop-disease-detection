# paddy-crop-disease-detection
# Paddy Crop Disease Detection Using Machine Learning

## 📌 Project Overview

This project is a machine learning-based application for detecting diseases in paddy leaves.

The system uses two machine learning approaches:

- Support Vector Machine (SVM)
- Convolutional Neural Network (CNN)

The application predicts the disease from a test image and displays possible remedies for the detected disease.

## 🌱 Disease Classes

The system supports four classes:

- Leaf Blast
- Brown Spot
- Hispa
- Healthy

## 🛠️ Technologies Used

- Python
- CNN
- SVM
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- TensorFlow/Keras
- Tkinter
- Matplotlib
- Seaborn

## 🔄 Methodology

The project follows these steps:

1. Load the paddy leaf image dataset.
2. Preprocess the images.
3. Resize images to 32 × 32 pixels.
4. Normalize and shuffle the dataset.
5. Split the dataset into 80% training and 20% testing data.
6. Train and evaluate the SVM model.
7. Train and evaluate the CNN model.
8. Compare the performance of both models.
9. Upload a test image for disease prediction.
10. Display the predicted disease and possible remedies.

## 📊 Model Comparison

The project compares SVM and CNN using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

CNN achieved better performance than SVM in the project.

- SVM Accuracy: 40%
- CNN Accuracy: 98%

## 🖥️ Application

A Tkinter-based graphical user interface is provided to:

- Load the dataset
- Preprocess images
- Run SVM
- Run CNN
- Compare model performance
- Upload a test image
- Predict the disease
- Display possible remedies

## ▶️ How to Run

### 1. Install the required libraries

```bash
pip install -r requirements.txt
