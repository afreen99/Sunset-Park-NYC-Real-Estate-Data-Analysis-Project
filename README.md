# Sunset-Park-NYC-Real-Estate-Data-Analysis-Project
A data science and analytics project on Sunset Park (NYC) real estate data from 2003 to 2021 integrating R programming skills, exploratory data analysis, time series analysis, and clustering.
## 📋 Project Overview
This project explores the residential Sunset Park real estate data to:
- Visualize insights about property sale prices and sales volumes
- Interpret clustering analysis on property prices

## 📊 Dataset
The Sunset Park real estate data contains:
- 7008 rows
- 16 columns with attributes like building class, description, zip_code, number of residential and commercial units, year built, gross sqft and sale price

## 🤖 K Means Clustering Insights
Running K Means clustering algorithm on sales price, gross sqft, price per sqft and property age (engineered from property's year built) revealed that Sunset Park’s residential market is dominated by older, modestly priced buildings, with smaller but meaningful segments of premium small properties and newer high-PPSF homes, alongside a niche of low-value distressed stock. 

## 🚀 Getting Started
### Prerequisites
- R 4.5.2 or higher
- RStudio

### Installation

1. Clone the repository:
```git clone https://github.com/afreen99/Smart-Home-IoT-Analytics-Project.git```

3. Install required packages:
```pip install -r requirements.txt```

4. Launch Jupyter Notebook:
```jupyter notebook Code/AD599_Smart_Home_IoT_project.ipynb```

### Running the Analysis
1. Open ```AD599_Smart_Home_IoT_project.ipynb``` in Jupyter
2. Ensure ```smart_home.db``` is in the Data folder (or update the DB_PATH variable)
3. Run all cells sequentially (Cell → Run All)

The notebook will:

- Connect to the database
- Perform SQL-based feature engineering
- Train and evaluate ML models
- Generate Plotly dashboard
