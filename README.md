# 🌾 Crop Yield Prediction

This project focuses on building a **Predictive Analytics Pipeline** to estimate agricultural crop yields (hg/ha) across the globe. Using a dataset covering over 100 countries and 20 years of data, the model analyzes the impact of environmental variables—such as annual rainfall and average temperature—alongside human interventions like pesticide usage.

## 🚀 Project Workflow

* **Data Loading & Inspection:** Import datasets, check for missing values, remove duplicates, and clean unnecessary columns to ensure data quality.  
* **Exploratory Data Analysis (EDA):** Visualize relationships between rainfall, temperature, and yield; analyze distribution of crop types across regions; generate correlation heatmaps.  
* **Feature Engineering:** Apply OneHotEncoder to categorical features (Area, Crop Type) and StandardScaler to numerical features (Year, Rainfall, Pesticides, Temperature) using ColumnTransformer for a clean pipeline.  
* **Model Training:** Train and benchmark multiple algorithms (Linear, Lasso, Ridge, Decision Tree Regressor) to find the best model for non-linear agricultural data.  
* **Prediction System:** Input parameters (e.g., Maize in Albania) to get a crop yield forecast.  

## 📊 Evaluation Metrics

* **Mean Absolute Error (MAE):** Measures average error in yield units (hg/ha) — easy for stakeholders and farmers to interpret.  
* **R² Score:** Measures how much variance in crop yield is explained by environmental features.  

### Model Results

* Linear / Lasso / Ridge: R² ≈ 0.74  
* Decision Tree Regressor: R² ≈ 0.97 with significantly lower MAE (~4,132 hg/ha)

## 🛠️ Tech Stack

* **Python**
* **Pandas & NumPy** (Data Manipulation)  
* **Matplotlib & Seaborn** (Visualization)  
* **Scikit-Learn** (Modeling & Preprocessing)  


