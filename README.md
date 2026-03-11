# 🎗️ Breast Cancer Detection via Machine Learning

This repository contains my machine learning project for breast cancer detection. It showcases how to apply classification and clustering algorithms using Scikit-learn, Pandas, and NumPy to analyze medical data. The code includes clear steps for data preprocessing, model training, and performance visualization using Matplotlib and Seaborn.

## 📊 Dataset Overview
* **Dataset:** Breast Cancer Wisconsin (Diagnostic) Database
* **Source:** UCI Machine Learning Repository
* **Instances:** 569 samples (patients)
* **Features:** 30 computed continuous numeric features capturing cell nucleus characteristics (radius, texture, perimeter, area, smoothness, etc.)
* **Target Variable:** * `1` = Malignant (Cancerous) - 212 cases (37.3%)
  * `0` = Benign (Non-Cancerous) - 357 cases (62.7%)

## 🛠️ Tech Stack & Libraries
* **Machine Learning:** `scikit-learn`
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`

## ⚙️ Data Preprocessing Pipeline
Before feeding the data into the machine learning models, rigorous preprocessing was applied to ensure high accuracy:
1. **Data Cleaning:** Verified zero null or missing values in the dataset.
2. **Label Encoding:** Converted the categorical target variable (`M` and `B`) into a binary format (`1` and `0`).
3. **Outlier Detection:** Utilized box plots to visualize data distributions and identify outliers.
4. **Feature Scaling:** Applied Standardization and Normalization to balance the feature scales, reducing the impact of outliers and optimizing the dataset for distance-based algorithms.
5. **Train-Test Split:** Divided the data into training (80%) and testing (20%) sets.

## 🧠 Models Implemented
This project explores both supervised classification and unsupervised clustering techniques to analyze the medical data.

**Supervised Learning (Classification):**
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Naive Bayes
* Decision Trees
* Support Vector Machines (SVM)

**Unsupervised Learning (Clustering & Dimensionality Reduction):**
* K-Means Clustering
* Agglomerative (Hierarchical) Clustering
* Divisive Clustering
* Gaussian Mixture Models (GMM)
* *Note: t-SNE was used extensively for high-dimensional cluster visualization.*

## 📂 Repository Structure
```text
📂 breast-cancer-detection/
│
├── 📂 data/                 
│   └── data.csv                 # The Wisconsin Breast Cancer dataset
│
├── 📂 notebooks/                # Jupyter/Colab Notebooks
│   ├── Decision.ipynb           # Decision Tree Classifier
│   ├── KNN.ipynb                # K-Nearest Neighbors Model
│   ├── logistic.ipynb           # Logistic Regression Model
│   ├── Naiive.ipynb             # Naive Bayes Classifier
│   └── SVM.ipynb                # Support Vector Machine
│
├── 📂 reports/                  # Project Documentation
│   ├── ML_Report_Preprocessing.pdf 
│   ├── ML_Report_Classification.pdf 
│   └── ML_Report_Clustering.pdf 
│
├── 📄 .gitignore                # Ignores junk files and cache
├── 📄 requirements.txt          # Dependencies for the project
└── 📄 README.md                 # Project overview
```
## How to Run the Project:
1. Clone the repository:
   ```text
   git clone [https://github.com/YourUsername/breast-cancer-detection.git](https://github.com/YourUsername/breast-cancer-detection.git) -> cd breast-cancer-detection
   ```
## Author: GAZANFAR ALI
