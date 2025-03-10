**🌸 Iris Flower Classification 🌸**
**📋 Table of Contents**
1.Project Overview
2.Repository Structure
3.Problem Statement
4.Dataset Information
  4.1 Class Distribution
5.Setup and Installation
  5.1 Clone the Repository
  5.2 Install Dependencies  
6.Data Loading and Exploration
  6.1 Insights
  6.2 Feature Correlation
7.Data Visualization
  7.1 Pair Plot  
8.Data Preprocessing
  8.1 Feature Scaling
  8.2 Splitting the Data  
9.Model Training
  9.1 Algorithm Choice
  9.2 Training Code 
10.Model Evaluation
10.1 Accuracy
  10.2 Classification Report
  10.3 Confusion Matrix
11.Hyperparameter Tuning
  11.1 Grid Search 
12.Saving the Model
13.Future Improvements
14.Key Takeaways
15.How to Use the Model
  15.1 Load the Model
  15.2 Predict New Samples
16.Conclusion
 **Project Overview******
This project demonstrates a machine learning approach to classifying iris flowers into one of three species: Setosa, Versicolor, and Virginica. Using the popular Iris dataset, a Random Forest Classifier was trained to predict the species based on four features:

Sepal Length
Sepal Width
Petal Length
Petal Width
The model achieved 100% accuracy on the test set, showcasing the effectiveness of ensemble methods in classification tasks.

** 1. Problem Statement**
The task is to build a machine learning model to classify iris flowers into one of the three species using their sepal and petal measurements. The primary objective is to:

Train a model with high accuracy.
Evaluate the model’s performance using standard metrics.
Save the trained model for future use.

** 2. Dataset Information**
Source: Scikit-learn’s built-in Iris dataset.
Total Samples: 150
Features: 4 numeric features (sepal length, sepal width, petal length, petal width).
Classes: 3 (Setosa, Versicolor, Virginica).
Class Distribution:

Setosa: 50 samples
Versicolor: 50 samples
Virginica: 50 samples


