# Survival Detection

This project is a **binary classification task** from the IIT Madras BS in Data Science & Applications program.  
The goal is to predict whether a passenger survived or did not survive a historical maritime incident using passenger data.

---

## Problem
Given passenger details, predict:

- `1` → Survived  
- `0` → Did not survive  

This is a **classification problem**, and the model is evaluated using **accuracy**.

---

## Dataset
The dataset contains passenger-level data with:
- Missing values  
- Noisy features  
- Obfuscated column names  

These are intentional and meant to simulate real-world datasets.

### Files
- `maritime_train.csv` – training data with labels  
- `maritime_test.csv` – test data (no labels)  
- `sample_submission.csv` – submission format  

⚠️ Using external lookup tables or known survival labels is **not allowed**.

---

## Evaluation
Predictions are evaluated using **Accuracy**:


---

## Submission Format
The submission file must be a CSV with the following columns:

```csv
PassengerName,Outcome
"Braund, Mr. Owen Harris",0
"Heikkinen, Miss. Laina",1
