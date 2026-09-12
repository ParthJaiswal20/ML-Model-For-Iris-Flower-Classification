# 🌸 Iris Flower Classification

A supervised machine learning project that classifies **Iris flower species** based on their physical measurements using three different classification algorithms:

* **K-Nearest Neighbors (KNN)**
* **Logistic Regression**
* **Naive Bayes**

The models are trained and evaluated to compare their performance and identify the best-performing algorithm for the Iris dataset.

---

## 📌 Project Overview

Manual identification of Iris flower species based on sepal and petal measurements can be time-consuming and error-prone.

This project uses machine learning to automatically predict the species of an Iris flower from four physical measurements:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The target variable is the Iris species.

### 🌱 Species

* Iris-setosa
* Iris-versicolor
* Iris-virginica

---

## 🎯 Objective

The main objectives of this project are:

1. Prepare and preprocess the Iris dataset.
2. Train three different classification models.
3. Evaluate their performance.
4. Compare the models using appropriate evaluation metrics.
5. Identify the best-performing algorithm.

---

## 📊 Dataset

The dataset contains **150 samples** divided equally among three Iris species.

| Feature      | Description              |
| ------------ | ------------------------ |
| Sepal Length | Length of the sepal (cm) |
| Sepal Width  | Width of the sepal (cm)  |
| Petal Length | Length of the petal (cm) |
| Petal Width  | Width of the petal (cm)  |
| Species      | Target class             |

Each species contains **50 samples**.

> **Note:** The assignment intentionally uses only **50% of the dataset for training** and evaluates the models on the full dataset as specified in the problem statement.

---

## 🤖 Machine Learning Models

### 1. K-Nearest Neighbors (KNN)

KNN classifies a data point based on the classes of its nearest neighboring points.

### 2. Logistic Regression

Logistic Regression is a classification algorithm that estimates the probability of a data point belonging to different classes.

### 3. Naive Bayes

Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem and the assumption of feature independence.

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Train KNN
   ↓
Train Logistic Regression
   ↓
Train Naive Bayes
   ↓
Evaluate Models
   ↓
Compare Performance
   ↓
Select Best Model
```

---

## 📈 Model Comparison

The performance of all three models will be compared using appropriate classification metrics.

| Model               | Performance     |
| ------------------- | --------------- |
| KNN                 | To be evaluated |
| Logistic Regression | To be evaluated |
| Naive Bayes         | To be evaluated |

The final results will determine which algorithm performs best on the given dataset.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## 📂 Project Structure

```text
iris-flower-classification/
│
├── iris-classification.ipynb
├── README.md
└── dataset/
    └── iris.csv
```

---

## 🚀 Key Learning Outcomes

Through this project, I explored:

* Supervised Machine Learning
* Multi-class Classification
* K-Nearest Neighbors
* Logistic Regression
* Naive Bayes
* Data preprocessing
* Model training
* Model evaluation
* Comparing multiple ML algorithms

---

## ⚠️ Important Note

The Iris dataset is small, clean, and well-balanced. Therefore, very high model performance is expected.

This performance should **not automatically be considered representative of real-world ML problems**, where datasets may contain noise, missing values, class imbalance, and significantly more preprocessing requirements.

---

## 👨‍💻 Author

**Parth Jaiswal**

B.Tech CSE — AI/ML & Robotics
