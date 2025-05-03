# Life_expectancy_EDA_Python
An exploratory data analysis (EDA) project using Python to examine global life expectancy trends and their relationships with economic development, healthcare, education, and environmental factors. Key insights were uncovered and visualized through data-driven analysis across years, countries, regions, and income groups.

# Project Objectives
- Explore and clean the dataset by handling missing values and NaNs.
- Merge and process additional datasets to include key variables such as GDP and Population for more comprehensive analysis.
- Create new calculated measures such as GDP per capita and Total Diseases and Injuries to enhance insights.
- Perform univariate analysis to describe variable distributions, detect skewness, and understand trends within the dataset.
- Conduct multivariate analysis with Life Expectancy as the dependent variable to assess the impact of economic development, healthcare, education, and environmental factors.
# Tools Used
- Python (Pandas, NumPy): Used for data cleaning, transformation, and analytical computations such as merging datasets and calculating new variables.
- Matplotlib & Seaborn: Utilized for visualizing distributions, trends, and multivariate relationships related to life expectancy.
- Jupyter Notebook: Provided an interactive environment for exploratory analysis and step-by-step presentation of insights.
# Dataset
- Source: Kaggle – Life Expectancy and Socio-Economic Indicators - World Bank Open Data
- Overview: The dataset includes annual data from 2000 to 2019 for 174 countries, covering various socio-economic and health-related indicators that potentially influence life expectancy.
- Key Features:
Country, Country Code, Region, IncomeGroup – Basic identifiers and classifications
Life expectancy – Average expected lifespan at birth
CO2 (kiloton) – Environmental impact from fossil fuels
Health Expenditure (% of GDP) – National health spending
Education Expenditure (% of GDP) – Public education spending
Unemployment (% of labor force) – Labor market indicator
Corruption (CPIA rating) – Governance and transparency
Sanitation Access (% of Population) – Population using safe sanitation services
Undernourishment (% of Population) – Population with inadequate dietary energy
DALYs due to Communicable / Non-Communicable Diseases / Injuries – Measures of health burden and quality of life loss
GDP, Population – Merged from external World Bank datasets
GDP per capita – Calculated during preprocessing
Total Diseases and Injuries – Calculated during preprocessing
=> These features allow for in-depth analysis of how economic, environmental, and healthcare factors correlate with life expectancy across different regions and income groups.

# Outcome
- The dataset was thoroughly cleaned and processed, including handling missing values and standardizing columns for consistency.
- Descriptive statistical analysis was conducted across all key indicators to summarize the data.
- Visualizations were created to explore the distribution, trends, and correlations among the various metrics.
- Key insights were derived to identify areas of effective performance and underperformance, enabling targeted improvements and informed decision-making.

# Key Insights Presented
1. What are the top 10 countries with the highest average life expectancy in the world?
How do the socio-economic, healthcare, and environmental factors in these countries compare to the global average?
2. What are the trends in average life expectancy over the years?
Which year had the highest and lowest life expectancy? What factors contributed to these differences?
3. How does life expectancy differ across countries with different income groups?
4. What is the relationship between CO2 emissions, economic development, and life expectancy worldwide?
How do CO2 emissions correlate with economic growth and life expectancy in different regions and countries?
