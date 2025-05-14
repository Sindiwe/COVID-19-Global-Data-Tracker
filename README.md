# COVID-19-Global-Data-Tracker
📋 Project Overview

The COVID-19 Global Data Tracker is a Jupyter Notebook project that uses the Our World in Data COVID-19 dataset to analyze global COVID-19 trends. This notebook covers data loading, cleaning, exploratory data analysis (EDA), and visualization to provide insights into the pandemic's impact.

🚀 Features

Efficient data loading and preprocessing using pandas

Handling missing values with forward filling for smoother trend lines

Time series analysis for total cases, total deaths, and total vaccinations

Professional visualizations using Matplotlib and Seaborn

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

Filtering: Focus on selected countries (United States, South Africa, India)

Visualization: Plot total cases and deaths over time for selected countries

🔍 Usage

This notebook provides a step-by-step analysis, including:

Initial data inspection (shape, columns, missing values)

Data cleaning (date conversion, forward filling)

Time series visualization for selected countries
