# 🌧️ Rain Prediction in Australia
### IT9201 — Machine Learning and Data Mining | MSc Artificial Intelligence
**Bahrain Polytechnic | Lecturer: Dr. Shomona Gracia Jacob**

---

## 📋 Project Overview
Binary classification project predicting next-day rainfall 
using the Rain in Australia dataset (145,460 records, 49 weather stations).

**Problem type:** Supervised Binary Classification  
**Target:** RainTomorrow (Yes=1 / No=0)  
**Class imbalance:** 77.6% No Rain vs 22.4% Rain  

---

## 🤖 Models Used
| Model | F1-Score | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 62.68% | 86.93% |
| Decision Tree | 60.40% | ~75% |
| Random Forest ★ | 66.42% | 88.91% |
| XGBoost | 68.10% | 90.03% |

**Best model:** Random Forest + class_weight='balanced' + Threshold 0.465  
**Final metrics:** Accuracy=83.93% | Recall=70.90% | F1=66.42% | MCC=0.561

---

## 📁 Repository Structure
1. notebook/   → Jupyter Notebook (.ipynb)
2. report/     → IEEE Project Report (.docx)
3. data/       → Dataset link (weatherAUS.csv)
4. orange/     → Orange unsupervised workflow (.ows)

---

## 🛠️ Tools & Libraries
- Python 3.13 | Scikit-learn 1.7.2 | XGBoost 3.2.0
- SHAP 0.51.0 | LIME 0.2.0.1
- Orange 3 (no-code unsupervised analysis)
- Pandas | NumPy | Matplotlib | Seaborn

---
## 📓 View Notebook
[![Open in nbviewer](https://img.shields.io/badge/View-nbviewer-orange)](https://nbviewer.org/github/maryanmudaffar/IT9201-Rain-Prediction/blob/main/Rain_Prediction_IT9201_v5_FINAL.ipynb)

---
## 📊 Dataset
**Source:** [Kaggle — Rain in Australia](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)  
**Origin:** Australian Bureau of Meteorology
