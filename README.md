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
Based on the analysis of `insurance.csv`, here are the key takeaways:

| Category | Metric | Result |
| :--- | :--- | :--- |
| **Age** | Average Patient Age | **39.2 years** |
| **Gender** | Male / Female | **51% / 49%** |
| **Smoking** | Smoker Prevalence | **20% Yes / 80% No** |
| **Avg Cost** | Overall Annual Premium | **$13,270.42** |
| **Avg Cost** | Smokers vs. Non-Smokers | **$32,050.23 vs. $8,434.27** |
| **Family** | Avg Number of Children | **1.09 per patient** |

> **Major Insight:** Smoking status is the most significant factor affecting costs, with smokers paying nearly **4x more** on average than non-smokers.

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

