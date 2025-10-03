# 🦄 Unicorn Companies – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project explores a dataset of 1,074 unicorn companies (valued at over $1B) to practice **exploratory data analysis (EDA)**.  
The dataset includes company valuations, industries, founding years, and investor details.  
The analysis provides insights into **time-to-unicorn status**, **industry valuation trends**, and investment opportunities.

## 🔧 Steps Performed
- Imported and cleaned data using **pandas**.
- Explored dataset size, shape, and structure with `.info()` and `.describe()`.
- Converted **Date Joined** column to datetime and extracted **Year Joined**.
- Created a new column for **years to unicorn status**.
- Took a **random sample of 50 companies** for visualization.
- Built visualizations with **matplotlib**:
  - Maximum years taken to reach unicorn status per industry.
  - Maximum valuation per industry.

## 📊 Key Findings
- Dataset includes **1,074 unicorn companies** worldwide (1919–2021).
- **Healthcare** and **Fintech** industries often take the longest to reach unicorn status.  
- **Consumer & Retail** companies tend to reach unicorn status faster.  
- Some companies took longer to grow but still achieved **very high valuations**.  

## 💡 Recommendations
- Focus on industries with fewer but **high-value unicorns** for investment opportunities.  
- Filter dataset by industries of interest and analyze subsets for deeper insights.  
- Consider **time-to-unicorn** as a metric when evaluating long-term growth potential.  

## 🛠️ Tools & Libraries
- Python  
- pandas  
- matplotlib  

## 📚 Dataset Reference
Bhat, M.A. (2022, March). [*Unicorn Companies*](https://www.kaggle.com/datasets/mysarahmadbhat/unicorn-companies) (Kaggle).  
