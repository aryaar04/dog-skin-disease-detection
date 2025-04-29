# dog-skin-disease-detection
Dog Skin Disease Detection using Deep Learning
This project implements an image-based deep learning model to detect various skin diseases in dogs. It uses Convolutional Neural Networks (CNNs) to classify dog skin conditions based on image input, helping veterinarians and pet owners identify issues early and accurately.

Features
Image classification of dog skin diseases
Preprocessing and augmentation of image datasets
CNN model built and trained using TensorFlow/Keras
Accuracy/loss visualization for model performance
Confusion matrix and classification report for evaluation

Diseases Covered
The model is trained to detect the following skin conditions:
● Dermatitis
● Fungal_infection
● Healthy
● Hypersensitivity
● Demodicosis
● Ringworm

Tech Stack
Python 3.x
Jupyter Notebook
TensorFlow / Keras
OpenCV, NumPy, Matplotlib
scikit-learn

Dataset
A labeled dataset of dog skin images divided into training, validation, and test sets.
Dataset Type Percentage Number of Images
Train Set 70% 3022
Validation Set 20% 860
Test Set 10% 433
Total 100% 4315

Results
Final Training Accuracy:96%
Validation Accuracy: 92%
Evaluation metrics (confusion matrix, precision, recall, F1-score) included in the notebook
