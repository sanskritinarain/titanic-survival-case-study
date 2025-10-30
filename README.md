# titanic-survival-case-study
A data analysis and case study project using the Titanic dataset to explore survival patterns, with a focus on why females had higher survival rates than males. This repository contains the cleaned dataset, exploratory data analysis, visualizations, and statistical insights combining historical context and data science methods.

Project Overview
This project analyzes the famous Titanic dataset to explore survival patterns and uncover the factors that influenced who lived and who didn’t.
The central research question is: Why did females have higher survival rates than males?

Through exploratory data analysis, visualization, and historical context, this study combines data science techniques with storytelling to understand the social and structural factors behind the disaster.

Contents:
1.Cleaned and preprocessed Titanic dataset
2.Jupyter Notebook with full exploratory data analysis (Titanic_Survival_Analysis.ipynb)
3.Visualizations of survival rates by gender, class, age, and family size
4.Statistical summaries and historical interpretation of findings

Quick Start:

1.Clone the repository
git clone https://github.com/yourusername/Titanic-Survival-Analysis.git
cd Titanic-Survival-Analysis

2.Install dependencies
pip install -r requirements.txt

3.Launch the notebook
jupyter notebook Titanic_Survival_Analysis.ipynb


Requirements:

Python 3.8+
pandas
numpy
matplotlib
seaborn
scikit-learn (if modeling is included)
jupyter


Methodology:

1.Data Cleaning-
Handled missing values (Age, Cabin, Embarked)
Encoded categorical features (Sex, Embarked, Pclass)
Created new features such as family size
2.Exploratory Data Analysis (EDA)-
Explored survival patterns by gender, class, and age
Visualized distributions and correlations
3.Visualization-
Used bar plots, histograms, and heatmaps to uncover relationships
Compared survival odds across demographic and social factors
4.Interpretation-
Combined quantitative findings with historical context from maritime practices


Key Findings:

Factor	Observation
Gender	Females had a much higher survival rate (~74%) than males (~19%)
Class	First- and second-class passengers had better survival odds
Age	Children were prioritized during evacuation
Family Size	Moderate family sizes (2–4) had better survival rates than singles or large families


Historical Context:

During the Titanic evacuation, the “women and children first” maritime protocol was heavily enforced.
Social norms prioritized saving women and children, influencing survival patterns.
Passenger class determined physical access to lifeboats — first-class passengers were closer and faced fewer barriers.
Third-class passengers were disadvantaged due to locked gates, lower decks, and slower communication.
These social and structural dynamics are clearly reflected in the dataset’s survival trends.


Future Work:

Build a predictive survival model (e.g., logistic regression, random forest)
Perform feature importance analysis
Develop an interactive dashboard (Streamlit / Plotly)
Incorporate natural language summaries for interpretability


References:

Titanic Dataset on Kaggle
Historical sources on maritime safety and the Titanic disaster


Author

Sanskriti Narain
sanskritinarain2005@gmail.com

This project is licensed under the MIT License — feel free to use, modify, and share.
