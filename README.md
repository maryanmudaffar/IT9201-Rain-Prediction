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
