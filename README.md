# Covid-19_Pandemic-Pulse

<h3>COVID-19 Data Analysis</h3>

This project involves analyzing the global spread of COVID-19 using a dataset containing aggregated data of confirmed cases, deaths, and recoveries for various countries. The analysis includes data pre-processing, visualization of global trends, country-specific analysis, comparative analysis, and correlation analysis.

## Dataset
The dataset is sourced from [datasets/covid-19](https://github.com/datasets/covid-19), which provides daily updates on COVID-19 statistics.

## Analysis Tasks
1. **Load and Pre-process the Dataset**
   - Load the dataset using Pandas.
   - Handle missing values.
   - Convert the date column to `datetime` format.

2. **Data Exploration and Cleaning**
   - Display basic information about the dataset.
   - Identify and handle outliers or inconsistencies.

3. **Visualize Global Trends**
   - Plot global trends of confirmed cases, deaths, and recoveries over time using Matplotlib and Seaborn.

4. **Country-Specific Analysis**
   - Visualize COVID-19 trends for specific countries.
   - Compare trends across multiple countries.

5. **Comparative Analysis**
   - Compare total confirmed cases, deaths, and recoveries among the top 10 most affected countries.
   - Analyze growth rates using moving averages.

6. **Correlation Analysis**
   - Analyze the correlation between confirmed cases, deaths, and recoveries.
   - Visualize the correlation matrix using heatmaps.

## Visual Insights
1. **Global Trends**: Separate plots for confirmed cases, deaths, and recoveries.
2. **Top Affected Countries**: Identify the countries with the highest numbers of confirmed cases, deaths, and recoveries.
3. **Country Trends Comparison**: Compare trends among the top 5 most affected countries.
4. **Growth Rates**: Global growth rates of confirmed cases, deaths, and recoveries.
5. **Cumulative Cases**: Cumulative confirmed cases, deaths, and recoveries for the top 10 most affected countries.
6. **Recovery Rates**: Comparison of recovery rates across different countries.
7. **Correlation**: Correlation between confirmed cases, deaths, and recoveries.
