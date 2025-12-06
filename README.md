# Iris Flower Classification using Machine Learning<br>

This project demonstrates a complete machine learning workflow using the classic Iris dataset. The goal is to classify iris flowers into their respective species — Setosa, Versicolor, and Virginica — based on sepal and petal measurements. This dataset is widely used for introductory ML and pattern recognition tasks.<br>

## Project Overview<br>

The Iris dataset contains 150 samples, each with four features:<br>
1. Sepal Length<br>
2. Sepal Width<br>
3. Petal Length<br>
4. Petal Width<br>
### Using these measurements, the model predicts one of three species:<br>
(i) Iris setosa<br>
(ii) Iris versicolor<br>
(iii) Iris virginica<br>
This project uses Logistic Regression from scikit-learn to build a multi-class classification model.<br>

## Features of the Project<br>
- Loads the Iris dataset from scikit-learn<br>
- Splits data into training and testing sets<br>
- Standardizes feature values for better model performance<br>
- Trains a Logistic Regression classifier<br>
- Generates predictions<br>
- Displays detailed model evaluation<br>
- Plots a confusion matrix for easy visualization<br>

## Technologies Used<br>
- Python<br>
- Scikit-learn<br>
- NumPy<br>
- Matplotlib<br>
## Project Structure<br>
├── iris_classifier.py          # Main ML model code<br>
├── README.md                   # Project documentation<br>
├── .gitignore                  # Clean repo configuration<br>
└── LICENSE           # MIT license<br>
## How to Run the Project<br>
### Install required libraries:<br>
pip install scikit-learn matplotlib numpy<br>
### Run the script:
python iris_classifier.py<br>
The script will train the model, print the classification report, and show a confusion matrix plot.<br>
## Model Evaluation<br>
### The model is evaluated using:
*Accuracy<br>
*Precision<br>
*Recall<br>
*F1-score<br>

### Confusion Matrix<br>
Logistic Regression performs extremely well on the Iris dataset, achieving high accuracy and very few misclassifications.<br>

### Confusion Matrix Visualization<br>

<img width="1111" height="927" alt="Screenshot 2025-12-06 154520" src="https://github.com/user-attachments/assets/604b92fc-2729-45ae-9a4a-3fd356f6fb49" />


### Conclusion

This project is a beginner-friendly machine learning classification example. It covers data preprocessing, model training, evaluation, and visualization. You can easily extend it using different algorithms such as KNN, SVM, Random Forest, or Decision Trees.
