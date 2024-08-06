# Capstone-Project for Professional Certificate in ML and AI. 

## Project Title 
Prediction of Breast Cancer Type

## Project description
This project focuses on improving the detection and classification of breast cancer tumours using advanced ML techniques. Breast cancer is the most common cancer among women, and early detection is crucial. By utilizing the Breast Cancer Wisconsin (Diagnostic) Dataset, three models were tested: Decision Trees, NN and SVM. NN was recognized as the best model and was used to accurately classify tumours as either malignant (cancerous) or benign (non-cancerous). Overall aim of this project was to enhance diagnostic accuracy, providing better outcomes for patients and to use technology to assist medical professionals in making more informed decisions, ultimately improving the quality of care and survival rates of cancer patients. 

## Data
In this notebook, we usd the Breast Cancer Wisconsin (Diagnostic) Dataset available on Kaggle (https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset/data). The main objective using this data is to build classification models to predict whether the cancer type is Malignant or Benign.

## Model
This is a binary classification problem. Several machine learning models are considered highly effective in this case e.g logistic regression, SVM, decision trees or even neural networks. According to this requirements of this Capstone project, 3 models were evaluated (DT,NN,SVM), and the most effective one was selected - NN. 

## Hyperparameter optimisation
Total of six hyperparameters were tuned to find the optimal configuration for the neural network model.
Number of Layers (num_layers): Options were 1, 2, or 3 hidden layers.
Units per Layer (units): Options were 32, 64, or 128 units per layer.
Activation Function (activation): Options were ReLU (relu) or Tanh (tanh).
Optimizer (optimizer): Options were Adam (adam) or RMSprop (rmsprop).
Dropout Rate (dropout): Continuous range from 0 to 0.5.
Batch Size (batch_size): Options were 16, 32, or 64.

## Results
The model achieved an accuracy of 97% on the test data. This high accuracy indicates that the model effectively distinguishes between malignant and benign breast cancer cases. Sensitivity was 95%, indicating that the model correctly identified 95% of the malignant cases. This is crucial in a medical setting where false negatives (failing to detect cancer) need to be minimized. The specificity was 98%, meaning the model accurately identified 98% of benign cases. High specificity reduces false positives, preventing unnecessary anxiety and medical procedures for patients. The model had a misclassification rate of 3%, showing a low rate of incorrect predictions, which contributes to the model's reliability. The combination of a neural network architecture and hyperparameter tuning led to a robust model capable of handling complex patterns in the data. Hyperparameter tuning using Bayesian optimization significantly improved model performance by finding the optimal combination of layers, units, activation functions, and dropout rates. The model maintained a good balance between sensitivity and specificity, which is critical in medical diagnostics to ensure both false negatives and false positives are minimized.





