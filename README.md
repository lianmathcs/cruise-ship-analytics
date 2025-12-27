# 🛳️ Cruise Ship Analytics

This project analyzes and visualizes real-world data of over 1,500 cruise ships from around the world. 
It includes feature engineering, data cleaning, and exploratory data analysis (EDA) using Python, Jupyter Notebook, 
and popular data science libraries like `pandas`, `seaborn`, and `scikit-learn`.

---

## 📊 Features

- Clean and preprocess raw cruise ship data
- Analyze trends in ship size, passenger capacity, age, and crew ratio
- Calculate service-level metrics like:
  - Crew-to-passenger ratio
  - Gross tonnage per passenger
- Explore space efficiency and service level across different ship types
- Visualize insights using matplotlib/seaborn
- Perform statistical testing and clustering  
---

## 📁 Project Structure
cruise-ship-analytics/
├── data/
│   ├── cruise_ships.csv                # Raw data
│   └── processed/
│       ├── cruise_ships_eda.csv        # Cleaned for visualization
│       └── cruise_ships_ml.csv         # Cleaned for ML tasks
├── notebooks/
│   ├── 01_data_cleaning.ipynb          # Data cleaning steps
│   ├── 02_data_EDA.ipynb               # Exploratory Data Analysis
│   ├── 03_data_EDA_nonnumeric.ipynb    # Exploratory Non-numeric Data Analysis
|   ├── 04_data_ML.ipynb                # Feature engineering + clustering
├── README.md
├── requirements.txt
└── .gitignore

---



