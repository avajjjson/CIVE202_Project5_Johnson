Project Objectives
Load and verify a merged dataset of TCR violations from five states

Clean and standardize key variables

Classify systems as Small or Large based on population served

Create summary tables for:
Violations by state
Violations by system size
Violations by year

Produce two required visualizations:
Violations by state over time
Total violations by state and by system size

Required Python Packages
Your notebook uses the following libraries:
pandas — data loading and cleaning
requests — satisfies the “third package not used in class” requirement
matplotlib — graphing
seaborn — improved visual styling

All packages are included in standard Anaconda installations.

How to Run the Code

Download the repository or clone it using:
git clone https://github.com/avajjjson/CIVE202_Project5_Johnson

Open the Jupyter notebook:
CIVE202_Code5Johnson.ipynb

Ensure the dataset file:
CIVE202_ViolationReportData.csv
is in the same directory as the notebook.

Run all cells in order.

Summary of Methods

1. Data Loading & Cleaning
The merged dataset is loaded into pandas.
Missing values are checked.
Population values are cleaned and converted to numeric.
The year is extracted from the submission_year_quarter column.

2. System Size Classification
A custom function labels systems as:
Small (≤ 10,000 population served)
Large (> 10,000 population served)

4. Summary Tables
The notebook generates:
Violations by state
Violations by system size
Violations by year

4. Visualizations
The notebook produces:
Line plot: Violations by state over time
Bar chart: Total violations by state
Bar chart: Violations by system size

📈 Key Results
States show clear differences in total TCR violations.
Small systems consistently have more violations than large systems.
Only one quarter of data (2026Q1) is available, limiting long‑term trend analysis.
