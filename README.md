# Survival Detection — Classification

This repository contains my solution notebook for the **Survival Detection** competition conducted as part of the **IIT Madras BS in Data Science & Applications** program.

The task was to predict whether a passenger survived or not using historical maritime passenger data.

---

## Task Summary
- **Problem type:** Binary classification  
- **Target variable:** `Outcome`
  - `1` → Survived  
  - `0` → Did not survive  
- **Evaluation metric:** Accuracy  

---

## Dataset
The dataset provided by the competition includes:
- Obfuscated feature names  
- Missing values  
- Added noise to simulate real-world data  

### Files used
- `maritime_train.csv` – training data with labels  
- `maritime_test.csv` – test data without labels  

External lookup tables or known survival labels were **not used**, as per competition rules.

---

## What I Did
- Performed basic data cleaning and preprocessing  
- Handled missing values  
- Encoded categorical features where required  
- Scaled numerical features  
- Trained classification models  
- Evaluated performance using accuracy  
- Generated predictions for the final submission  

---

## Results
The notebook focuses on building a clean and generalizable model rather than overfitting to the leaderboard.

*(Exact accuracy depends on the hidden test set.)*

---

## Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## Files in This Repository
- `survival-detection-classification.ipynb` – final submitted notebook  
- `README.md` – project description  

---

## Notes
This notebook was submitted to the official competition platform and is shared here for learning and reference purposes.

---
