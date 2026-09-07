# Telco Customer Churn — Data Mining Project

**Course:** IT326 – Data Mining, King Saud University
**Students:** Lujain Aldujain *(add remaining team members here)*

## Project Description

This project applies data mining techniques to the **Telco Customer Churn** dataset to solve two tasks:

- **Classification** — predict whether a customer will churn (leave the telecom provider) based on their account, service, and billing attributes.
- **Clustering** — group customers into segments with similar characteristics and usage patterns.

## Motivation

Customer churn is one of the most costly problems telecom companies face: acquiring a new customer costs significantly more than retaining an existing one. Being able to predict which customers are likely to churn — and understanding what distinguishes them — lets a company act proactively (e.g., targeted offers) instead of losing revenue reactively. This dataset was chosen because it is a realistic, well-studied business problem with a clear class label (`Churn`), a manageable size for classroom use, and an existing body of published research to compare against.

## Dataset

Located in [`Dataset/`](Dataset/):

- **`Raw_dataset.csv`** — the original, unmodified Telco Customer Churn dataset (IBM sample dataset, widely hosted on Kaggle: [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)).
  - 7,043 customer records, 21 attributes.
  - Class label: `Churn` — `No` (5,174 customers) / `Yes` (1,869 customers).
- **`Ahmad_et_al_2019_Customer_Churn_Prediction_Telecom_BigData.pdf`** — supporting research paper: Ahmad, A.K., Jafar, A. & Aljoumaa, K. "Customer churn prediction in telecom using machine learning in big data platform." *J Big Data* 6, 28 (2019). https://doi.org/10.1186/s40537-019-0191-6 — addresses the same problem (telecom churn prediction) using classification techniques, achieving an AUC of 93.3% with XGBoost.

## Repository Structure

```
data-mining-project/
├── Dataset/
│   ├── Raw_dataset.csv
│   └── Ahmad_et_al_2019_Customer_Churn_Prediction_Telecom_BigData.pdf
├── Phase1.ipynb
├── .gitignore
└── README.md
```

Notebooks for later phases (`Phase2.ipynb`, `Phase3.ipynb`) and `Preprocessed_dataset.csv` will be added as the project progresses.
