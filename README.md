# GDP and Life Expectancy Data Analysis Project

## 📌 Project Overview

**Economic Prosperity vs. Longevity: A Longitudinal Study (2000–2015)**

This project explores the relationship between the Gross Domestic Product (GDP) and Life Expectancy at Birth across six geographically and economically diverse nations: Chile, China, Mexico, the United States, and Zimbabwe. The analysis spans a 15-year period from 2000 to 2015.  

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
2. **Data Loading and Inspection** – Load CSV file, handle missing values.
3. **Prepare Data for Analysis** – Ensure appropriate data types, adjust column names for clarity.
4. **Exploratory Data Analysis** – GDP and Life Expectancy distributions, summary statistics by country, trend analysis, explore relationship between GDP and Life Expectancy.
5. **Conclusion and Main Findings** – Key findings of the study and conclusion.


## 📊 Key Findings & Insights

The project yielded several significant insights:

* **Positive Correlation:** There is a general positive correlation between GDP and life expectancy. As GDP increases, life expectancy tends to rise.

* **Diminishing Returns:** The relationship is not strictly linear. At very high GDP levels, gains in life expectancy appear to diminish, suggesting a "ceiling effect."

* **Global Progress:** All six countries showed an increase in both GDP and life expectancy over the 15-year period.

* **Economic Disparities:** Large divergences in GDP were noted, with the United States and China leading the group, while Chile and Zimbabwe represented significantly smaller economies.

* **Average Life Expectancy:** Germany has the highest average life expectancy (79.66 years), followed closely by Chile and the USA. Zimbabwe, despite improvements in recent years, had a significantly lower average life expectancy (50.09 years).

* **Distribution of GDP and Life Expectancy:** The distribution of GDP was highly right-skewed, with most data points concentrated at the lower end of the distribution and a long tail extending to very high GDP values (primarily from the USA and China). On the contrary, the distribution of life expectancy is heavily left-skewed, with the majority of the life expectancy data points concentrated in the range of 70 to 80 years, with a significant peak around the late 70s. 

> **Conclusion:** While economic prosperity, as measured by GDP, generally correlates positively with improved life expectancy, the impact appear to be more significant at lower levels of development. Countries with robust economies and healthcare systems tend to maintain high and gradually increasing life expectancies. The analysis highlights both the global progress in health and economic development, as well as persistent disparities.


## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)

2. Ensure you have the all_data.csv file in the same directory as the notebook.

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook GDP-and-Life-Expectancy-Project.ipynb


## 🪜 Next Steps

* **Economic Data:** GDP in current U.S. dollars may be not the best metric to assess economic prosperity. It would be insightful to try the following approaches for the GDP variable.

*GDP per Capita (PPP):* Use Purchasing Power Parity (PPP) in constant international dollars. This adjusts for the cost of living and inflation, allowing you to see if life expectancy gains are truly tied to individual wealth.  <br>

*Logarithmic Transformation:* Since GDP is highly skewed, try using $log(\text{GDP})$.

* **Expansion of the Dataset:** To understand if the results hold true with a more representative sample of countries, pull data from the World Bank and WHO for more countries, and group countries by income level (Low, Middle, High). This would allow to test the hypothesis of a positive non-linear relationship between economic prosperity and life expectancy.  

* **Correlation Coefficients:** Calculate the Pearson or Spearman rank correlation for each country individually. Does the strength of the correlation differ between a developing economy like China and a mature one like Germany?