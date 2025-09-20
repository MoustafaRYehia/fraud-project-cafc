# Fraud Analysis – Canadian Anti-Fraud Centre (2021–2025)

This project explores ~329k fraud and cybercrime reports from the Canadian Anti-Fraud Centre (CAFC).

## Contents
- `Canadian_CAFC_Fraud_Analysis.ipynb`  
  Jupyter notebook with data cleaning, imputation, exploratory analysis, and clustering.  

- `MYehia_FraudAnalysis_Business_Insights.pdf`  
  Combined project summary with technical analysis and stakeholder-facing EDA insights.  

## Data
Source: Government of Canada Open Data Portal  
- Dataset: https://open.canada.ca/data/en/dataset/6a09c998-cddb-4a22-beff-4dca67ab892f  
- Metadata / definitions: https://open.canada.ca/data/en/dataset/6a09c998-cddb-4a22-beff-4dca67ab892f/resource/ec49223e-d746-4171-a97b-12fcc79d360f  

*Note: Data file not included in this repo due to size. Update the notebook’s `pd.read_csv("fraud_data.csv")` path to your local copy.*  

## Tools
- Python: pandas, numpy, scikit-learn, matplotlib, seaborn, plotly  
- Methods: EDA, missingness tests, imputation, clustering (KMeans, HDBSCAN, PCA, UMAP)  

## Key Insights
- Investments and Romance scams caused the largest combined losses (> C$1.4B).  
- Seniors aged 60–69 are most affected in Romance scams, especially women.  
- High per-capita exposure in Quebec and Manitoba.  
- Major fraud channels: Internet, social media, email, direct call.
