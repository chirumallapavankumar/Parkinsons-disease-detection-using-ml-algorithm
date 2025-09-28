# 🧠 Parkinson's Disease Detection using Machine Learning

This project uses machine learning techniques to detect Parkinson's Disease based on biomedical voice and signal measurements. The model is trained on the dataset published on Kaggle by Manas Garg, which includes multiple vocal measurements and other related features.

---

## 📁 Dataset

**Source:** [Kaggle - Parkinson's Dataset by Manas Garg](https://www.kaggle.com/datasets/gargmanas/parkinsonsdataset)

**Filename:** `Parkinsson disease.csv`

**Features:**

- `MDVP:Fo(Hz)`, `MDVP:Fhi(Hz)`, `MDVP:Flo(Hz)` – Fundamental frequency and its variation
- `MDVP:Jitter(%)`, `MDVP:RAP`, `MDVP:PPQ`, `Jitter:DDP` – Measures of voice jitter
- `MDVP:Shimmer`, `MDVP:APQ3`, `MDVP:APQ5`, `Shimmer:APQ11`, `Shimmer:DDA` – Measures of voice shimmer
- `NHR`, `HNR` – Noise-to-harmonics and harmonics-to-noise ratio
- `RPDE`, `DFA`, `spread1`, `spread2`, `D2`, `PPE` – Nonlinear and dynamical complexity measures
- `status` – Target label (1: Parkinson’s positive, 0: healthy)

**Total Samples:** 195  
**Total Features:** 23  
**Target Variable:** `status`

---

## 🧠 ML Models Used

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting / XGBoost

---

## please find the attached file for the source code in main file

