# 🧪 Task 4 — Logistic Regression Classification

This project builds a binary classification model using Logistic Regression on the Breast Cancer Wisconsin Dataset.
The goal is to classify tumors as Malignant (1) or Benign (0).

**📌 Objective**

Build a logistic regression model

Preprocess the data

Train/Test split

Standardize features

Fit the model

Evaluate using classification metrics

Plot confusion matrix, ROC curve, and sigmoid function

Perform threshold tuning

**📁 Dataset**

Breast Cancer Wisconsin Dataset

diagnosis is the target

M → 1 (Malignant)

B → 0 (Benign)

Columns like Unnamed: 32 are removed because they contain empty values.

**⚙️ Technologies Used**

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

**🧹 Data Preprocessing**

Dropped unused column: Unnamed: 32

Removed missing values

Converted categorical target:

M → 1

B → 0

Splitted into training/testing sets

Scaled numerical features using StandardScaler

**🤖 Model Used**
Logistic Regression

Suitable for binary classification

Outputs probabilities using the sigmoid function

Final prediction based on threshold (default = 0.5)

📊 Evaluation Metrics

Accuracy

Precision

Recall

F1-score

Confusion Matrix

ROC Curve

AUC Score

📈 Graphs Generated

Confusion Matrix Heatmap

ROC Curve

Sigmoid Function Plot

🔍 Threshold Tuning

Tested thresholds:

0.5 (default)

0.4 (more sensitivity)

0.6 (more strict)
