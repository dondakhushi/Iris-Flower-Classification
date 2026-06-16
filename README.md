# 🌸 Iris Flower Classification using Machine Learning

## 📌 Project Overview

The Iris Flower Classification project is a supervised Machine Learning classification task that predicts the species of an iris flower based on its physical measurements.

The model is trained using the famous Iris dataset and classifies flowers into one of the following species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

This project demonstrates the complete machine learning workflow, including data preprocessing, data visualization, model training, prediction, and performance evaluation.

---

## 🎯 Objectives

* Load and analyze the Iris dataset.
* Perform data cleaning and preprocessing.
* Convert categorical labels into numerical values.
* Split the dataset into training and testing sets.
* Train a K-Nearest Neighbors (KNN) classification model.
* Evaluate model performance using various metrics.
* Visualize results using a confusion matrix heatmap.

---

## 📂 Dataset Information

The dataset contains 150 flower samples with the following features:

| Feature       | Description          |
| ------------- | -------------------- |
| SepalLengthCm | Length of sepal (cm) |
| SepalWidthCm  | Width of sepal (cm)  |
| PetalLengthCm | Length of petal (cm) |
| PetalWidthCm  | Width of petal (cm)  |
| Species       | Flower species       |

### Target Classes

* Iris-setosa
* Iris-versicolor
* Iris-virginica

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Structure

```text
Iris-Flower-Classification/
│
├── Iris.csv
├── Iris-Flower-Classification.py
├── README.md
├── requirements.txt
└── screenshots/
    └── confusion_matrix.png
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/dondakhushi/Iris-Flower-Classification.git
```

### Move to Project Folder

```bash
cd Iris-Flower-Classification
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Project

```bash
python Iris-Flower-Classification.py
```

---

## 🔄 Machine Learning Workflow

### 1. Load Dataset

Read the Iris.csv dataset using Pandas.

### 2. Data Exploration

* View dataset structure
* Check missing values
* Analyze feature information

### 3. Data Preprocessing

* Remove unnecessary columns
* Encode species labels into numerical values

### 4. Train-Test Split

Split data into:

* 80% Training Data
* 20% Testing Data

### 5. Model Training

Train a K-Nearest Neighbors (KNN) classifier.

### 6. Prediction

Predict flower species using the trained model.

### 7. Evaluation

Evaluate model using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### 8. Visualization

Display confusion matrix using a heatmap.

---

## 📊 Evaluation Metrics

### Accuracy

Measures how many predictions are correct.

### Classification Report

Provides:

* Precision
* Recall
* F1-Score
* Support

### Confusion Matrix

Shows correct and incorrect predictions for each class.

---

## 📈 Sample Output

```text
Accuracy: 1.0

Classification Report:

              precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

accuracy                           1.00        30
```

---

## 🚀 Future Improvements

* Implement Logistic Regression
* Apply Random Forest Classifier
* Use Support Vector Machine (SVM)
* Build a Streamlit Web Application
* Deploy the model online

---

## 🎓 Learning Outcomes

By completing this project, you will learn:

* Supervised Machine Learning
* Classification Algorithms
* Data Preprocessing
* Label Encoding
* Model Evaluation Techniques
* Data Visualization

---

## 👩‍💻 Author

Khushi Donda

Data Science & Machine Learning Enthusiast
