# 📊 Netflix Analysis & Prediction

This repository contains an exploratory and predictive analysis of Netflix movies and TV shows using Python and machine learning models.

📌 Project Description

The objective of this project is to analyze the characteristics of movies and TV shows on Netflix, identify patterns in the data, and build a predictive model using Random Forest to estimate key variables, such as a movie’s popularity.

📂 Repository Structure

📁 Netflix_Analysis
│── 📁 data               # Data (not included in the repository, available on Kaggle)
│── 📁 Graficos           # Generated visualizations
│── 📁 Linkedin Post      # Resources for sharing on social media
│── 📄 Netflix_Analysis.ipynb  # Notebook with the complete analysis
│── 📄 README.md          # This file

🔗 Dataset

The data used in this project comes from Kaggle. You can find it here:
👉 Netflix Movies and TV Shows Dataset

🛠 Tools & Technologies Used

✅ Python - Main programming language
✅ Pandas - Data manipulation and cleaning
✅ Matplotlib & Seaborn - Data visualization
✅ Scikit-Learn - Modeling and hyperparameter tuning with Random Forest
✅ Git & GitHub - Version control and project storage

🔍 Methodology

Data Exploration
	•	Data loading and cleaning
	•	Handling missing values
	•	Transforming categorical variables

Data Visualization
	•	Distribution of key features
	•	Correlations between variables
	•	Feature importance in Random Forest

Predictive Modeling
	•	Implementation of a Random Forest Regressor model
	•	Hyperparameter tuning with GridSearchCV and RandomizedSearchCV
	•	Model evaluation using MAE, MSE, and R²

Results Export
	•	Generating visualizations
	•	Exporting processed data for Power BI

📈 Key Findings
	•	Vote count (vote_count) and budget (budget) are the most influential variables in predicting a movie’s popularity.
	•	Movies with higher budgets tend to receive more votes and popularity.
	•	Genre and country of origin also impact popularity.
	•	The optimized Random Forest model achieved an R² of approximately 0.52, indicating moderate predictive capability.

🚀 How to Run

1️⃣ Clone this repository:

git clone https://github.com/juanfeijoo98/Netflix-Analysis-Prediction.git

2️⃣ Install the necessary dependencies:

pip install -r requirements.txt  # (if you have a requirements file)

3️⃣ Open and run the Netflix_Analysis.ipynb notebook.

🏆 Contributions

If you have suggestions or improvements, feel free to open an Issue or submit a Pull Request. Your contribution is welcome! 😊

📩 Contact: LinkedIn