# FUTURE_ML_01 — Machine Learning Internship Tasks
**Future Interns | Machine Learning Internship 2026**

**Intern:** Akalya A  
**CIN:** FIT/MAR26/ML6268  
**Duration:** 13 March 2026 – 13 April 2026

---

## Tasks Overview

### Task 1 — Sales & Demand Forecasting
**Folder:** `Task1_Sales_Forecasting/`

Built a sales forecasting system using historical business data to predict future sales and help businesses plan inventory and resources.

- Data cleaning and time-based feature engineering
- Models: Linear Regression & Random Forest Regressor
- Evaluation: MAE, RMSE, R² Score
- Business-friendly visualizations and recommendations
- **Dataset:** Superstore Sales Dataset (Kaggle)

---

### Task 2 — Support Ticket Classification & Prioritization
**Folder:** `Task2_Ticket_Classification/`

Built an NLP-based system that automatically classifies customer support tickets into categories and assigns priority levels to help support teams respond faster.

- Text preprocessing: lemmatization, stopword removal (NLTK)
- Feature extraction: TF-IDF vectorization
- Models: Logistic Regression (category + priority classifiers)
- Evaluation: Accuracy, Precision, Recall, F1, Confusion Matrix
- **Dataset:** Customer Support Ticket Dataset (Kaggle)

---

### Task 3 — Resume / Candidate Screening System
**Folder:** `Task3_Resume_Screening/`

Built an ML resume screening system that scores and ranks candidates based on job description match, extracts skills, and identifies skill gaps.

- NLP text preprocessing and skill extraction
- TF-IDF cosine similarity scoring
- Weighted final score = 60% text similarity + 40% skill coverage
- Candidate ranking with skill gap analysis
- **Dataset:** Resume Dataset (Kaggle)

---

## Tech Stack
- Python 3.10
- pandas, numpy
- scikit-learn
- NLTK
- matplotlib, seaborn
- Jupyter Notebook

## How to Run
```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn jupyter
jupyter notebook
```
Open each task folder and run the `.ipynb` notebook.

---

*This repository was created as part of the Future Interns ML Internship Program 2026.*
