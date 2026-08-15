# Loan-Approval-Prediction
Loan Approval Prediction Using ANN

Overview

This project predicts whether a loan application will be Approved or Rejected using an Artificial Neural Network (ANN).

The project is developed using Python and TensorFlow/Keras in Google Colab.

Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn

 Dataset

The dataset contains 45,000 loan application records with 13 input features, including:

* Age
* Income
* Employment Experience
* Loan Amount
* Interest Rate
* Credit Score
* Credit History
* Previous Loan Default
* Education and other applicant details

Target: `loan_status`

* `0` → Loan Rejected
* `1` → Loan Approved

 ANN Model

Input Layer
     ↓
64 Neurons (ReLU)
     ↓
32 Neurons (ReLU)
     ↓
16 Neurons (ReLU)
     ↓
1 Neuron (Sigmoid)


Optimizer:Adam
Loss:Binary Crossentropy
Epochs:50
Batch Size:32

 Results

The model achieved approximately 90.8% test accuracy.

The project also includes:

* Loan approval distribution graph
* Accuracy and loss graphs
* Confusion matrix
* Classification report
* User-input loan prediction

Future Scope

* Streamlit Web Application
* Cloud Deployment
* Explainable AI
* Hyperparameter Optimization
