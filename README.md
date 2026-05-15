# 🎬 Netflix Content Analytics & Localization Insights

End-to-end analytics project analyzing Netflix's global catalog to identify content performance patterns across genres, languages, and regions — with a focus on multilingual content distribution relevant to localization strategy.

## 🎯 Objective

Design a modular analytics pipeline to explore what drives content engagement on Netflix, with emphasis on regional and language-based patterns that inform localization expansion decisions.

## 🛠 Tech Stack

- **Python** · Pandas · Scikit-learn · Matplotlib · Seaborn
- **Models:** Random Forest Regressor · GridSearchCV · RandomizedSearchCV
- **Evaluation:** MAE · MSE · Feature Importance Analysis
- **Version control:** Git · GitHub

## 🔍 Methodology

**1. Data Engineering & Cleaning**
- Loaded and cleaned Netflix catalog dataset (Kaggle)
- Handled missing values, encoded categorical variables
- Engineered features for genre, language, and regional origin

**2. Exploratory Analysis**
- Distribution of content across genres and countries
- Language and regional engagement patterns
- Correlation analysis between budget, votes, and popularity

**3. Predictive Modeling**
- Random Forest Regressor to predict content popularity
- Hyperparameter tuning via GridSearchCV and RandomizedSearchCV
- Feature importance ranking to identify key drivers

## 📈 Key Findings

- **vote_count and budget** are the strongest predictors of content popularity
- **Genre and country of origin** significantly impact engagement — directly relevant to localization prioritization strategy
- **Multilingual content** shows distinct regional engagement patterns, supporting data-driven decisions on dubbing and subtitle investment
- Feature importance analysis enables prioritization of which content categories benefit most from localization effort

## 📂 Structure
