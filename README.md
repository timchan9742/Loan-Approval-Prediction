# Loan Approval Prediction

## Overview
This project focuses on predicting loan approval on a highly imbalanced dataset, where approved loans are the minority but carry higher business importance. The workflow includes **EDA, Data Preprocessing, Model Training, Hyperparameter Tuning, and Model Evaluation**.

A **custom F1 score (β=0.5)** was used during model selection to prioritize precision for approved loans, while **PR-AUC (Average Precision)** was used for final evaluation to measure threshold-independent performance.

---

## Models
- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**
- **Random Forest**

**Results:**

| Model                 | Average Precision |
|-----------------------|-----------------|
| KNN                   | 0.88            |
| Logistic Regression   | 0.86            |
| Random Forest         | 0.92            |

Random Forest achieved the best overall performance.

## Usage
1. Clone the repository:
```bash
git clone <https://github.com/timchan9742/Loan-Approval-Prediction>
