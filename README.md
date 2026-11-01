# Machine Learning Lab (Experiments 1 to 8)

This repository contains the complete practical programs and actual execution output screenshots for the Machine Learning Laboratory (CSE II Year), covering Experiments 1 through 8.

---

## Experiment Summary & Output Verification

| No. | Experiment Name | Script | Dataset | Screenshots Included | Status |
|:---:|:---|:---:|:---:|:---|:---:|
| **01** | Data Cleaning (Missing Values & One-Hot Encoding) | [`Exp1.py`](Exp1/Exp1.py) | Titanic (`seaborn`) | [`Exp1_1.jpeg`](Exp1/Exp1_1.jpeg) (Terminal Execution) | Verified |
| **02** | Train & Test Fairly (KNN Classification) | [`Exp2.py`](Exp2/Exp2.py) | Iris (`scikit-learn`) | [`Exp2_1.jpeg`](Exp2/Exp2_1.jpeg) (Terminal Execution) | Verified |
| **03** | Linear Regression (Predict Fuel Efficiency) | [`Exp3.py`](Exp3/Exp3.py) | Auto MPG (`seaborn`) | [`Exp3_1.jpeg`](Exp3/Exp3_1.jpeg) (Terminal Execution)<br>[`Exp3_2.jpeg`](Exp3/Exp3_2.jpeg) (Regression Plot) | Verified |
| **04** | Classification: KNN vs SVM (Product Purchase) | [`Exp4.py`](Exp4/Exp4.py) | Social Network Ads | [`Exp4_1.jpeg`](Exp4/Exp4_1.jpeg) (Terminal Execution) | Verified |
| **05** | K-Means Clustering (Customer Segmentation) | [`Exp5.py`](Exp5/Exp5.py) | Mall Customers | [`Exp5_1.jpeg`](Exp5/Exp5_1.jpeg) (Terminal Execution)<br>[`Exp5_2.jpeg`](Exp5/Exp5_2.jpeg) (Cluster Scatter Plot) | Verified |
| **06** | Hierarchical Agglomerative Clustering | [`Exp6.py`](Exp6/Exp6.py) | Mall Customers | [`Exp6_1.jpeg`](Exp6/Exp6_1.jpeg) (Terminal Execution)<br>[`Exp6_2.jpeg`](Exp6/Exp6_2.jpeg) (Dendrogram Tree) | Verified |
| **07** | Ensemble Learning: Random Forest Classifier | [`Exp7.py`](Exp7/Exp7.py) | Breast Cancer (`sklearn`) | [`Exp7_1.jpeg`](Exp7/Exp7_1.jpeg) (Terminal Execution)<br>[`Exp7_2.jpeg`](Exp7/Exp7_2.jpeg) (Feature Importance) | Verified |
| **08** | Sequential Boosting (Gradient Boosting) | [`Exp8.py`](Exp8/Exp8.py) | Heart Disease UCI | [`Exp8_1.jpeg`](Exp8/Exp8_1.jpeg) (Terminal Execution) | Verified |

---

## Directory Structure

```text
ml/
├── README.md
├── Exp1/
│   ├── Exp1.py
│   └── Exp1_1.jpeg
├── Exp2/
│   ├── Exp2.py
│   └── Exp2_1.jpeg
├── Exp3/
│   ├── Exp3.py
│   ├── Exp3_1.jpeg
│   └── Exp3_2.jpeg
├── Exp4/
│   ├── Exp4.py
│   ├── Social_Network_Ads.csv
│   └── Exp4_1.jpeg
├── Exp5/
│   ├── Exp5.py
│   ├── Mall_Customers.csv
│   ├── Exp5_1.jpeg
│   └── Exp5_2.jpeg
├── Exp6/
│   ├── Exp6.py
│   ├── Mall_Customers.csv
│   ├── Exp6_1.jpeg
│   └── Exp6_2.jpeg
├── Exp7/
│   ├── Exp7.py
│   ├── Exp7_1.jpeg
│   └── Exp7_2.jpeg
└── Exp8/
    ├── Exp8.py
    ├── heart.csv
    └── Exp8_1.jpeg
```

---

## Environment & Requirements

- **Python Version:** 3.10+ (tested on Python 3.14)
- **Required Libraries:**
  ```bash
  pip install numpy pandas scikit-learn scipy matplotlib seaborn pillow
  ```

---

## Execution Guide

To run any experiment individually:

```bash
cd Exp1
python Exp1.py
```

All programs include prediction logic on unseen data points and automatically output performance metrics (accuracy, R² score, cluster statistics) alongside generated graphical plots.
