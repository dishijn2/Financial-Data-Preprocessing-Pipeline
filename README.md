# **Financial Data Preprocessing Pipeline**

This repository contains a comprehensive pipeline to preprocess financial datasets for predictive analytics. The project is implemented in a Jupyter Notebook and includes steps such as data cleaning, transformation, discretization, and integration to create a machine-learning-ready dataset.  

---

## **Repository Structure**

```plaintext
📂 Financial-Data-Preprocessing-pipeline
├── 📂 dataset
│   ├── Annual_P_L_1_final.csv
│   ├── Balance_Sheet_final.csv
│   ├── cash_flow_statments_final.csv
│   ├── other_metrics_final.csv
│   ├── ratios_1_final.csv
├── 📄 ETL pipeline.ipynb
├── 📄 preprocessed_financial_data_M.xls
└── 📄 README.md
```

## Contents

### `dataset/`
Contains the raw financial data in `.csv` format:
- **`Annual_P_L_1_final.csv`**: Annual Profit & Loss data.
- **`Balance_Sheet_final.csv`**: Balance sheet data.
- **`cash_flow_statments_final.csv`**: Cash flow statement data.
- **`other_metrics_final.csv`**: Key financial metrics data.
- **`ratios_1_final.csv`**: Financial ratios data.

### `ETL_pipeline.ipynb`
Jupyter Notebook containing the complete preprocessing pipeline:
- **Data Load and validation**: Loading and verifying the datasets. Creating data frames for CSV files.
- **Handling missing values and duplicates**: Cleaning the data. 
- **Data discretization using KMeans clustering**: Converting numeric columns into discrete bins.
- **Ensuring consistent data types and ranges**: Validating and formatting data for uniformity.
- **Combining datasets into a single file**: Merging all datasets into one comprehensive file.

### `preprocessed_financial_data_M.xls`
The final output file contains the preprocessed and combined data.


