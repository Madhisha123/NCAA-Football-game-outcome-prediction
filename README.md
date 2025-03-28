# NCAA Football Game Outcome Prediction  

## Project Overview  
This project analyzes NCAA Men's and Women's March Madness basketball games to identify key trends and predict match outcomes. The dataset consists of **35 files** covering both men's and women's basketball data. We conducted extensive exploratory data analysis (EDA) and built predictive models using historical data.  

## Problem Statement  
The objective is to leverage past tournament and regular-season data to predict match outcomes and extract insights into **team performance, consistency, and key factors affecting wins**. This analysis provides valuable information for teams, analysts, and sports bettors.  

## Approach & Methodology  

### 1. Data Preparation & Cleaning  
- The dataset was cleaned and preprocessed using **Python (Pandas, NumPy)**.  
- Handled missing values, duplicate entries, and irrelevant columns.  
- Focused on essential metrics like **team performance, player statistics, and game results**.  

### 2. Exploratory Data Analysis (EDA)  
- Identified **top-performing teams** based on various metrics.  
- Created **visualizations** using **Matplotlib & Seaborn** to analyze trends.  

### 3. Key Findings  
- **Total number of matches played** (Men & Women separately).  
- **Top 10 winning teams** for both Men’s and Women’s tournaments.  
- **Combined total matches played** across both tournaments.  
- **Highest average scores** for Men’s and Women’s teams.  
- **Team with the most overtime wins** in both Men’s and Women’s tournaments.  
- **Best winning percentage team** for both Men’s and Women’s categories.  
- **Most consistent performing teams** in both tournaments.  

### 4. Visualizations & Insights (Matplotlib/Pyplot)  
- **Score distribution** for Men’s and Women’s tournaments.  
- **Margin of victory distribution** for both tournaments.  
- **Home vs. Away win comparison** for Men’s and Women’s teams.  
- **Overtime impact** on Men’s and Women’s tournament results.  

### 5. Feature Engineering & Modeling  
- Created features like **team efficiency, offensive/defensive ratings, and player contributions**.  
- Applied **Logistic Regression, Random Forest, and XGBoost** to predict game outcomes.  
- Evaluated models using **accuracy, F1-score, and confusion matrix**.  

## Results & Key Insights  
- The **most significant factors** affecting game outcomes included **turnover ratio, 3-point accuracy, and free throw percentage**.  
- Teams with **higher consistency in season performance** had better tournament results.  
- **Overtime games** impacted overall fatigue and affected future match outcomes.  
- **Home-court advantage** was more significant in the regular season than in the tournament.  

## Tools Used  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- **Jupyter Notebook** (Kaggle for model development)  

## Repository Structure  
### 📌 Notes  
- This project was developed entirely in **Python**.  
- Originally hosted on **Kaggle**: [View Notebook Here](https://www.kaggle.com/code/madhisham/march-machine-learning-mania)  
