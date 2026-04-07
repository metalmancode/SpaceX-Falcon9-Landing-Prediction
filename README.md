# SpaceX Falcon 9 First Stage Landing Prediction
Capstone project for the IBM Data Science Professional Certificate


## Project Overview
[cite_start]The goal of this capstone project is to predict whether the first stage of a SpaceX Falcon 9 rocket will land successfully[cite: 17, 18]. SpaceX significantly reduces launch costs by reusing these stages. [cite_start]By predicting the landing outcome, we can estimate the cost of a launch—information that is highly valuable for competitors or satellite operators[cite: 17].

## Methodology
The project followed a structured data science workflow:
1. [cite_start]**Data Collection:** Gathering data through the SpaceX REST API and web scraping[cite: 23, 24].
2. [cite_start]**Data Wrangling:** Cleaning the data, handling missing values, and engineering the "Class" target variable[cite: 25, 26].
3. [cite_start]**Exploratory Data Analysis (EDA):** Using SQL and Visualization (Matplotlib/Seaborn) to identify trends[cite: 27].
4. [cite_start]**Interactive Analytics:** Visualizing launch site locations and proximities using Folium and building a dynamic dashboard with Plotly Dash[cite: 28].
5. [cite_start]**Predictive Modeling:** Training and tuning four machine learning classification models[cite: 29, 30].

## Repository Structure & Notebook Descriptions
This repository contains the following core files:

| File Name | Description |
| :--- | :--- |
| **jupyter-labs-spacex-data-collection-api (1).ipynb** | [cite_start]Uses the SpaceX API to retrieve historical launch data, focusing on Falcon 9 cores[cite: 40]. |
| **jupyter-labs-webscraping.ipynb** | [cite_start]Scrapes Wikipedia using BeautifulSoup to extract additional Falcon 9 launch records[cite: 44]. |
| **labs-jupyter-spacex-Data wrangling (1).ipynb** | [cite_start]Performs data cleaning and creates a binary classification label (1 = success, 0 = failure)[cite: 50]. |
| **jupyter-labs-eda-sql-coursera_sqllite.ipynb** | [cite_start]Executes SQL queries to extract insights like total payload mass and landing counts[cite: 58]. |
| **edadataviz.ipynb** | [cite_start]Creates scatter plots and bar charts to visualize how payload, orbit, and site affect success[cite: 54]. |
| **lab_jupyter_launch_site_location.ipynb** | [cite_start]An interactive map using Folium to show launch site clusters and distance to infrastructure[cite: 63]. |
| **SpaceX_Machine Learning Prediction_Part_5.ipynb** | [cite_start]Builds and tunes Logistic Regression, SVM, Decision Tree, and KNN models using GridSearchCV[cite: 73]. |
| **interactive dashboard.pdf** | [cite_start]A summary report of the Plotly Dash application built to filter launch data in real-time[cite: 68]. |

## Key Findings
* **Model Performance:** All classification models (Logistic Regression, SVM, KNN, and Decision Tree) achieved a test accuracy of approximately **83.33%**[cite: 178, 179].
* [cite_start]**Site Trends:** KSC LC-39A has the highest success count among all launch sites[cite: 168].
* [cite_start]**Success Factors:** Success rates have improved significantly over time, with certain orbits (like SSO and HEO) showing near-perfect success rates in recent years[cite: 91, 103].

## Tools Used
* **Languages:** Python, SQL [cite: 27]
* [cite_start]**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Folium, Scikit-learn, Plotly Dash [cite: 28, 29, 30]
* [cite_start]**Environment:** Jupyter Notebooks [cite: 192]
