## <h1 align="center"> 📊 Life Expectancy and GDP</h1>

A Data Science Analysis Using World Health Organization Data

## 📌 Project Overview

This project examines the relationship between life expectancy at birth and GDP per capita using official data from the World Health Organization (WHO) and complementary economic indicators.
    
The objective is to understand how economic conditions relate to population health outcomes, identify nonlinearities and diminishing returns, and highlight cross-country disparities using a rigorous, reproducible data science workflow.

## 🎯 Objectives

* Analyze the relationship between GDP per capita and life expectancy

* Assess nonlinear and diminishing-return effects

* Compare outcomes across regions and income groups

* Produce policy-relevant visualizations and insights

* Maintain reproducibility using authoritative WHO data

## 🗂️ Data Sources

* Primary Source (Health Data):

    * *World Health Organization – Global Health Observatory (GHO)*

* Indicator: *Life expectancy at birth (years)*

* Economic Data Source:

    * *World Bank (GDP per capita, constant USD)*
      *(used only for economic comparison; health outcomes are WHO-sourced)*

* Variables Used

    * *country*

    * *year*

    * *Life expectancy at birth (years)*

    * *GDP*

## 🛠️ Tools & Technologies

* Python 3.14+

* Pandas – data processing

* NumPy – numerical analysis

* Matplotlib / Seaborn – visualization

* SciPy / Statsmodels – correlation & regression

* Jupyter Notebook – analysis environment

## 📈 Methodology

* Data Ingestion

* Load WHO life expectancy data

* Merge with GDP per capita indicators

* Data Cleaning

* Handle missing values

* Harmonize country names and years

* Remove implausible observations

* Exploratory Data Analysis

* Descriptive statistics

* Correlation analysis

* Log-transformed GDP modeling

* Visualization

* GDP vs life expectancy (linear & log scale)

* Temporal trends

* Regional comparisons

* Interpretation

* Diminishing marginal returns to GDP

* Outlier analysis

* Policy implications

## 📁 Project Structure
├── data/
│   ├── who_life_expectancy.csv
│   └── gdp_per_capita.csv
├── notebooks/
│   └── who_gdp_life_expectancy.ipynb
├── figures/
├── requirements.txt
└── README.md

## ▶️ How to Run
- pip install -r requirements.txt
- jupyter notebook

## 📜 Data Attribution

Life expectancy data © World Health Organization (WHO).
GDP data © World Bank.

Used under respective open data licenses.
