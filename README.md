# COVID-19-Global-Data-Tracker
📋 Project Overview

The COVID-19 Global Data Tracker is a Jupyter Notebook project that uses the Our World in Data COVID-19 dataset to analyze global COVID-19 trends. This notebook covers data loading, cleaning, exploratory data analysis (EDA), and visualization to provide insights into the pandemic's impact.

🎯 Project Objectives

Import and clean real-world COVID-19 data

Perform exploratory data analysis (EDA) on cases, deaths, and vaccinations

Generate visualizations to highlight key trends

Provide data-driven insights and reflections

🚀 Features

Efficient data loading and preprocessing using pandas

Handling missing values with forward filling for smoother trend lines

Time series analysis for total cases, total deaths, and total vaccinations

Professional visualizations using Matplotlib and Seaborn

📦 Requirements

The following libraries installed:

pandas - for data loading, cleaning, and manipulation

matplotlib - for creating static visualizations

seaborn - for enhanced data visualization and styling

plotly.express - for interactive plots (optional, not fully used yet)

🗂️ File Structure

├── Owid-Covid-Data.ipynb   # Main Jupyter Notebook (provided)
├── owid-covid-data.csv     # COVID-19 data file (required)
├── README.md               # Project documentation (this file)

🛠️ Setup Instructions

Ensure the owid-covid-data.csv file is in the same directory as the notebook.

Install the required libraries (if not installed):

pip install pandas matplotlib seaborn plotly

Open the notebook and run all cells to generate the visualizations.

📊 Key Data Processing Steps

Data Import: Load the dataset using pandas.read_csv()

Data Cleaning: Drop rows with critical missing values (date, location) and fill cumulative columns using ffill

Filtering: Focus on selected countries (United States, Africa, India,Zambia,Angola, Afghanistan, Albania, Algeria, Andorra, Antigua, Austria, Botswana)

Visualization: Plot total cases and deaths over time for selected countries

🔍 Usage

This notebook provides a step-by-step analysis, including:

Initial data inspection (shape, columns, missing values)

Data cleaning (date conversion, forward filling)

Time series visualization for selected countries

🚀 How to Run the Project

Ensure the owid-covid-data.csv file is in the same directory as the notebook.

Install the required libraries if not already installed:

pip install pandas matplotlib seaborn plotly

Open the notebook Owid-Covid-Data.ipynb in Jupyter or any compatible environment.

Run all cells to generate the data insights and visualizations.

🔎 Insights and Reflections

Cases Over Time: Total cases have shown sharp rises during multiple waves, with different peaks in each country.

Deaths Analysis: The relationship between cases and deaths varies significantly by region, reflecting differences in healthcare systems and vaccination rates.

Vaccination Progress: Vaccination rollouts have played a critical role in reducing the severity and spread of COVID-19, but coverage remains uneven across regions.

Data Gaps: Some countries have inconsistent or incomplete data, highlighting the challenges of global health data collection.
