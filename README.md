Exploratory-Data-Analysis
Exploratory Data Analysis Project on Python Haryo prabowo

Introduction
In this repository, I will perform Exploratory Data Analysis (EDA) on admission status of high school graduates applying for universities.

Steps:
Missing value check and handling
Duplicated value check and handling
Statistical summaries of columns
Univariate analysis
Bivariate analysis
Overall summary/EDA findings
The details can be found on the notebook in this repo

Overall summary/EDA findings
The data does not contain major issues. There are only some NULL values and duplicated rows, and have been handled accordingly.
Overall, the minimum and maximum values make sense for each column.
Overall, all numeric columns have a somewhat symmetrical distributions, with an outlier in recommendation_strength column
From the barchart of research experience vs admit status: we found that students who have research experience is more likely to be admitted
From correlation heatmap: we note that TOEFL Score, GRE Score and GPA is highly correlated --> choose only one of them for modelling
From Pairplot on admit_status: we found many useful insights, with the keypoint being most students that are admitted have high score in TOEFL Score, GRE Score and GPA
