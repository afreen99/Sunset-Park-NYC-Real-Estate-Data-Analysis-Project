# Sunset-Park-NYC-Real-Estate-Data-Analysis-Project
A data science and analytics project on Sunset Park (NYC) real estate data from 2003 to 2021 integrating R programming skills, exploratory data analysis, time series analysis, and clustering.
## 📋 Project Overview
This project explores the Sunset Park residential real estate data to:
- Visualize insights about property sale prices and sales volumes
- Interpret clustering analysis on property prices

## 📊 Dataset
The Sunset Park real estate data (```sunset_park.csv```) contains:
- 13050 rows
- 16 columns with attributes like building class, description, zip_code, number of residential and commercial units, year built, gross sqft and sale price

## 🤖 K Means Clustering Insights
Running K Means clustering algorithm on sales price, gross sqft, price per sqft and property age (engineered from property's year built) revealed that Sunset Park’s residential market is dominated by older, modestly priced buildings, with smaller but meaningful segments of premium small properties and newer high-PPSF homes, alongside a niche of low-value distressed stock. 

## 🚀 Getting Started
### Prerequisites
- R 4.5.2 or higher
- RStudio

### Installation
1. Clone the repository: ```git clone https://github.com/afreen99/Sunset-Park-NYC-Real-Estate-Data-Analysis-Project.git```

2. Install required R packages: The list of required R packages is provided in ```requirements.txt```
   - Open RStudio and run the following in the R console:
   ```
   packages <- c( "tidyverse", "dplyr", "skimr", "inspectdf", "factoextra")

   install.packages(setdiff(packages, rownames(installed.packages())))
   ```

3. Open and run the analysis
     1. Open the project folder in RStudio
     2. Open the main R Markdown file ```Sunset_Park_Data_Analysis_Project.Rmd```
     3. Run all code chunks interactively
