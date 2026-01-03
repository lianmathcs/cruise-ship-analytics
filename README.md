## 🛳️ Cruise Ship Operations Analytics & Staffing Modeling

* The analysis is informed by first-hand industry experience as a former cruise ship crew ( **Royal Caribbean, Celebrity Cruises, and Viking cruise fleets**) , providing practical context for staffing, service-level expectations, and operational constraints
 
* This project is an End-to-end data analysis and machine learning project analyzing ~1,500 global cruise ships to uncover operational patterns, efficiency differences, and structural drivers of crew requirements.
* It goes beyond exploratory data analysis to validate operational hypotheses and model real-world staffing behavior in the cruise industry.

* It also combines data scraping, feature engineering, statistical testing, clustering, and regression to extract actionable insights from heterogeneous maritime data

 
Built with **Python, Pandas, and scikit-learn** etc.. 

--- 
##  Objective

The objective of this project is to move beyond exploratory data analysis and validate structural patterns and operational relationships in global cruise ship data using statistical testing and machine learning.

Specifically, the project focuses on:
- Evaluating staffing and space-efficiency differences across ship types
- Identifying latent vessel archetypes through unsupervised clustering
- Modeling the relationship between ship design attributes and total crew requirements

--- 
##  Project Structure

    cruise-ship-analytics/
    ├── data/
    │   ├── cruise_ships.csv
    │   ├── cruise_ships_eda.csv
    │   ├── cruise_ships_enriched_ml_ready.csv   
    │   ├── cruise_ships_ml.csv
    |
    ├── notebooks/
    │   ├── 01_data_cleaning.ipynb
    │   ├── 02_data_EDA.ipynb
    │   ├── 03_data_EDA_nonnumeric.ipynb
    │   └── 04_data_ML.ipynb
    ├── README.md
    ├── requirements.txt
    └── .gitignore

---
##  Methods

- **Data Collection:** Python-based web scraping of real-time public cruise ship listings (~1,500 vessels)
- **Data Cleaning & Feature Engineering:** Normalization of ship characteristics and construction of efficiency metrics
- **Statistical Analysis:** Non-parametric tests (e.g., Spearman correlation, Kruskal–Wallis) to validate operational differences
- **Machine Learning:**
  - K-Means clustering to identify latent vessel archetypes
  - Linear regression to model crew requirements based on ship design and capacity

---
##  Key Findings

- Staffing and space-efficiency metrics differ significantly across ship types (ferry, cruise, river cruise, icebreaker), reflecting distinct operational models.
- Clustering analysis reveals multiple vessel archetypes that are not explicitly defined by ship type alone.
- Ship design and capacity features explain a substantial portion of the variance in total crew size, indicating strong structural relationships between vessel scale and staffing requirements.

---
##  Notebook Guide

- `01_data_cleaning.ipynb` — Raw data cleaning and normalization
- `02_data_EDA.ipynb` — Exploratory analysis of numeric features
- `03_data_EDA_nonnumeric.ipynb` — Analysis of categorical and textual features
- `04_data_ML.ipynb` — Statistical testing, clustering, and regression modeling

