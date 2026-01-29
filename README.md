# Google-Play-Store-Apps-Analysis


📊 Google Play Store Apps Analysis
📌 Project Overview

This project focuses on exploratory data analysis (EDA) and data cleaning of the Google Play Store apps dataset to uncover insights about app categories, ratings, pricing, installs, and user behavior.
The analysis helps understand what factors influence app popularity and performance on the Play Store.

🎯 Objectives

Clean and preprocess raw Play Store data

Handle missing values, duplicates, and inconsistent formats

Analyze app categories, ratings, installs, and pricing trends

Visualize relationships between key variables

Generate insights useful for product, marketing, and business decisions

🧰 Tools & Technologies

Python

Pandas – Data cleaning & manipulation

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Statistical visualizations

KaggleHub – Dataset access

Google Colab – Development environment

📂 Dataset

Source: Kaggle – Google Play Store Apps Dataset

Records: ~10,000 apps

Features Include:

App Name

Category

Rating

Reviews

Installs

Price

Type (Free / Paid)

Content Rating

Genres

🧹 Data Cleaning & Preprocessing

The following steps were performed to ensure high-quality data:

Removed duplicate records

Handled missing values (mean imputation for ratings)

Cleaned numeric fields:

Removed $, +, and commas from Price, Installs, Reviews

Converted columns to proper data types

Filtered invalid ratings (ratings > 5)

Created a new feature:

isPaid → Binary flag for paid apps

Exported cleaned dataset as:

cleaned_playstore.csv

📊 Exploratory Data Analysis (EDA)
Key Analyses Performed:

Top 10 app categories by count

Average rating by category

Distribution of free vs paid apps

Rating distribution across apps

Relationship between:

Price vs Rating

Installs vs Rating (log scale)

Correlation analysis among:

Rating, Reviews, Installs, Price, Paid status

Visualizations Used:

Bar charts

Histograms

Scatter plots

Heatmaps (correlation matrix)

🔍 Key Insights

Free apps dominate the Play Store ecosystem

Certain categories consistently receive higher average ratings

App price has low correlation with ratings

Install counts increase sharply for highly rated apps

Reviews and installs show strong positive correlation

📁 Project Structure
📦 Google-Play-Store-Apps-Analysis
 ┣ 📜 DevTown_assignment1.ipynb
 ┣ 📄 cleaned_playstore.csv
 ┣ 📄 eda_summary.csv
 ┗ 📄 README.md

📌 Output Files

cleaned_playstore.csv → Final cleaned dataset

eda_summary.csv → Statistical summary of numerical features

🚀 How to Run the Project

Clone the repository

Open DevTown_assignment1.ipynb in Google Colab or Jupyter Notebook

Install required libraries:

pip install pandas numpy matplotlib seaborn kagglehub


Run cells sequentially

📈 Skills Demonstrated

Data Cleaning & Wrangling

Exploratory Data Analysis (EDA)

Feature Engineering

Data Visualization

Statistical Interpretation

Python for Data Analytics

🧑‍💻 Author

Vignesh R
Aspiring Data Analyst | Business Analytics | Power BI | Python | SQL

⭐ If you like this project

Give it a ⭐ and feel free to fork or suggest improvements!
