# Investment Analysis using Business Analytics

## Overview
The aim of this analysis is to investigate various investment patterns, preferences, and factors that influence investment decisions. The findings from this analysis can help investors, financial planners, and businesses make more informed decisions by understanding what drives individuals' investment choices.

## Dataset Info
The dataset consists of several attributes that describe demographic details and investment preferences of participants. It contains columns such as 'Gender', 'Age', 'Investment Avenues', 'Savings Objectives', and 'Expectations', which provide insights into the investment behavior of individuals. The dataset contains 40 rows and 24 columns with information ranging from demographic characteristics to investment choices. The raw dataset used in this project has been included within this repository

## Analysis Techniques
This project uses Python for data analysis, with libraries like:
* Pandas: For data cleaning, manipulation, and summary statistics.
* Matplotlib and Seaborn: For data visualization to represent findings clearly.
* NumPy: For numerical computations and statistical analysis.
  
The analysis explores various aspects of the dataset, including:
* Demographic distribution: Visualizing gender distribution, and other characteristics.
* Descriptive statistics: Calculating and analyzing statistics like mean, median, and standard deviation for numerical fields such as age and income.
* Investment preferences: Identifying the most preferred investment avenues and the reasons driving these choices.
* Correlation analysis: Investigating relationships between factors like age, expected returns, and investment duration.

## Task 1 - Data Overview
**Objective**: Understand the dataset structure.
- Loaded the dataset into a data analysis tool using Pandas in Python.
- Analyzed the dataset's structure using `info()` and `describe()` functions.
- **Output**: Number of entries, column types, and basic statistical information.

**Files**: 
- [task1_data_overview.ipynb](./Task1_DataOverview/task1_data_overview.ipynb)
- [dataset.csv](./data/dataset.csv)

---

## Task 2 - Gender Distribution
**Objective**: Visualize gender distribution in the dataset.
- Extracted the gender column and visualized the distribution using a pie chart.
- **Output**: A bar chart and a pie chart showing gender distribution.

**Files**: 
- [task2_gender_distribution.ipynb](./Task2_GenderDistribution/task2_gender_distribution.ipynb)
- [gender_distribution.png](./Task2_GenderDistribution/gender_distribution.png)

---

## Task 3 - Descriptive Statistics
**Objective**: Present basic statistics for numerical columns.
- Calculated the mean, median, and standard deviation for age and income columns.
- **Output**: Summary of descriptive statistics for all numerical data.

**Files**: 
- [task3_descriptive_statistics.ipynb](./Task3_DescriptiveStatistics/task3_descriptive_statistics.ipynb)

---

## Task 4 - Most Preferred Investment Avenue
**Objective**: Identify the most preferred investment avenue.
- Conducted frequency analysis to find the most popular investment avenue among participants.
- **Output**: Bar chart showing the frequency of each investment avenue.

**Files**: 
- [task4_investment_avenue_analysis.ipynb](./Task4_InvestmentAvenue/task4_investment_avenue_analysis.ipynb)
- [investment_avenue_chart.png](./Task4_InvestmentAvenue/investment_avenue_chart.png)

---

## Task 5 - Reasons for Investment
**Objective**: Analyze and summarize reasons for participants' investment choices.
- Explored the 'Reasons' column and identified common themes.
- **Output**: A textual summary of recurring reasons for investment.

**Files**: 
- [task5_reasons_for_investment.ipynb](./Task5_InvestmentReasons/task5_reasons_for_investment.ipynb)

---

## Task 6 - Savings Objectives
**Objective**: Identify and present the main savings objectives.
- Analyzed the 'Savings Objectives' column and created a list of the top objectives.
- **Output**: Summary of participants' main savings objectives.

**Files**: 
- [task6_savings_objectives.ipynb](./Task6_SavingsObjectives/task6_savings_objectives.ipynb)

---

## Task 7 - Common Information Sources
**Objective**: Analyze common sources participants rely on for investment information.
- Explored the 'Information Sources' column and identified the most commonly cited sources.
- **Output**: Summary of the top information sources participants rely on.

**Files**: 
- [task7_information_sources.ipynb](./Task7_InformationSources/task7_information_sources.ipynb)

---

## Task 8 - Investment Duration
**Objective**: Calculate the average investment duration.
- Used statistical methods to calculate the average investment duration from the dataset.
- **Output**: Average duration and a histogram of investment durations.

**Files**: 
- [task8_investment_duration.ipynb](./Task8_InvestmentDuration/task8_investment_duration.ipynb)
- [investment_duration_histogram.png](./Task8_InvestmentDuration/investment_duration_histogram.png)

---

## Task 9 - Expectations from Investments
**Objective**: Summarize participants' expectations from investments.
- Analyzed the 'Expectations' column and identified common expectations such as returns and growth.
- **Output**: List of participants' expectations.

**Files**: 
- [task9_investment_expectations.ipynb](./Task9_Expectations/task9_investment_expectations.ipynb)

---

## Task 10 - Correlation Analysis
**Objective**: Explore potential correlations between factors such as age, investment duration, and expected returns.
- Calculated correlation coefficients and visualized correlations using scatter plots.
- **Output**: Correlation heatmap and scatter plots for selected columns.

**Files**: 
- [task10_correlation_analysis.ipynb](./Task10_CorrelationAnalysis/task10_correlation_analysis.ipynb)
- [correlation_heatmap.png](./Task10_CorrelationAnalysis/correlation_heatmap.png)

---

## Technologies Used
- **Python** (pandas, matplotlib, seaborn)
- **Jupyter Notebook**
- **Excel** (for data cleaning)
- **Power BI** (for visualization tasks)
- **GitHub Pages** (for portfolio hosting)

---

## How to Run
1. Clone this repository: 
```bash
git clone https://github.com/SonaliGupta/Business-Analytics-Internship-Cognifyz.git
