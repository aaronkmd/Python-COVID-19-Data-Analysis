# COVID-19 Data Analysis

This repository contains the analysis performed on COVID-19 data, focusing on the conditions contributing to COVID-19 deaths across different demographics and locations in the United States. The purpose of this analysis was to uncover insights into the factors contributing to COVID-19 mortality and provide data-driven recommendations for public health strategies and policy decisions.

## Project Overview

This project utilizes real-world data on COVID-19 deaths and contributing conditions from the Centers for Disease Control and Prevention (CDC). The goal of this analysis was to understand the impact of various conditions on COVID-19 deaths, analyze geographical variations, and develop predictive models to support public health officials and policymakers in targeting interventions effectively.

## Repository Structure

- **01 Project Management:** Contains the project brief which outlines the objectives and expectations of the analysis.
- **02 Data:** Contains a PDF file with links to the datasets and files used in the analysis.
- **03 Scripts:** Includes all Python scripts used in the data analysis, structured in Jupyter Notebooks.
- **04 Analysis/Visualizations:** Contains image files of the visualizations generated during the analysis.
- **05 Final Report:** Includes the Tableau Public storyboard as a PDF file, available to view on Tableau Public [here](https://public.tableau.com/views/CFAch6-AnalysisofCOVID-19Data/Story1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link).

## Key Questions Addressed

- Which conditions are most strongly associated with COVID-19 deaths?
- How do COVID-19 death rates vary across different states and age groups?
- What are the geographical patterns in COVID-19 death rates and contributing conditions across the United States?
- How can linear regression and clustering analyses be used to predict and understand COVID-19 mortality?
- What are the temporal trends and seasonal patterns in COVID-19 deaths and contributing conditions?

## Tools Used

- **Python:** Primary programming language used for data analysis.
- **Pandas:** For data manipulation and analysis.
- **NumPy:** For numerical operations.
- **Matplotlib & Seaborn:** For generating data visualizations.
- **Scikit-learn:** For implementing machine learning models.
- **Statsmodels:** For time series analysis and ARIMA modeling.
- **Geopandas:** For geographical data manipulation and visualization.
- **Plotly:** For interactive visualizations.
- **Tableau Public:** For creating interactive visualizations and dashboards.

## Visualizations

This project includes various visualizations such as scatter plots, choropleth maps, bar charts, and time-series plots, which illustrate the impact of different conditions on COVID-19 mortality, geographical variations, and temporal trends.

## Analysis Sections

### Initial Data Exploration

- **Exploration of the dataset:** Understanding the structure and key statistics.
- **Cleaning and preprocessing:** Handling missing values, outliers, and data type conversions.

### Geographical Analysis

- **Choropleth maps:** Visualizing total COVID-19 deaths and death rates per 100,000 population across states.
- **Insights:** Identifying high-impact regions and patterns.

### Linear Regression Analysis

- **Model Building:** Developing a regression model to predict COVID-19 deaths based on the number of mentions of conditions.
- **Performance Evaluation:** Assessing the model using Mean Squared Error (MSE) and R-squared score.

### Cluster Analysis

- **K-means clustering:** Identifying clusters of states with similar COVID-19 impact.
- **Cluster Interpretation:** Analyzing the characteristics and severity of each cluster.

### Time Series Analysis

- **Trend and Seasonality:** Decomposing time series data to identify trends and seasonal patterns.
- **Stationarity Check:** Performing the Dickey-Fuller test and differencing to achieve stationarity.
- **Autocorrelation Analysis:** Using ACF and PACF plots to analyze the autocorrelation structure of the time series data.

## Conclusion and Recommendations

The analysis provided actionable insights into the factors contributing to COVID-19 mortality, highlighting the importance of demographic and condition-specific factors. The findings support targeted public health interventions and resource allocation strategies to better prepare for future health crises.

## Limitations and Potential Biases

- **Provisional Nature of Data:** Data is provisional and conclusions may need revision as finalized data becomes available.
- **Reporting Delays:** Delays in reporting can affect the completeness of recent data.
- **Inconsistent Reporting Standards:** Variability in state-level reporting standards may impact reliability.
- **Multiple Conditions:** Presence of multiple conditions per death complicates analysis.
- **Double Counting Risk:** Deaths involving multiple conditions are counted in each relevant category.
- **Population Data:** Analysis is based on 2020 population data, which may not reflect changes over time.

## Recommendations for Future Work

- **Enhanced Clustering:** Perform clustering analyses on additional conditions and demographics.
- **Predictive Modeling:** Develop models to identify high-risk populations and enhance public health strategies.
