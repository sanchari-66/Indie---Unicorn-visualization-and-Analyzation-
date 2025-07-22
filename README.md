# Indi – Unicorn Startup 2023 Datasets

A data analysis and predictive modeling project on Indian unicorn startups (2023) aimed at uncovering factors that drive success, funding patterns, and valuation growth.

## Overview
The project focuses on analyzing a dataset of Indian unicorn startups, performing exploratory data analysis (EDA), and building predictive models to forecast valuation and growth. Insights help understand sector-wise performance, investor patterns, and funding strategies.

## Features
- Data cleaning and preprocessing to handle missing values, outliers, and formatting issues.
- Exploratory Data Analysis (EDA) for uncovering trends and patterns.
- Sector-wise and valuation distribution visualizations using **ggplot2**.
- Feature engineering to capture growth potential and investor impact.
- Training and comparing multiple machine learning models, including **Random Forest (ranger)**.
- Evaluation of model performance using **Mean Absolute Error (MAE)**.
- Selection and fine-tuning of top 3–4 best-performing models.
- Export of final model in **PMML format** using **r2pmml** for deployment.
- Insights into funding patterns, dominant sectors, and growth indicators.

## Tech Stack
- **Language:** R  
- **Libraries:** `metrics`, `ranger`, `dplyr`, `caret`, `ggplot2`, `r2pmml`

## Project Structure
```
Indi-Unicorn-2023/
│
├── data/ # Raw and cleaned datasets
├── scripts/ # R scripts for cleaning, EDA, and modeling
├── results/ # Visualizations, reports, and model outputs
└── README.md # Project documentation

```

## Key Insights
- Identified top-performing sectors in Indian unicorn space.
- Found patterns in funding rounds and investor participation.
- Built a model capable of predicting startup valuations with minimized MAE.

## Future Work
- Enhance the dataset with real-time funding updates.
- Implement a web-based dashboard for visualization and prediction.
- Explore deep learning models for improved forecasting.

## Author
**Sanchari Thakur**

