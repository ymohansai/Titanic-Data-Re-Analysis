# Titanic-Data-Re-Analysis
-> Project Overview

This project is part of the Data Science with Python Internship – Task 3 by Maincrafts.
The goal is to perform Exploratory Data Analysis (EDA) on the Titanic dataset, clean the data, and generate insights through visualizations.

-> Steps Completed

Data Cleaning

Filled missing Age values with the mean.

Filled missing Embarked values with the mode.

Dropped irrelevant columns: Cabin, Ticket, Name.

Feature Engineering

Created AgeGroup by binning passengers into categories:

Child (0–12), Teen (13–19), Adult (20–40), Senior (40+).

Created FamilySize = SibSp + Parch.

Analysis

Survival rate by Age Group.

Survival rate by Embarkation Port.

Survival rate by Family Size.

Visualizations

Age distribution → Histogram.

Survival by Gender → Bar Plot.

Survival by Class → Bar Plot.

Survival by Age Group → Bar Plot.

Survival by Embarkation Port → Bar Plot.

Survival by Family Size → Bar Plot.

Correlation Heatmap of numerical features.

-> Insights

Women had a higher survival rate than men.

Passengers in 1st Class had higher chances of survival.

Children had better survival rates than adults.

Embarkation port influenced survival likelihood.

Moderate family sizes had better chances compared to being alone or very large families.

-> Files

Maincrafts_Task_Completed.ipynb → Completed Jupyter Notebook with analysis & visualizations.

train_and_test2.csv → Titanic dataset (used for analysis).

README.md → Project documentation.

-> Tools & Libraries

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook / Google Colab
