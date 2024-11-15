# Cardiovascular Disease Detection Using Deep Learning and Machine Learning Models on ECG Images
## Group Members
HITIK ADWANI - 22BDS029  
LAKSHYA BABEL - 222BDS033  
ABHIJIT SINGH - 22BDS054  
SURYANSH AYUSH - 22BDS057

## Overview
This project implements a system for cardiovascular disease detection using ECG images. By leveraging advanced Machine Learning (ML) and Deep Learning (DL) techniques, including Convolutional Neural Networks (CNNs), the system automates early diagnosis and improves the accuracy of heart disease detection.
## Features

1. Preprocessing Techniques:
    Grayscale conversion.
    Extraction of 12-lead ECG signals.
    Background noise removal.
    Signal isolation via contour techniques.
2. Machine Learning Models:
    Logistic Regression
    K-Nearest Neighbors (KNN)
    Support Vector Machines (SVM)
3. Deep Learning Model:
    Convolutional Neural Network (CNN) with state-of-the-art      layers for feature extraction and classification.

## Dataset

The dataset contains ECG images representing both normal and abnormal heart activities. It is sourced from [Mendeley data](https://data.mendeley.com/datasets/gwbz3fsgp8/2).

## Methodology
1. Data Preprocessing:
Convert ECG images to grayscale.
Apply Gaussian filtering and thresholding.
Extract and trace individual leads.
2. Model Training:
Train ML and CNN models using preprocessed ECG images.
3. Evaluation:
Assess model performance using metrics like Accuracy, Precision, Recall, and F1-Score.


## Project Structure
.
.
├── Data_Preprocessing/
│   ├── Data_original/
│   │   ├── Infected
│   │   ├── Normal
│   └── Final_1D_images/
│   |   ├── final_1D.csv
│   └── processed_contours_images/
│       ├── Infected
│       ├── Normal
└── colabs/
    ├── Cardiovascular_Detection_DL.ipynb
    └── Cardiovascular_Detection_ML.ipynb
          

## Conclusion

This project demonstrates the potential of leveraging Machine Learning and Deep Learning models for early detection of cardiovascular diseases using ECG images. The proposed system achieved high accuracy across multiple models, with the CNN model demonstrating superior performance in both training (98% accuracy) and validation (92% accuracy). 

The system's automated approach offers a fast, reliable, and scalable solution for heart disease detection, reducing dependency on manual ECG interpretation. The study also highlights the importance of preprocessing techniques like grayscale conversion and signal extraction to improve model performance.

Future enhancements include extending the model to detect multiple heart conditions, further optimizing feature extraction, and improving overall accuracy. These advancements could make the system even more applicable in clinical settings, particularly for telemedicine and remote healthcare solutions.



## Contributing

Contributions are welcome! Please feel free to submit a Pull Request to the [Cardiovascular_Detection repository](https://github.com/hitikadwani/CardioVascular_Detection.git).

Link to report:  

