# GDP and Life Expectancy Data Analysis Project

## 📌 Project Overview
This project explores the relationship between the Gross Domestic Product (GDP) and Life Expectancy at Birth in Years across six different countries: Chile, China, Mexico, the United States, and Zimbabwe. The analysis spans a 15-year period from 2000 to 2015.  

The key objective of this study is to shed light on the relationship between economic prosperity, as measured by GDP, and life expectancy.


## 🎯 Objectives

The main research questions we will seek to answer are the following:

* What is the distribution of both GDP and life expectancy?
* What is the average life expectancy for each country?
* What is the trend of GDP over time in the six countries?
* Has life expectancy increased over time in the six countries?
* Is there a linear relationship between GDP and life expectancy?


## 🗂️ Data Sources

* **GDP Source:** [World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD) national accounts data, and OECD National Accounts data files.
* **Life expectancy Data Source:** [World Health Organization](http://apps.who.int/gho/data/node.main.688)


## 🛠️ Tech Stack & Libraries
* Python 3
* Jupyter Notebook – Analysis environment
* Pandas – Data processing
* Matplotlib and Seaborn – Data visualization


## 📈 Notebook Structure
1. **Introduction** – Project objectives, research questions.
2. **Data Loading and Inspection** – Load CSV file, handle missing values, data types, clean column names.
3. **Prepare Data for Analysis** – Ensure appropriate data types, adjust column names for clarity.
4. **Exploratory Data Analysis** – GDP and Life Expectancy distributions, summary statistics by country, trend analysis, explore relationship between GDP and Life Expectancy.
5. **Conclusion and Main Findings** – Key findings of the study and conclusion.


## 📊 Key Findings & Insights
The project yielded several significant insights:

* Positive Correlation: There is a general positive correlation between GDP and life expectancy. As GDP increases, life expectancy tends to rise.

* Diminishing Returns: The relationship is not strictly linear. At very high GDP levels, gains in life expectancy appear to diminish, suggesting a "ceiling effect."

* Global Progress: All six countries showed an increase in both GDP and life expectancy over the 15-year period.

* Economic Disparities: Large divergences in GDP were noted, with the United States and China leading the group, while Chile and Zimbabwe represented significantly smaller economies.

* Distribution of GDP and Life Expectancy: The distribution of GDP was highly right-skewed, with most data points concentrated at the lower end of the distribution and a long tail extending to very high GDP values (primarily from the USA and China). On the contrary, the distribution of life expectancy is heavily left-skewed, with the majority of the life expectancy data points concentrated in the range of 70 to 80 years, with a significant peak around the late 70s. 

> **Conclusion:** In conclusion, while economic prosperity, as measured by GDP, generally correlates positively with improved life expectancy, the impact appear to be more significant at lower levels of development. Countries with robust economies and healthcare systems tend to maintain high and gradually increasing life expectancies. The analysis highlights both the global progress in health and economic development, as well as persistent disparities.

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)

2. Ensure you have the insurance.csv file in the same directory as the notebook.

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook US_Medical_Insurance_Costs.ipynb

## 🪜 Future Work

* **Bias Analysis:** Investigate if certain regions are overrepresented or if age groups are skewed.

* **Predictive Modeling:** Implement a multiple linear regression model to predict insurance costs based on BMI, age, sex, smoking status, geographical region and number of children.

* **Dictionary Mapping:** Refactor the code to store patient data in a nested dictionary for more efficient querying.

