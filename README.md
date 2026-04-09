# Shark Attack Data Cleaning & Analysis

## Project Overview
This project focuses on cleaning and analyzing a real-world shark attack dataset.  
The goal was to transform messy data into a structured dataset and extract meaningful insights.

## Dataset
We used the GSAF shark incident dataset.

The dataset contained:
- missing values
- inconsistent formats
- messy text data

## Data Cleaning
- **Activity_final**  
Grouped free-text activities into categories (e.g. swimming, surfing, fishing, diving).

- **Type_final**  
Standardized into: unprovoked, provoked, other.

- **Species_final**  
Simplified inconsistent species names into broader groups (e.g. white shark, tiger shark, other, unknown).

- **Age_final**  
Converted to numeric values where possible; invalid entries set to missing.

- **Injury_final**  
Categorized into: injured, fatal, no injury, unknown, other.

- **Additional columns**  
(final_date, country, state, location, sex) were cleaned and standardized for geographic and demographic context.

## Project Structure
- cleaning_ludmilla.ipynb
- cleaning_jorge.ipynb
- final_dataset_build.ipynb
- eda.ipynb
- final_dataset.csv
- GSAF5.csv

## Tools
- Python
- Pandas
- Jupyter Notebook

## Conclusion
We transformed messy real-world data into a structured dataset ready for analysis and identified key patterns in shark incidents.