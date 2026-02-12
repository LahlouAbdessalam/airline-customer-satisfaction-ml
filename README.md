# Airline Passenger Satisfaction — EDA + Logistic Regression

Goal: understand what drives airline passenger satisfaction and predict **satisfied vs not satisfied**.

## What I did
- Cleaned the data (fixed CSV import issue, handled missing values, removed ID column)
- Ran EDA to compare satisfaction across segments (travel type, class, loyalty)
- Built an interpretable baseline model with a **scikit-learn Pipeline**
  - imputation + scaling + one-hot encoding
  - **Logistic Regression**
- Evaluated performance (accuracy ~0.87, AUC ~0.93) and interpreted coefficients

## Key drivers (high level)
- Strong positives: **Business travel**, **Loyal customer**, good **online boarding / wifi / onboard service** scores  
- Strong negatives: **Personal travel**, **Disloyal customer**, **Economy class**, **arrival delays**

## Files
- `Rush3.ipynb` — notebook (EDA + model)
- `Rapport RUSH3-data.pdf` — report

## Run
Install basics: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, then open the notebook.
