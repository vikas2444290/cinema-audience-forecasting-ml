# Cinema Audience Forecasting – Machine Learning Project

## Problem Statement
This project was developed for the **Cinema Audience Forecasting** Kaggle competition.  
The objective is to **predict daily cinema audience counts** for movie–theatre combinations using historical booking and visit data.

The task is a **time-series forecasting problem**, where audience behavior is influenced by booking patterns, theatre characteristics, and calendar effects such as weekends and holidays.

---

## Dataset Overview
The dataset combines information from two sources:
- **BookNow** – Online ticket booking platform  
- **CinePOS** – On-site point-of-sale (POS) system  

It includes theatre metadata, booking transactions, daily audience counts, and calendar-related features.  
The dataset is anonymized and provided as part of the competition.

---

## Approach
The solution follows a structured machine learning pipeline:
- Data cleaning and preprocessing
- Feature engineering using temporal, booking, and theatre-level features
- Handling missing values and closed-theatre days
- Training and evaluating regression-based models
- Model tuning and experimentation to improve performance

The complete workflow is implemented end-to-end in the notebook.

---

## Models Used
- LightGBM  
- Random Forest Regressor  
- XGBoost (experimentation)

---

## Results
- **Final Rank:** **177 / 2632 participants**
- **Leaderboard Performance:** Top ~7%

This result reflects effective feature engineering and model optimization on a real-world forecasting problem.

---

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- LightGBM  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## Repository Contents
- `cinema_audience_forecasting.ipynb` – Complete notebook containing data preprocessing, modeling, and evaluation

---

## Notes
- This project was completed individually as part of a competitive machine learning challenge.
- The notebook is organized to allow easy understanding of the full ML workflow.
