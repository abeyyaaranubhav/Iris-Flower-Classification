Iris Flower Classification using Machine Learning

This project demonstrates a complete machine learning workflow using the classic Iris dataset. The goal is to classify iris flowers into their respective species — Setosa, Versicolor, and Virginica — based on sepal and petal measurements. This dataset is widely used for introductory ML and pattern recognition tasks.

📘 Project Overview

The Iris dataset contains 150 samples, each with four features:
Sepal Length
Sepal Width
Petal Length
Petal Width
Using these measurements, the model predicts one of three species:
Iris setosa
Iris versicolor
Iris virginica
This project uses Logistic Regression from scikit-learn to build a multi-class classification model.

🧠 Features of the Project
✔ Loads the Iris dataset from scikit-learn
✔ Splits data into training and testing sets
✔ Standardizes feature values for better model performance
✔ Trains a Logistic Regression classifier
✔ Generates predictions
✔ Displays detailed model evaluation
✔ Plots a confusion matrix for easy visualization

🛠️ Technologies Used
Python
Scikit-learn
NumPy
Matplotlib
📂 Project Structure
├── iris_classifier.py          # Main ML model code
├── README.md                   # Project documentation
├── .gitignore                  # Clean repo configuration
└── LICENSE (optional)          # MIT license
▶️ How to Run the Project

Install required libraries:
pip install scikit-learn matplotlib numpy

Run the script:
python iris_classifier.py
The script will train the model, print the classification report, and show a confusion matrix plot.

📊 Model Evaluation

The model is evaluated using:
Accuracy
Precision
Recall
F1-score

Confusion Matrix
Logistic Regression performs extremely well on the Iris dataset, achieving high accuracy and very few misclassifications.

📈 Confusion Matrix Visualization

<img width="1111" height="927" alt="Screenshot 2025-12-06 154520" src="https://github.com/user-attachments/assets/604b92fc-2729-45ae-9a4a-3fd356f6fb49" />


🎯 Conclusion

This project is a beginner-friendly machine learning classification example. It covers data preprocessing, model training, evaluation, and visualization. You can easily extend it using different algorithms such as KNN, SVM, Random Forest, or Decision Trees.
