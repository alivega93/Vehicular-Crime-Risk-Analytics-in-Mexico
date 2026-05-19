# Vehicular Crime Risk Analytics in Mexico

End-to-end analytics project focused on vehicular crime analysis, risk classification and predictive modeling to support insurance pricing and risk management decisions.

## Business Problem

Which municipalities and states in Mexico present the highest vehicular crime risk, and how can this information support an insurance company in defining competitive and profitable pricing strategies?

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- SQL Server
- pyodbc
- Looker Studio
- Data Visualization
- Clustering (K-Means)
- Time Series Analysis

## Project Architecture

Open Data → SQL Server → Python Processing → Predictive Analytics → Interactive Dashboard

The project follows a complete analytics workflow including data acquisition, cleaning, transformation, predictive modeling, clustering and dashboarding. :contentReference[oaicite:4]{index=4}

## Methodology

### 1. Data Acquisition

Official open data from Mexico’s National Public Security System (SESNSP) was used to analyze vehicular crime incidence between 2015–2021. :contentReference[oaicite:5]{index=5}

### 2. SQL Database Design

SQL Server was used to store, organize and query municipal crime information through analytical tables and views. :contentReference[oaicite:6]{index=6}

### 3. Python Data Cleaning & Transformation

Python and Pandas were used to:

- validate data types
- review null values
- remove duplicates
- optimize formats
- prepare analytical datasets

### 4. Exploratory Data Analysis

EDA techniques were applied to analyze:

- state-level crime concentration
- municipal behavior
- temporal patterns
- geographic distribution
- top crime categories

### 5. Time Series Analysis

Time series visualization was used to evaluate historical trends in vehicular crime evolution. :contentReference[oaicite:7]{index=7}

### 6. Machine Learning — Prediction Model

Linear Regression was implemented to estimate vehicular crime levels for 2022 using historical behavioral trends. :contentReference[oaicite:8]{index=8}

### 7. Risk Classification — K-Means Clustering

K-Means clustering was used to classify Mexican states into risk groups:

- High Risk
- Medium Risk
- Low Risk

This segmentation supports insurance pricing strategies and territorial risk evaluation. :contentReference[oaicite:9]{index=9}

### 8. Interactive Dashboard

A Looker Studio dashboard was developed including:

- dynamic filters
- geographic maps
- crime evolution tracking
- comparative analysis
- decision-support visualization

## Key Insights

- Crime incidence varies significantly across Mexican states.
- Geographic segmentation improves territorial risk understanding.
- Historical patterns allow predictive estimation of future behavior.
- Clustering techniques support insurance pricing decisions.
- Interactive dashboards facilitate strategic monitoring and analysis. :contentReference[oaicite:10]{index=10}

## Author

Ali Vega

Data Analytics • Cloud Computing

## Repository Structure

```text
vehicular-crime-risk-analytics-mexico/
│
├── README.md
├── report/
├── notebooks/
├── datasets/
├── screenshots/
└── dashboard/
