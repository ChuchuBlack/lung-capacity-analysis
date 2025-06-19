# Lung Capacity Analysis (SQL Project)

This project explores the lung capacity of children and teenagers (ages 3–19) using SQL.

The main goal was to clean the data** and perform exploratory data analysis to understand what factor affect lung capacity.



## Files Included

- `lungcapdata.csv` – Original dataset
- `lung_capacity_cleaning_and_eda.sql`
- `lungcapdata_cleaned.csv`
- `README.md` – Project summary



## Steps Performed

### 1. Data Cleaning
- Removed unnecessary column
- Added auto-incrementing primary key (`ID`)
- Removed duplicate records
- Deleted rows with null values
- Standardized values

### 2. Exploratory Data Analysis (EDA)
- Average lung capacity by smoking status
- Comparison by gender
- Grouped analysis by age ranges


## Key Findings

- Children who smoke tend to have lower lung capacity
- Older and taller children typically have higher lung capacity
- No major differences based on gender or caesarean status in this sample



## Tools Used

- MySQL for all data cleaning and analysis
