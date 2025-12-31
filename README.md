# Healthcare Readmission Prediction — Artificial Neural Network

## Overview
This project builds an Artificial Neural Network (ANN) to predict whether a patient will be readmitted to a hospital within 30 days of discharge. The model uses patient demographic and clinical data to identify high-risk cases and support hospitals in improving patient care and reducing unnecessary readmissions.

## Problem Statement
Hospital readmissions increase healthcare costs and often indicate gaps in patient care. The objective of this project is to build a predictive model that can accurately identify patients who are likely to be readmitted, enabling proactive interventions.

## Dataset
The dataset contains healthcare records with features such as:
- Patient demographics (age, gender, etc.)
- Medical history and diagnoses
- Treatment and discharge information

Each record includes a target variable indicating whether the patient was readmitted within 30 days.

## Methodology

### Data Preprocessing
- Handled missing values and outliers
- Encoded categorical variables
- Applied feature scaling using standardization or normalization

### Model Development
- Designed an Artificial Neural Network using TensorFlow and Keras
- Used dense layers with appropriate activation functions
- Applied backpropagation and gradient descent for optimization

### Training and Evaluation
- Trained the model on the training dataset
- Evaluated model performance using accuracy and loss metrics
- Visualized training and validation curves

## Results
The ANN model achieved good predictive performance and demonstrated the ability to identify patients at high risk of readmission.

## Technologies Used
- Python
- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib

## How to Run

1. Clone the repository:
git clone https://github.com/div72ya/healthcare-readmission-ann.git

2. Navigate to the project directory:
cd healthcare-readmission-ann

3. Install dependencies:
pip install pandas numpy tensorflow scikit-learn matplotlib

4. Open and run the notebook:
Neural_Network_mini_project.ipynb

## Future Improvements
- Try different neural network architectures and hyperparameters
- Incorporate feature importance analysis
- Deploy the model as a web-based prediction service

## Acknowledgements
This project was developed as part of an academic data science mini project to explore neural networks on healthcare data.

## Contact
GitHub: https://github.com/div72ya  
LinkedIn: https://linkedin.com/in/divya-sharma-student
