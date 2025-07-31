# CodeAlpha_Iris-Flower-Classification

<img width="1024" height="367" alt="68747470733a2f2f7777772e656d6265646465642d726f626f746963732e636f6d2f77702d636f6e74656e742f75706c6f6164732f323032322f30312f497269732d446174617365742d436c617373696669636174696f6e2" src="https://github.com/user-attachments/assets/f5209b78-8558-43ae-b756-3678522d0a5b" />

This project demonstrates the process of classifying Iris flowers into their three species using machine learning algorithms. The analysis is performed within a Jupyter Notebook.

### Introduction 
The objective of this project is to create a model that can accurately classify Iris flowers into one of three species: Iris-setosa, Iris-versicolor, and Iris-virginica. The model uses measurements of the length and width of the flowers' petals and sepals to make its predictions.

### Dataset
The dataset used is iris.data.csv. It contains 150 instances of Iris flowers, with each of the three classes having 50 instances. There are five columns in the dataset: sepal_length, sepal_width, petal_length, petal_width, and the target species.
Link For DataSet : https://www.kaggle.com/datasets/saurabh00007/iriscsv

### Project Workflow 
The notebook follows a standard machine learning workflow:

#### Importing Libraries
Essential libraries such as numpy, pandas, matplotlib.pyplot, and seaborn are imported to handle data, perform calculations, and create visualizations.

#### Data Loading and Analysis
The dataset is loaded and a statistical summary of the data is displayed using df.describe(). The notebook also visualizes the data using a pair plot, histograms, box plots, kernel density estimate (KDE) plots, and violin plots to understand the distribution and relationships of the features.

#### Data Splitting: 
The data is separated into input features (X) and the target output (Y). The dataset is then split into training and testing sets, with 20% of the data designated for testing.

#### Machine Learning Models: 
Three classification algorithms from the scikit-learn library are used:

#### Support Vector Machine (SVM): 
This model achieved an accuracy of approximately 93.3% on the test data.

#### Logistic Regression:
This model was the most accurate, with a score of approximately 96.6% on the test data. A detailed classification report is also provided for this model.

#### Decision Tree Classifier: 
This model achieved an accuracy of approximately 90% on the test data.

#### Prediction on New Data: 
The notebook concludes by using the trained SVM model to predict the species for a new set of data points. The prediction for the new data [[3, 2, 1, 0.2], [4.9, 2.2, 3.8, 1.1], [5.3, 2.5, 4.6, 1.9]] is ['Iris-setosa', 'Iris-versicolor', 'Iris-virginica'].

