# Fraud Analysis – Canadian Anti-Fraud Centre (2021–2025)

This project explores ~329k fraud and cybercrime reports from the Canadian Anti-Fraud Centre (CAFC). The work includes exploratory data analysis, cleaning and imputation of missing values, descriptive statistics, segmentation of fraud patterns, and clustering using machine learning methods. The summary below only highlights key findings, while much deeper insights from exploratory analysis, clustering visualizations, and statistical testing are available in the complete notebook.


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

## Approach
**Dataset:** Canadian Anti-Fraud Centre (CAFC), ~329k reports (2021–2025)  
**Goal:** Provide a stakeholder-friendly exploratory analysis of fraud and cybercrime reports, answering key descriptive questions with clear statistics and tables.

---

## Data Insights
- Investments and Romance scams caused the largest combined losses (> C$1.4B).  
- Seniors aged 60–69 are most affected in Romance scams, especially women.  
- High per-capita exposure in Quebec and Manitoba.  
- Major fraud channels: Internet, social media, email, direct call.  

---

## Important Questions Answered

**What are the most common fraud types?**  
- Identity Fraud (23% of reports), Extortion (9.6%), Phishing (8.7%).  

**Which scams cause the largest losses?**  
- Investments (C$1.18B), Romance (C$256M), Spear Phishing (C$246M).  
- Highest average loss per case: Investments, Spear Phishing, Timeshare.  

**Who is most affected?**  
- Romance scams peak in ages 60–69, especially for women (C$130M vs men C$69M).  
- Complaint type split shows meaningful differences across fraud themes (χ² test p < 0.00001).  

**How do fraudsters reach victims?**  
- Major channels by loss: Internet-Social (C$717M), Internet (C$596M), Email (C$305M), Direct Call (C$252M).  
- Door-to-door is rare but has the highest average loss per case (~C$51k).  

**Where are the geographic hot spots?**  
- Ontario leads in both reports (96k) and total losses (C$871M).  
- British Columbia and Alberta also high in losses; Quebec ranks 2nd in report volume (67k).  
- Adjusted for population, Quebec and Manitoba show high per-capita exposure.  
