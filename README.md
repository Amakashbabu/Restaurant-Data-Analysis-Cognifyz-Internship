Restaurant Data Analysis Project

Internship Program: Data Analysis Internship
Organization: Cognifyz Technologies

Project Overview

This project involves end-to-end exploratory and advanced data analysis on a restaurant dataset to uncover insights related to customer preferences, city-wise performance, pricing patterns, service availability, and brand consistency.

The analysis is divided into two levels:

Level-1: Descriptive & foundational analysis

Level-2: Advanced pattern-based analysis

The goal is to transform raw restaurant data into actionable business insights that can support decision-making for food-tech platforms and restaurant aggregators.

 Dataset Description

The dataset contains structured information about restaurants across multiple cities.
Each row represents a restaurant and includes the following key attributes:

Restaurant Name – Name of the restaurant

City – City where the restaurant is located

Cuisines – Types of cuisines served (multiple values possible)

Aggregate rating – Average customer rating

Votes – Number of customer votes

Price range – Pricing category

Has Online delivery – Online delivery availability

Latitude, Longitude – Geographic location

Some restaurants serve multiple cuisines and some appear multiple times as part of restaurant chains.

🛠 Tools & Technologies Used

Python

Pandas – data cleaning and aggregation

Matplotlib – data visualization

Jupyter Notebook – analysis environment

 Project Structure
Restaurant_Data_Analysis/
│
├── Dataset.csv
├── README.md
│
├── notebooks/
│   ├── Level_1_Analysis.ipynb
│   └── Level_2_Analysis.ipynb
│
├── reports/
│   ├── Level_1_Cognifyz_Data_Analysis_Report.pdf
│   └── Level_2_Cognifyz_Data_Analysis_Report.pdf
│
└── visuals/
    ├── level1/
    └── level2/
 Level-1 Analysis Summary

Focus: Descriptive analytics

Key Tasks

Top 3 most common cuisines and their market share

City with highest number of restaurants

Average restaurant ratings by city

Price range distribution

Online delivery adoption and rating comparison

Key Insights

A small number of cuisines dominate customer demand

High restaurant density does not always imply higher quality

Most restaurants operate in lower to mid-price ranges

Restaurants offering online delivery generally receive higher ratings

 Level-2 Analysis Summary

Focus: Advanced and pattern-based analysis

Key Tasks

Aggregate rating and vote distribution

Cuisine combination performance analysis

Geographic clustering of restaurants

Restaurant chain performance evaluation

Key Insights

Most restaurants cluster around mid-range ratings

Certain cuisine combinations consistently receive higher ratings

Restaurants are concentrated in urban food hubs

Strong restaurant chains maintain consistent quality and customer trust

 Visualizations

The project includes multiple visualizations such as:

Bar charts for cuisine, city, and price analysis

Rating distribution charts

Geographic scatter plots

Restaurant chain comparison charts

These visuals help communicate insights clearly to both technical and non-technical audiences.

 Business Impact

The insights from this project can help:

Food-tech platforms optimize restaurant onboarding

Identify high-potential cities for expansion

Improve pricing and service strategies

Strengthen partnerships with high-performing restaurant chains

 How to Run the Project

Clone or download the repository

Open Jupyter Notebook

Load the dataset:

import pandas as pd
df = pd.read_csv("Dataset.csv")

Run notebooks in order:

Level_1_Restaurant_Data_Analysis.ipynb

Level_2_Advanced_Restaurant_Data_Analysis.ipynb

 Conclusion

This project demonstrates a complete data analytics workflow—from data understanding and cleaning to insight generation and business interpretation.
By progressing from Level-1 to Level-2, the analysis moves from descriptive statistics to strategic insights, reflecting real-world data analyst practices.

 Author

Name: Akash Babu
Role: Data Analysis Intern

🔗 Acknowledgement

This project was completed as part of the Data Analysis Internship Program by Cognifyz Technologies.