# **Financial Data Preprocessing Pipeline**

This repository contains a comprehensive pipeline to preprocess financial datasets for predictive analytics. The project is implemented in a Jupyter Notebook and includes steps such as data cleaning, transformation, discretization, and integration to create a machine learning-ready dataset.  

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
├── 📄 Financial_Data_Preprocessing.ipynb
├── 📄 final_preprocessed_data.csv
└── 📄 README.md

Contents
dataset/: Contains the raw financial data in .csv format:

Annual_P_L_1_final.csv: Annual Profit & Loss data.
Balance_Sheet_final.csv: Balance sheet data.
cash_flow_statments_final.csv: Cash flow statement data.
other_metrics_final.csv: Key financial metrics data.
ratios_1_final.csv: Financial ratios data.

Financial_Data_Preprocessing.ipynb: Jupyter Notebook containing the complete preprocessing pipeline:
Data ingestion and validation.
Handling missing values and duplicates.
Data discretization using KMeans clustering.
Ensuring consistent data types and ranges.
Combining datasets into a single file.
final_preprocessed_data.csv: The final output file containing the preprocessed and combined data, ready for machine learning or further analysis.

Getting Started
Prerequisites
Make sure you have Python 3.7+ installed along with the following libraries:

pandas
numpy
scikit-learn
jupyter


Running the Notebook

1. Clone the repository:

git clone https://github.com/your-repository-link.git
cd Financial-Data-Preprocessing

2. Launch the Jupyter Notebook:

jupyter notebook Financial_Data_Preprocessing.ipynb

3. Execute all cells sequentially to preprocess the data and generate the final_preprocessed_data.csv.

Usage
Raw Datasets: Place the raw .csv files in the dataset/ folder.
Final Dataset: Use the final_preprocessed_data.csv file for further analysis or as input to machine learning models.
