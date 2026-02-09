# Supervised Learning Models: Tree-Based Models & K-Nearest Neighbors (KNN)

## Objective
The objective of this project is to apply and compare different **supervised learning classification models**, with a focus on:
- Tree-based models
- K-Nearest Neighbors (KNN)

The models are evaluated using standard classification metrics to understand their performance on a medical diagnosis dataset.

---

## Dataset
**Breast Cancer Wisconsin Dataset**

- Type: Classification (Binary)
- Target Variable: `diagnosis`
  - M = Malignant
  - B = Benign
- Number of samples: 569
- Number of features: 30 (numerical)

This dataset is widely used for machine learning and medical diagnosis tasks.

---

## Models Implemented

### 1. Tree-Based Models
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

### 2. K-Nearest Neighbors (KNN)
- Tested multiple values of **k (1–20)**
- Identified optimal value of k using accuracy
- Feature scaling applied before KNN

---

## Evaluation Metrics
All models were evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-score

---

## Methodology
1. Load and preprocess the dataset
2. Encode categorical target variable
3. Split the data into training and test sets
4. Train each classification model
5. Generate predictions on the test set
6. Evaluate model performance
7. Compare results in a tabular format
8. Visualize KNN performance across different k values

---

## Results
- Tree-based models showed strong performance without feature scaling
- Random Forest and Gradient Boosting achieved higher accuracy than a single Decision Tree
- KNN performance varied with k and required feature scaling
- Optimal k was selected based on maximum test accuracy

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Git & GitHub

---

## 📁 Repository Structure
Supervised-Learning-Models/
│
├── data/
│ └── breast-cancer.csv
│
├── notebooks/
│ └── supervised_learning_models.ipynb
│
├── README.md
└── requirements.txt

---

## How to Run
1. Clone the repository
```bash
git clone https://github.com/sakshi17317/Supervised-Learning-Models.git
