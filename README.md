# Vehicular Crime Risk Analytics in Mexico

End-to-end analytics project focused on vehicular crime analysis, risk classification and predictive modeling to support insurance pricing and territorial risk management decisions.

---

## Business Problem

Which municipalities and states in Mexico present the highest vehicular crime risk, and how can this information support insurance companies in defining competitive, data-driven and profitable pricing strategies?

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- SQL Server
- pyodbc
- Looker Studio
- Data Visualization
- K-Means Clustering
- Time Series Analysis

---

## Project Architecture

Open Data → SQL Server → Python Processing → Predictive Modeling → Risk Classification → Interactive Dashboard

The project follows a complete analytics workflow including data acquisition, cleaning, transformation, exploratory analysis, predictive modeling, clustering and business dashboarding.

---

## Methodology

### 1. Data Acquisition

Official open data from Mexico’s National Public Security System (*SESNSP) was used to analyze vehicular crime incidence between **2015–2021*.

### 2. SQL Database Design

SQL Server was used to:

- store municipal crime records
- organize analytical datasets
- create tables and analytical views
- support downstream querying and reporting

### 3. Python Data Cleaning & Transformation

Python and Pandas were used to:

- validate data types
- handle null values
- remove duplicates
- optimize data formats
- prepare analytical datasets

### 4. Exploratory Data Analysis (EDA)

EDA techniques were applied to analyze:

- state-level crime concentration
- municipal behavior
- temporal patterns
- geographic distribution
- top crime categories

### 5. Time Series Analysis

Time series analysis was performed to evaluate:

- historical crime evolution
- temporal behavior
- trend identification across years

### 6. Machine Learning — Prediction Model

A *Linear Regression* model was implemented to estimate vehicular crime levels for *2022* using historical behavioral trends.

### 7. Risk Classification — K-Means Clustering

K-Means clustering was used to classify Mexican states into risk groups:

- High Risk
- Medium Risk
- Low Risk

This segmentation supports insurance pricing strategies and territorial risk evaluation.

### 8. Interactive Dashboard

A Looker Studio dashboard was developed including:

- dynamic filters
- geographic maps
- crime evolution tracking
- comparative analysis
- decision-support visualization

---

## Key Insights

- Crime incidence varies significantly across Mexican states.
- Geographic segmentation improves territorial risk understanding.
- Historical patterns enable predictive estimation of future behavior.
- Clustering techniques support insurance pricing strategies.
- Interactive dashboards facilitate strategic monitoring and analytical decision-making.

---

## Author

*Ali Vega*  
Data Analytics • Cloud Computing

---

## Repository Structure

```text
vehicular-crime-risk-analytics-mexico
├── README.md
└── report
    └── Vehicular Crime Risk Analytics in Mexico.pdf
```
