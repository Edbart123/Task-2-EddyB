# Data Cleaning & Exploratory Data Analysis — DecodeLabs Week 2

## Overview
Performed end-to-end data cleaning and exploratory data analysis (EDA) on a 
structured dataset using Python and Pandas. The project simulates the first 
phase of any real-world data analytics workflow — assessing data quality, 
resolving issues, and preparing a clean dataset ready for analysis or modeling.

**Tools:** Python · Pandas · NumPy · Jupyter Notebook

---

## Business Questions Explored
- What does the dataset structure look like and are the data types correct?
- Where are the missing values and how should they be handled?
- What does the distribution of key fields look like?
- Is the dataset clean and ready for downstream analysis?

---

## What I Did

### 1. Data Loading & Inspection
Loaded the dataset into a Pandas DataFrame and performed an initial inspection
to understand its structure, column types, and overall shape.

```python
df = pd.read_csv('Week2_Part1_Data_Cleaning.ipynb')
df.head()
df.info()
df.describe()
```

### 2. Missing Value Analysis
Identified columns with null values and quantified the extent of missing data
across the dataset to determine the appropriate cleaning strategy.

![Missing Values Analysis](df_isnull.png)

### 3. Data Type Validation
Reviewed and corrected column data types to ensure numeric, categorical, and 
date fields were properly formatted for analysis.

### 4. Data Cleaning
Applied cleaning techniques to handle missing values, remove duplicates, and 
standardize fields — producing a clean, analysis-ready dataset.

### 5. Dataset Preview
Validated the cleaned dataset structure before exporting for downstream use.

![Dataset Preview](df_labeling.png)

---

## Key Skills Demonstrated
- Data loading and inspection with Pandas
- Missing value detection and handling
- Data type validation and correction
- Exploratory data analysis (EDA)
- Data cleaning and preprocessing
- Jupyter Notebook workflow management

---

## Project Files
| File | Description |
|------|-------------|
| `Week2_Part1_Data_Cleaning.ipynb` | Main Jupyter Notebook with full workflow |
| `df_isnull.png` | Missing values analysis output |
| `df_labeling.png` | Cleaned dataset preview |

---

## Results
Successfully assessed and cleaned the dataset, resolving missing values and 
data type inconsistencies. The cleaned dataset was validated and prepared for 
downstream exploratory analysis and visualization.

---

## Author
**Eddy Bartolome**  
Data Analyst | Python · SQL · Power BI · Excel  
[LinkedIn](https://www.linkedin.com/in/eddybartolome) · 
[GitHub](https://github.com/Edbart123)
