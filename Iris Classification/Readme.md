# Iris Flower Classification Project 🌸

This project focuses on classifying Iris flowers into three species: **Setosa**, **Versicolor**, and **Virginica**, based on their sepal and petal measurements. The goal is to train a machine learning model that can accurately predict the species of an Iris flower using the provided dataset.

---

## Project Overview

The Iris dataset is a classic dataset in machine learning, often used for classification tasks. This project uses a **RandomForestClassifier** to predict the species of Iris flowers based on four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

The model is trained on the dataset and evaluated using accuracy, a classification report, and a confusion matrix.

---

## Dataset

The dataset used in this project is the **Iris Species Dataset**, which can be downloaded from [Kaggle](https://www.kaggle.com/datasets/saurabh00007/iriscsv). It contains 150 samples of Iris flowers, with 50 samples from each of the three species.

### Features:
- `sepal_length`: Length of the sepal (in cm)
- `sepal_width`: Width of the sepal (in cm)
- `petal_length`: Length of the petal (in cm)
- `petal_width`: Width of the petal (in cm)

### Target:
- `species`: The species of the Iris flower (Setosa, Versicolor, or Virginica)

---

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/iris-classification.git
   cd iris-classification

## 📊 Exploratory Data Analysis (EDA)

The dataset is analyzed through visualizations such as:

- Histograms & scatter plots to observe feature distributions
- Pair plots to visualize relationships between features
- Correlation heatmaps to understand feature dependencies

## 🔥 Model Training & Evaluation

Various machine learning models are trained and evaluated, including:

- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**

The best-performing model is selected based on accuracy, precision, recall, and F1-score.


## Classification Report:

```bash
Accuracy: 1.00
Classification Report:
               precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30
```
## Confusion Matrix:
```bash
 [[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
```
Accuracy: 1.00
