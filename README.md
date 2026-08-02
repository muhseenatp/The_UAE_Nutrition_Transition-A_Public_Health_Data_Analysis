# The_UAE_Nutrition_Transition-A_Public_Health_Data_Analysis

A data analysis project evaluating dietary patterns, health markers, and demographic trends across the UAE. Using Python (Pandas, Matplotlib, Seaborn), raw health survey data was cleaned, processed, and visualized to reveal insights into daily caloric intake, child and adult obesity and Anaemia trends to support public health initiatives.

## 📌 1. Project Overview

Over the past four decades, rapid urbanization and economic transition in the UAE significantly altered population diets and lifestyle health risks. The primary objective of this project is to analyze longitudinal nutritional trends (1975–2024), evaluating the structural shift from undernutrition (thinness, underweight) to overnutrition (overweight, obesity), along with underlying demographic disparities.

### Key Objectives:
- **Data Cleaning & Preprocessing**: Handle missing values, adjust data types, and normalize nutritional metrics.
- **Exploratory Data Analysis**: Evaluate dietary consumption trends across age groups, genders, and regions within the UAE.
- **Data Visualization**: Generate informative univariate, bivariate, and multivariate visualizations.
- **Actionable Insights**: Extract meaningful conclusions to support evidence-based dietary recommendations and public health awareness.

---
## 🛠️ 2. Tools & Technologies Used

* **Python:** Primary programming language.
* **Jupyter Notebook:** Interactive environment for code execution and reporting.
* **Pandas:** Data manipulation, cleaning, aggregation, and time-series pivoting.
* **Matplotlib:** Custom multi-panel visual layouts, bar charts, and figure styling.
* **Seaborn:** Advanced statistical plotting (box plots, linear regressions, KDE density plots, heatmaps).
* **Plotly:** Interactive, high-resolution time-series exploration.
---
## 📊 3. Dataset Information

- **Source**: World Health Organization (WHO) - Nutrition Landscape Information System (NLiS)
- **Key Features / Columns**:
        GHO (CODE), GHO (DISPLAY), GHO (URL), YEAR (DISPLAY),
        STARTYEAR, ENDYEAR, REGION (CODE), REGION (DISPLAY),
        COUNTRY (CODE), COUNTRY (DISPLAY), DIMENSION (TYPE),
        DIMENSION (CODE), DIMENSION (NAME), Numeric, Value, Low,
        High
---

## 🔄 4. Steps Followed

1. Imported the dataset using Pandas.
2. Cleaned the data by:
   - Removing duplicate values.
   - Converting date and numeric columns to proper formats.
   - Filling missing values with descriptive placeholders.
   - Renaming columns into simple, standardized formats.
3. Performed exploratory data analysis (EDA) using Pandas.
4. Created visualizations using Matplotlib, Seaborn and Plotly such as:
   - Bar plot for Distribution of Top 8 Health Indicators in Dataset.
   - Bivariate Line Plots for Anaemia Trends in Children vs. Women. 
   - Box plot for Distribution Spectrum of Child Malnutrition Metrics.
   - Linear Regression Scatter Plot for comparing Underweight and Obesity.
   - Plotly Grouped Bar for Interactive Gender Disparity Comparison.
 5. Generated meaningful insights and potential recommendations.
---

## 💡 5. Key Insights & Findings

* **The Big Shift (From Underfed to Overfed)**: Over the last 40 years, the UAE successfully solved the problem of hunger and being underweight. However, as underweight rates dropped to almost zero, obesity and overweight rates skyrocketed to take their place.

* **The Gender Gap is Real and Permanent**: Women have consistently had much higher obesity rates than men. This isn't just a recent trend; the data shows this gap has existed for the entire 40-year period.

* **Weight Issues are a Family Matter**: The data shows that childhood weight problems and adult obesity rise together perfectly. This means children are inheriting the lifestyle and eating habits of the adults in their households.

* **The 1980s and 90s Were the Fastest Growth Years**: The most rapid, dangerous spike in national weight gain happened during the 1980s and 1990s as the country's economy and modern food habits grew extremely fast.

* **Anaemia and Micronutrient Parallel Trends**: Female micronutrient vulnerabilities (such as anemia rates in women of reproductive age) closely track child health metrics, pointing to shared dietary quality issues (like poor nutrient density) regardless of caloric intake.

* **The Problem is Finally Leveling Off**: There is good news! Over the last 10 to 15 years, the rapid rise in obesity has finally slowed down and started to level off. This proves that recent national health campaigns and awareness are working.
---

## 📈 6. Visualizations Overview

The analysis includes several visualizations such as:
* Dataset Overview: Indicator Record Distribution 
* Gender Disparity Spread & Statistical Benchmarking
* Linear Regression Analysis & Cross-Indicator Correlation Heatmap
* Decade-over-Decade Shifts & Interactive Plotly Explorer
* Anaemia Trends, Pediatric Malnutrition, and Infant Feeding Indicators
* Combined Risk Stacked Bar, Year-over-Year Rate of Change in Adult Obesity, and Interactive Gender Comparison
* Multi-Panel Executive Dataset Summary & Profile Dashboard

---

## 📁 7. Files Included

* Nutrition_indicators_UAE.csv – Raw dataset.
* UAE_NutritionIndicators.ipynb – Pandas analysis and visualizations.
* README.md – Project description and usage instructions.

## ⚙️ 8. How to Use

1. Open UAE_NutritionIndicators.ipynb using Jupyter Notebook or JupyterLab.
2. Run the notebook cells step by step to view data cleaning, analysis, and
   visualizations.

---

## 🎯 9. Conclusion

This project illustrates how Python's data science stack can be leveraged to extract meaningful public health narratives from longitudinal datasets.
The findings offer valuable historical context for policymakers, pointing toward family-centric lifestyle programs and targeted gender-specific health initiatives in the UAE.

---
