Retina Gray-Scale Image Perception using Deep Learning

A deep learning project for analyzing retina images by converting them to grayscale and leveraging CNNs for feature extraction and classification. This repository demonstrates how medical image preprocessing and neural networks can be applied to retinal images to detect patterns and support automated diagnosis.

🔍 Project Overview

Retinal diseases, such as diabetic retinopathy and glaucoma, are among the leading causes of vision impairment worldwide. Early detection is critical for effective treatment.

This project focuses on:

Converting RGB retina images to grayscale to reduce complexity while retaining critical features.

Using Convolutional Neural Networks (CNNs) to extract meaningful patterns.

Training models to classify retina images into relevant categories.

By simplifying the images and applying deep learning, this project aims to create a pipeline that can assist in automated retinal image analysis.

⚙️ Features

✅ Load and preprocess retina images

✅ Convert images to grayscale for simplified analysis

✅ Train CNN-based models for classification

✅ Evaluate model performance with accuracy, precision, and recall metrics

✅ Easily extensible for other medical image datasets

🗂 Repository Structure
Retina-Gray-Scale-Image-Perception-using-Deep-Learning/
├── Codes/                     # Scripts for preprocessing, training, and evaluation
│   ├── preprocess.py
│   ├── train.py
│   └── evaluate.py
├── Dataset/                   # Retina image dataset
│   └── images/
├── requirements.txt           # Python dependencies
├── README.md                  # This file
└── .gitignore

💻 Installation

Clone the repository:

git clone https://github.com/HarshiniReddy1324/Retina-Gray-Scale-Image-Perception-using-Deep-Learning.git
cd Retina-Gray-Scale-Image-Perception-using-Deep-Learning


pip install numpy matplotlib opencv-python tensorflow scikit-learn

🧩 How to Use
1. Prepare the Dataset

Place your retina images in the Dataset/images/ directory.
Organize them by category if you have multiple classes:

Dataset/
├── normal/
└── diseased/

2. Preprocess Images
python Codes/preprocess.py


Converts RGB images to grayscale

Resizes and normalizes images

Saves processed data for model training

3. Train the Model
python Codes/train.py


Defines and trains the CNN architecture

Saves the trained model to Codes/models/

4. Evaluate Model Performance
python Codes/evaluate.py


Loads test data

Evaluates the trained model

Outputs metrics such as accuracy, precision, recall, and loss


📝 Publication

If you use this work in your research or projects, please cite our paper:
AIP Conf. Proc. 3028, 020025 (2024)
https://doi.org/10.1063/5.0212988
