# ai-in-sustainable-agriculture

This project is part of a data science pipeline to explore, clean, and prepare an agricultural dataset for further analysis or machine learning modeling. The dataset contains information about soil properties, weather, crop types, input usage, crop yield, and sustainability scores from 10,000 farms.

📁 Dataset Overview

The dataset used is named: farmer_advisor_dataset.csv

Features:
Column Name	Description
Farm_ID	Unique identifier for each farm
Soil_pH	Soil pH level
Soil_Moisture	Moisture content in soil (%)
Temperature_C	Temperature in Celsius
Rainfall_mm	Rainfall received (mm)
Crop_Type	Type of crop grown (e.g., Wheat, Corn, Soybean, etc.)
Fertilizer_Usage_kg	Fertilizer used (kg)
Pesticide_Usage_kg	Pesticide used (kg)
Crop_Yield_ton	Crop yield in tons
Sustainability_Score	Score indicating sustainability (0-100)
🔍 Project Workflow
1. Data Loading & Exploration

Loaded the dataset using pandas.

Displayed basic structure with .head(), .info(), and .describe().

2. Data Quality Checks

Verified no missing values.

Checked and found no duplicate rows.

Assessed data types (mostly numerical, one categorical).

3. Statistical Summary

Computed statistical summary for both numerical and categorical features.

Found 4 unique crop types, with Soybean being the most frequent.

4. Data Preprocessing

Encoded categorical variables using one-hot encoding (get_dummies()).

Verified that no outliers exist in the Sustainability_Score using IQR method.

📈 Insights Prepared For

Although this notebook is focused on data cleaning, it lays the groundwork for:

Predictive modeling (e.g., crop yield or sustainability score prediction).

Feature importance analysis.

Sustainability optimization strategies.

🛠️ Tools & Libraries

Python 3.11

pandas

numpy

seaborn

matplotlib

📦 File Structure
project/
│
├── farmer_advisor_dataset.csv      # Input dataset
├── data_processing_notebook.ipynb  # This Jupyter Notebook
└── README.md                       # Project documentation

📌 Future Enhancements

Build ML models for predicting crop yield or sustainability.

Add visualizations for better EDA (e.g., correlation heatmaps, boxplots).

Develop a web-based advisor interface for farmers.

🤝 Contributing

Pull requests and feedback are welcome! Please open an issue first to discuss any major changes.
