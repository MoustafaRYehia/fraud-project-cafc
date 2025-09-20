{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Fraud Analysis \'96 Canadian Anti-Fraud Centre (2021\'962025)\
\
This project explores ~329k fraud and cybercrime reports from the Canadian Anti-Fraud Centre (CAFC).\
\
## Contents\
- `Canadian_CAFC_Fraud_Analysis.ipynb`  \
  Jupyter notebook with data cleaning, imputation, exploratory analysis, and clustering.  \
\
- `MYehia_FraudAnalysis_Business_Insights.pdf`  \
  Combined project summary with technical analysis and stakeholder-facing EDA insights.  \
\
## Data\
Source: Government of Canada Open Data Portal  \
- Dataset: https://open.canada.ca/data/en/dataset/6a09c998-cddb-4a22-beff-4dca67ab892f  \
- Metadata / definitions: https://open.canada.ca/data/en/dataset/6a09c998-cddb-4a22-beff-4dca67ab892f/resource/ec49223e-d746-4171-a97b-12fcc79d360f  \
\
*Note: Data file not included in this repo due to size. Update the notebook\'92s `pd.read_csv("fraud_data.csv")` path to your local copy.*  \
\
## Tools\
- Python: pandas, numpy, scikit-learn, matplotlib, seaborn, plotly  \
- Methods: EDA, missingness tests, imputation, clustering (KMeans, HDBSCAN, PCA, UMAP)  \
\
## Key Insights\
- Investments and Romance scams caused the largest combined losses (> C$1.4B).  \
- Seniors aged 60\'9669 are most affected in Romance scams, especially women.  \
- High per-capita exposure in Quebec and Manitoba.  \
- Major fraud channels: Internet, social media, email, direct call.\
}