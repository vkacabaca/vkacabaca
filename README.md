# Khanh Nguyen - Data Analyst portfolio
# About Me

Hi, I’m Khanh Nguyen! I’m a Data Analyst with a MSc in Business Analytics. My journey blends financial reasoning with strong technical skills in Python, SQL, and Power BI — and a passion for using data to solve real-world problems.

During my academic and industry projects, I’ve worked with large datasets, performed exploratory data analysis, built dashboards for stakeholders, and developed machine learning models to uncover patterns and drive decisions. I’m especially interested in applying analytics in areas like public impact, operational efficiency, and social good.

In my free time, I love exploring new tools, improving my analytics workflow, and continuously learning from real data challenges. Whether it’s transforming raw data or delivering actionable insights, I’m driven by curiosity and a strong sense of purpose.

This repository is where I showcase my projects, technical growth, and passion for all things data.
---
## Table of Contents
- [About]()
- [Portfolio Projects]()
  - Python
 - Power BI
 - Excel 
- [Education]()  
- [Certificates]()
- [Contact]()

## 📂 Portfolio Projects

### Customer Segmentation – FiftyEight Ltd (Industrial Placement)

**Goal:**  
To segment 75,000+ users of the Just Good Work app based on behavioural and demographic patterns to support ethical hiring strategies, regional marketing, and stakeholder decision-making.

**Code:** [`Customer_Segmentation_FiftyEight.ipynb`](https://github.com/vkacabaca/Customer_Segmentation_fiftyeight.ipynb/blob/main/demo%20trial.ipynb)]

**Description:**  
The dataset included user records from the Just Good Work app, supplemented by UK Home Office visa data. The project involved EDA, handling missing values, feature engineering, outlier detection, and dimensionality reduction using PCA. Three unsupervised machine learning models were implemented (K-Means, K-Modes, DBSCAN) to identify clusters of user profiles.

**Skills:**  
EDA, customer segmentation, dimensionality reduction, outlier detection, clustering, data visualization, stakeholder communication.

**Technology:**  
Python, Pandas, Numpy, Scikit-learn, Seaborn, Matplotlib, Power BI, SQL.

**Results:**  
Developed and presented an interactive Power BI dashboard showing 4 key user segments. Insights were used to tailor regional outreach strategies and improve app engagement among high-risk worker groups.

---

### Accident Severity Prediction – MSc Academic Project

**Goal:**  
To build a machine learning model that predicts traffic accident severity levels based on road and driver-related features.

**Code:** [`Accident_Severity_Prediction.ipynb`](https://github.com/vkacabaca/Predicting-Accident-Severity/blob/main/Predicting%20Accident%20Severity.ipynb)

**Description:**  
Used a dataset with over 32,000 UK accident records. The project included EDA, data cleaning, feature engineering, class imbalance handling, and multi-model ML training. Three classifiers (Logistic Regression, Random Forest, XGBoost) were trained, with hyperparameter tuning using GridSearchCV and RandomizedSearchCV.

**Skills:**  
Predictive modeling, classification, class imbalance handling (SMOTE, oversampling), model tuning, EDA, evaluation metrics.

**Technology:**  
Python, Pandas, Numpy, Scikit-learn, XGBoost, SMOTE, Matplotlib, Seaborn.

**Results:**  
Achieved an F1-score of 85% on minority class using tuned XGBoost model. Key insights identified road conditions and vehicle type as strong predictors of severity.

### PD Credit Scorecard – Credit Risk Modeling Project

**Goal:**  
To build a credit scorecard that estimates the **Probability of Default (PD)** of loan applicants to support credit risk assessment and lending decisions.

**Code:**  
[`PD_credit_scorecard.ipynb`](https://github.com/vkacabaca/PD--credit-scorecard-)

**Description:**  
Developed an end-to-end PD credit scorecard using historical borrower data. The project covered data cleaning, exploratory data analysis, variable binning, Weight of Evidence (WoE) encoding, and logistic regression modeling. The scorecard framework emphasizes interpretability and follows industry-standard credit risk modeling practices.

**Skills:**  
Credit risk modeling, probability of default (PD), logistic regression, feature binning, Weight of Evidence (WoE), exploratory data analysis, model evaluation.

**Technology:**  
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.

**Results:**  
Built an interpretable PD model capable of ranking borrowers by credit risk. The scorecard supports clear risk segmentation and provides a practical foundation for credit approval and portfolio risk monitoring.

### Solo Travel Safety Index – Data Analysis Project

**Goal:**  
Build a ranking of all 50 U.S. states and D.C. to identify the safest destinations for solo travelers using multi-factor data from 2023.

**Code:**  
([solo travel by state.xlsx](https://github.com/vkacabaca/US-Solo-Travel-Safety-Index/blob/main/solo%20travel%20by%20state.xlsx))

**Description:**  
Collected and merged state-level datasets to evaluate key solo-travel risk factors:
- Violent and property crime rates (FBI UCR)
- Road safety (fatal crash rate, DUI rate, total crashes – IIHS, NHTSA/BTS)
- Access to emergency services (hospitals, police per capita, EMS response time – KFF, WorldPopulationReview, PMC EMS study)
- Infrastructure quality (miles of public road, number of airports, accommodation affordability – BTS, WorldPopulationReview)
- Popularity of solo travel searches (Google Trends via Python PyTrends)

All metrics were converted to per-capita or percentage rates, normalized to a 0–100 scale using min-max scaling, and combined into a **Solo Safety Score** using weighted factors:
- Crime rate: **30%**
- Road safety: **20%**
- Emergency access: **20%**
- Infrastructure quality: **25%**
- Solo-travel search interest: **5%**

**Skills:**  
Data collection, cleaning, and normalization; per-capita calculations; weighted scoring and ranking; Excel PivotTables; Python automation (PyTrends).

**Technology:**  
Excel, Python, Pandas, NumPy.

**Results:**  
Generated a final Solo Safety Index with Top 10 safest and Top 10 riskiest states for solo travelers, revealing states with strong infrastructure, low crime, and efficient emergency services as the best options for 2023 travel.
## 🎓 Education

**Aston University (UK)**  
MSc in Business Analytics (2024 – 2025)

**University of London (UK)**  
BSc in Banking & Finance (2019 – 2023)
## Certifications

- Data Analyst in SQL – DataCamp

---

## Contact

- **Email:** vankhanhnguyen1611@gmail.com  
- **LinkedIn:** (https://www.linkedin.com/in/khanh-nguyen-717999157/) 
