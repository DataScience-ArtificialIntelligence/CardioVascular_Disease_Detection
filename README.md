# Cardiovascular Disease Detection Using Deep Learning and Machine Learning Models on ECG Images
## Group Members
HITIK ADWANI - 22BDS029  
LAKSHYA BABEL - 222BDS033  
ABHIJIT SINGH - 22BDS054  
SURYANSH AYUSH - 22BDS057

## Overview
This project implements a system for cardiovascular disease detection using ECG images. By leveraging advanced Machine Learning (ML) and Deep Learning (DL) techniques, including Convolutional Neural Networks (CNNs), the system automates early diagnosis and improves the accuracy of heart disease detection.


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

## Project Setup

To set up this project locally, follow these steps:  

### Step 1: Clone the Repository  


```bash
git clone https://github.com/DataScience-ArtificialIntelligence/CardioVascular_Disease_Detection.git
```

### Step 2: Navigate to the Project Directory
```bash
cd CardioVascular_Detection 
``` 

### Step 3: Install Required Packages
```bash
pip install -r requirements.txt
```

### Step 4: Run Jupyter Notebooks
1. Open Jupyter Notebook:
2. In Jupyter Notebook, navigate to the notebooks folder.
3. Open and run Cardiovascular_Detection_DL.ipynb for the deep learning model or Cardiovascular_Detection_ML.ipynb for the machine learning model.



## Conclusion

This project demonstrates the potential of leveraging Machine Learning and Deep Learning models for early detection of cardiovascular diseases using ECG images. The proposed system achieved high accuracy across multiple models, with the CNN model demonstrating superior performance in both training and validation. 

The system's automated approach offers a fast, reliable, and scalable solution for heart disease detection, reducing dependency on manual ECG interpretation. The study also highlights the importance of preprocessing techniques like grayscale conversion and signal extraction to improve model performance.

Future enhancements include extending the model to detect multiple heart conditions, further optimizing feature extraction, and improving overall accuracy. These advancements could make the system even more applicable in clinical settings, particularly for telemedicine and remote healthcare solutions.



## Contributing

Contributions are welcome! Please feel free to submit a Pull Request to the [Cardiovascular_Detection repository](https://github.com/DataScience-ArtificialIntelligence/CardioVascular_Disease_Detection.git).

## Links  

[Link to report](https://drive.google.com/file/d/1g05qLyQw4gQHIu3E1OYCPLxhudNLyqiu/view?usp=sharing)  


