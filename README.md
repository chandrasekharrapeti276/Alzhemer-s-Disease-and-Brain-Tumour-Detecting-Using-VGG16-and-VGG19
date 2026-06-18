# Alzheimer’s Disease and Brain Tumor Detection using VGG16 & VGG19

## Overview

This project presents a deep learning–based approach for detecting Alzheimer’s disease and brain tumors from MRI/DICOM brain images using VGG16 and VGG19 convolutional neural networks (CNNs). The system provides dataset preprocessing, model training, performance comparison, and prediction through a graphical user interface (GUI).

The objective is to support early detection and assist medical image analysis using transfer learning techniques.

---

## Features

* Upload MRI/DICOM brain image datasets
* Preprocess and normalize medical images
* Train and evaluate VGG16 model
* Train and evaluate VGG19 model
* Compare model performance graphically
* Predict Alzheimer’s brain tumor presence from test images
* Generate confusion matrix and evaluation metrics

---

## Technologies Used

* Python
* Tkinter (GUI)
* TensorFlow / Keras
* OpenCV
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Pydicom

---

## Project Structure

```plaintext
Project/
│
├── Main.py
├── model/
│   ├── vgg16_weights.hdf5
│   ├── vgg19_weights.hdf5
│   ├── vgg16_history.pckl
│   ├── vgg19_history.pckl
│   ├── X.txt.npy
│   └── Y.txt.npy
│
├── Dataset/
│   ├── Normal/
│   └── Alzheimer Brain Tumor/
│
├── testData/
└── README.md
```

---

## Dataset

The dataset contains MRI/DICOM brain images categorized into:

* Normal
* Alzheimer Brain Tumor

Images are preprocessed and resized before training.

---

## System Workflow

### Step 1: Upload Dataset

Load MRI/DICOM brain images.

### Step 2: Dataset Preprocessing

* Read DICOM images
* Convert image format
* Resize images
* Normalize pixel values

### Step 3: Train Models

Train:

* VGG16
* VGG19

### Step 4: Model Evaluation

Evaluate performance using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

### Step 5: Prediction

Upload a new MRI image to predict whether the image is normal or contains Alzheimer’s brain tumor patterns.

---

## Installation

Install required libraries:

```bash
pip install tensorflow keras numpy opencv-python matplotlib seaborn scikit-learn pydicom
```

---

## Run the Project

Execute:

```bash
python Main.py
```

---

## Model Information

### VGG16

* Faster training
* Lower computational cost
* Good feature extraction capability

### VGG19

* Deeper architecture
* Improved learning of complex features
* Higher computational requirements

---

## Performance Metrics

The system compares both models using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix Visualization

---

## Applications

* Medical image classification
* Alzheimer’s disease screening
* Brain tumor detection
* Healthcare research

---

## Future Enhancements

* Multi-class disease classification
* Improved dataset balancing
* Explainable AI integration
* Web-based deployment
* Real-time prediction support

---

## Disclaimer

This project is intended for educational and research purposes only and should not be used as a standalone clinical diagnostic system.

---

## Author

Deep Learning Medical Imaging Project
