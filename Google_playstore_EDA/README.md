# Google Play Store Data - Exploratory Data Analysis (EDA)

## Project Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on the Google Play Store Apps dataset. The objective is to clean, preprocess, analyze, and visualize app-related data to discover patterns, trends, and valuable insights regarding app categories, ratings, reviews, installs, pricing, and user engagement.

---

## Dataset

**Dataset Source:** Kaggle

**Dataset Link:**  
https://www.kaggle.com/datasets/lava18/google-play-store-apps/

The dataset contains information about Android applications available on the Google Play Store, including app names, categories, ratings, reviews, installs, prices, content ratings, versions, and more.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading & Exploration
- Loaded dataset using Pandas.
- Examined dataset shape, columns, and data types.
- Generated descriptive statistics.
- Explored unique values and dataset structure.

### 2. Data Cleaning
- Cleaned the `Size` column by converting KB and MB values into numeric format.
- Converted `Installs` column into integers by removing commas and plus signs.
- Converted `Price` column into numerical values by removing currency symbols.
- Created additional features such as:
  - `Size_in_Mb`
  - `Installs_category`

### 3. Missing Value Handling
- Identified missing values across all columns.
- Visualized missing data using heatmaps and bar charts.
- Removed records with minimal missing information.
- Filled missing ratings using the mean rating value.
- Preserved important missing values where imputation was not appropriate.

### 4. Correlation Analysis
- Generated correlation matrix for numerical features.
- Analyzed relationships between:
  - Reviews and Installs
  - Ratings and Installs
  - App Size and Installs
- Calculated Pearson Correlation Coefficients.

### 5. Duplicate Removal
- Detected duplicate records.
- Identified duplicate app names.
- Removed duplicate entries to improve data quality.

### 6. Data Visualization
Created multiple visualizations including:
- Correlation Heatmaps
- Distribution Plots
- Boxplots
- Scatter Plots
- Bar Charts
- Trend Analysis Graphs

### 7. Business Insights
Analyzed:
- Categories with the highest number of apps
- Categories with the highest installs
- Categories with the highest reviews
- Categories with the highest ratings
- Free vs Paid app performance
- Impact of app size on installs
- Popular content ratings
- Top-rated applications
- Most-reviewed applications

---

## Key Findings

- Most applications on the Play Store are free.
- Reviews and installs show a strong positive relationship.
- Highly installed apps generally receive more reviews.
- Some categories dominate both installs and app count.
- Most apps have ratings above 4.0, indicating generally positive user satisfaction.
- Duplicate records and inconsistent formats significantly impact analysis and must be cleaned before generating insights.

---

## Results

The project successfully transformed raw Google Play Store data into a clean and analyzable format. Through preprocessing, visualization, and statistical analysis, meaningful insights were extracted regarding app popularity, user engagement, pricing strategies, and category performance.

---

## Future Improvements

- Perform advanced feature engineering.
- Build machine learning models for rating prediction.
- Develop recommendation systems using app metadata.
- Create interactive dashboards using Streamlit or Power BI.
- Analyze sentiment from app reviews.

---

## Author

**Saif Ullah**

Data Analysis | Artificial Intelligence | Machine Learning Enthusiast

---
⭐ If you found this project useful, consider giving it a star on GitHub.