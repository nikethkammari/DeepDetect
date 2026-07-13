# AI-Based Agricultural Crop Recognition from Field Images Using Machine Learning

## Overview

Agricultural Crop Recognition is an intelligent machine learning application that automatically identifies different crop species from field images. The system utilizes image processing and machine learning techniques to classify crops accurately, helping farmers, researchers, and agricultural professionals make informed decisions.

The application provides a graphical user interface (GUI) that allows users to upload datasets, preprocess images, train multiple machine learning models, compare their performance, and predict crop categories from new field images.

---

## Features

- Upload crop image dataset
- Automatic image preprocessing
- Image resizing and normalization
- Train-Test dataset splitting
- Multiple Machine Learning algorithms
  - Multinomial Naive Bayes
  - Gaussian Naive Bayes
  - Random Forest Classifier
- Performance evaluation
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Confusion Matrix visualization
- Model comparison graphs
- Real-time crop prediction from field images
- User-friendly Tkinter GUI

---

## Technologies Used

### Programming Language
- Python 3.x

### Libraries
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Pillow (PIL)
- Joblib
- Tkinter

---

## Project Structure


Project/
│
├── Dataset/
│ ├── Crop_1/
│ ├── Crop_2/
│ ├── Crop_3/
│ └── ...
│
├── model/
│ ├── X.txt.npy
│ ├── Y.txt.npy
│ ├── Multi_NBC_Model.pkl
│ ├── naive_bayes.pkl
│ └── random_forest.pkl
│
├── Main.py
├── background.png
├── README.md
└── requirements.txt

---

## Workflow

1. Upload the crop image dataset.
2. Perform image preprocessing.
3. Generate feature vectors.
4. Split dataset into training and testing sets.
5. Train Machine Learning models.
6. Evaluate model performance.
7. Compare algorithm results.
8. Predict crop type from a new image.

---

## Machine Learning Algorithms

### Multinomial Naive Bayes
A probabilistic classifier suitable for classification tasks with discrete feature representations.

### Gaussian Naive Bayes
Assumes features follow a Gaussian distribution and performs fast probabilistic classification.

### Random Forest Classifier
An ensemble learning algorithm that combines multiple decision trees to improve classification accuracy and reduce overfitting.

---

## Evaluation Metrics

The system evaluates each model using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Installation

Clone the repository

```bash
