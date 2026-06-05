# Data Analytics Portfolio

Welcome to my data analytics portfolio. This repository showcases a collection of end-to-end data analysis projects demonstrating my expertise in data cleaning, exploratory data analysis (EDA), predictive modeling, time-series analysis, and interactive dashboard creation.

Leveraging my Master’s degree in Computer Science specializing in Data Science and Artificial Intelligence, these projects utilize a robust technical stack—including Python, SQL, Power BI, and Tableau to transform raw datasets into actionable strategic insights.

---

## Portfolio Projects

### 1. E-Commerce Data Analysis & Visualization — Online Retail II

This project analyzes the **Online Retail II** dataset, a real transactional dataset containing e-commerce sales for a UK-based online retailer. The data includes detailed records of customer purchases such as invoice numbers, product codes, descriptions, quantities, unit prices, transaction dates, and customer identifiers.

The goal of this analysis is to transform the raw transactional data into meaningful insights through:

* **Data Cleaning:** Correcting data types, handling missing values, fixing inconsistent entries, and preparing the dataset for analysis.
* **Feature Engineering:** Creating new variables to enhance analytical depth.
* **Exploratory Data Analysis (EDA):** Examining distributions, identifying patterns, and exploring relationships between variables to understand customer behavior and sales dynamics.
* **Visualization:** Using Matplotlib and Seaborn to produce clear and interpretable charts that highlight key trends and findings.
* **Dashboarding:** Developed a dedicated Tableau dashboard for this dataset to monitor sales performance and track key business metrics over time.
* More information about the dataset is available at the [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) page.

### 2. Global Sales Analytics — Walmart Global Superstore

The Kaggle Global Superstore dataset is a comprehensive dataset containing information about sales and orders in a global superstore, making it a valuable resource for data analysis and visualization tasks. For this project, the data was processed and transformed from its original text format (txt) to CSV.

The goal of this analysis is to transform the raw transactional data into meaningful insights through:

* **Data Cleaning:** Correcting data types, handling missing values, fixing inconsistent entries, and preparing the dataset for analysis.
* **Feature Engineering:** Creating new variables to enhance analytical depth.
* **Exploratory Data Analysis (EDA):** Examining distributions, identifying patterns, and exploring relationships between variables to understand customer behavior and sales dynamics.
* **Visualization:** Using Matplotlib and Seaborn to produce clear and interpretable charts that highlight key trends and findings.
* **Dashboarding:** Built an interactive Power BI dashboard for the Walmart Global Superstore dataset to drive corporate strategy and manage overall global performance.
* The transformed CSV file used in this analysis and a description of the columns can be found here: [Global Superstore](https://www.kaggle.com/datasets/anandaramg/global-superstore/data).

### 3. Supply Chain & Operations Optimization — Olist (Brazilian E-Commerce)

This project analyzes a real Brazilian e-commerce dataset from **Olist Store**, covering 100,000 orders placed between 2016 and 2018 across multiple marketplaces in Brazil. Olist is Brazil's largest department store platform, connecting small businesses nationwide to customers through a single contract.

The dataset includes comprehensive order information such as pricing, payment methods, shipping performance, customer locations, product details, and customer reviews. All data has been anonymized to protect privacy.

This analysis explores:

* Customer behavior and regional sales patterns.
* Shipping efficiency and delivery performance.
* Product category performance and factors directly affecting customer satisfaction.
* Extraction of actionable insights aimed at optimizing supply chain logistics and overall e-commerce operations.
* For more details about the dataset, see: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

### 4. Clinical Data Processing & Medical Analytics — UCI Heart Disease

This project utilizes the UCI Heart Disease repository, which contains data collected from 4 separate hospitals. The repository includes multiple files:

* `cleveland.df`, `hungarian.df`, `switzerland.df`, `long-beach-va.df` → The raw heart disease datasets from the 4 hospitals.
* `processed.cleveland.df`, `processed.hungarian.df`, `processed.switzerland.df`, `processed.va.df` → Cleaned and processed versions of the files above.
* `heart-disease.names` → The description of columns acting as the data dictionary.
* `reprocessed.hungarian.df` → Another processed variant.
* `new.df` → An aggregated or test dataset.

For this analysis, `processed.cleveland.df` was selected as it is the most commonly used version in research and tutorials. It contains 14 key clinical attributes (columns), where the last column is the target variable indicating the presence and severity of heart disease (0 = no disease, 1-4 = levels of heart disease). The `heart-disease.names` file was thoroughly utilized to decode column meanings.

* **Data Engineering & Cleaning:** Centralized, cleaned, and structured the clinical data to make it ready for predictive algorithms.
* **Dashboarding:** Developed a Tableau dashboard to visualize the dataset, highlighting the distribution and correlation of cardiovascular risk factors.

### 5. Operational Demand Forecasting — Seoul Bike Sharing System

In urban centers worldwide, bike-sharing systems have become a cornerstone of modern mobility, enhancing accessibility and reducing environmental impact. A critical challenge for these systems is ensuring a stable and efficient supply—making rental bikes available at the right place and time to minimize user waiting periods. This project addresses this operational concern by conducting a comprehensive analysis of the **Seoul Bike Sharing System**.

The core objective is to explore and model the factors influencing bike rental demand to ultimately inform better inventory management and distribution strategies. By predicting the number of bikes required at any given hour, service providers can significantly improve system reliability and user satisfaction.

#### Data Description

The analysis utilizes a detailed dataset capturing the hourly count of public bicycles rented, enriched with corresponding meteorological and calendar data. Key variables include:

* **Target Variable:** `Rented Bike Count` - The number of bikes rented per hour.
* **Temporal Features:** Date and hour, enabling precise time-series analysis.
* **Weather Conditions:** Temperature (°C), Humidity (%), Windspeed (m/s), Visibility (10m), Dew Point Temperature (°C), Solar Radiation (MJ/m²), Rainfall (mm), and Snowfall (cm).
* **Holiday Information:** A binary indicator for public holidays.

#### Analytical Approach

This investigation proceeds through a structured, multi-faceted data pipeline:

* **Exploratory Data Analysis (EDA) in SQL:** Initial data profiling, summary statistics, and cohort analysis are performed using SQL to understand data integrity, distributions, and foundational relationships.
* **Time Series Analysis:** Rental patterns are decomposed to identify core trends, seasonal cycles (daily, weekly, monthly), and irregularities.
* **Visual Analytics with Plotly:** Interactive dashboards and visualizations are built using Plotly to dynamically explore correlations between weather events, holidays, and rental demand, revealing intuitive, actionable insights for operational planning.
* More information about the dataset is available at the [Seoul Bike Sharing Demand](https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand) page.
