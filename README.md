#  Iris Flower Species Classification using KNN

This project implements a K-Nearest Neighbors (KNN) classifier using the popular Iris flower dataset. The goal is to accurately classify iris flowers into one of three species based on their sepal and petal dimensions.

---

## 📂 Dataset

The dataset contains 150 samples of iris flowers with the following features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species (target variable)

📎 **Dataset source**: [Kaggle - Iris Flower Dataset](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)

---

##  Data Preprocessing

- Loaded the dataset using Pandas.
- Checked for null/missing values.
- Converted the categorical `Species` column into numerical labels using `LabelEncoder`.

---

## 🧠 Model: K-Nearest Neighbors (KNN)

Implemented KNN **from scratch** in NumPy with support for:
- Euclidean Distance
- Manhattan Distance
- Cosine Similarity

Evaluation was done using:
- Train-Test Split (80/20)
- Accuracy Score
- Confusion Matrix
- Classification Report
- K-Fold Cross Validation

---

## 📈 Results


| Distance Metric     | Accuracy |
|---------------------|----------|
| **Euclidean** (default)  | 100%     |
| **Cosine Similarity**    | 97%      |
| **Manhattan Distance**   | 90%      |
| **Scikit-learn KNN**     | 100%     |

- Petal Length and Petal Width were identified as the most influential features for classifying species.
- The custom implementation performs competitively with the built-in scikit-learn KNN.
---

## 🧪 Libraries Used

- NumPy
- Pandas
- scikit-learn (for evaluation purposes)
- Matplotlib, Seaborn (for visualization)

---

## 📊 Visualizations

- Feature distributions by species
- Correlation heatmaps
- Confusion matrix heatmaps

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/kapihllkumar/Iris-KNN-Classifier.git
   cd Iris-KNN-Classification
