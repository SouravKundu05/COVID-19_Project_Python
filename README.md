# COVID-19 Data Analysis Project
Overview

This project analyzes the global COVID-19 pandemic using real-world datasets on confirmed cases, recoveries, and deaths. The goal is to demonstrate practical Python data analysis skills, generate insights into the pandemic’s progression, and visualize trends for countries and regions worldwide.

The analysis includes:

Daily and monthly trends of confirmed, recovered, and death cases

Country-wise comparisons

Recovery and death rate analysis

Time-series data transformations and visualizations

Datasets

Three main datasets are used (from the Johns Hopkins University COVID-19 repository
):

Confirmed Cases: Cumulative confirmed COVID-19 cases per country/province by date

Deaths: Cumulative deaths attributed to COVID-19 by country/province by date

Recovered Cases: Cumulative recovered cases by country/province by date

Each dataset contains the following columns:

Province/State

Country/Region

Lat and Long (geographic coordinates)

Date columns (daily cumulative counts)

Project Objectives

Data Loading & Cleaning: Load CSV files using Pandas, handle missing values, and standardize date formats.

Exploratory Data Analysis (EDA):

Analyze global and country-specific trends

Identify peak daily cases, recovery rates, and death rates

Compare metrics between countries (e.g., Germany, France, Italy, Canada, Australia, South Africa, US)

Data Transformation: Convert wide-format datasets into long format for time-series analysis.

Merged Dataset Analysis: Combine confirmed, recovered, and death datasets to create a comprehensive view of the pandemic.

Monthly Aggregation: Summarize monthly confirmed, recovered, and death cases to observe progression.

Visualizations:

Line charts for trends over time

Bar charts for country comparisons

Highlighting peak cases and recovery/death ratios

Key Insights

Peak Daily Cases: Identified peak surge days for Germany, France, and Italy.

Recovery Rates: Compared recovery efficiency between Canada and Australia.

Death Rates: Determined provinces with highest and lowest death rates in Canada.

Top Impacted Countries: Highlighted countries with highest average death rates in 2020.

South Africa: Compared recoveries vs deaths to evaluate outcomes.

United States: Analyzed monthly recovery ratios from March 2020 to May 2021.

Libraries Used

pandas – Data loading, cleaning, and analysis

numpy – Numerical operations

matplotlib & seaborn – Data visualization

datetime – Date and time handling

How to Run

Clone this repository:

git clone <your-repo-link>


Install dependencies:

pip install pandas numpy matplotlib seaborn


Place the CSV datasets in the same directory.

Run the Python scripts or Jupyter notebooks to reproduce analyses and visualizations.

Repository Structure
COVID19-Analysis/
│
├─ data/                # Raw CSV datasets (confirmed, deaths, recovered)
├─ notebooks/           # Jupyter notebooks with analyses
├─ scripts/             # Python scripts for analysis
├─ README.md            # Project description
└─ requirements.txt     # Python dependencies

Conclusion

This project provides a comprehensive analysis of COVID-19 trends, showcasing Python’s capabilities in data cleaning, transformation, aggregation, and visualization. It offers insights into pandemic progression, recovery efficiency, and country-wise impact, which can help in understanding global health outcomes.
