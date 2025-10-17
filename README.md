# 🎬 Movie Rating Analysis & Prediction

## 📖 Project Overview

This project performs an in-depth analysis of a movie dataset to uncover insights about what makes a movie successful. Through comprehensive **Exploratory Data Analysis (EDA)** and **Machine Learning modeling**, we explore the factors that influence IMDB ratings and build a predictive model to estimate a movie's score based on its features.

## 📊 Dataset

The analysis uses the `fandango_scrape.csv dataset containing over 9,000 movies with the following key features:

- **Numerical Features:** `year`, `runtime`, `votes`, `budget`, `box_office`
- **Categorical Features:** `genre`, `rating` (MPAA), `director`, `writer`, `star`, `country`, `company`
- **Target Variable:** `score` (IMDB rating from 1-10)

## 🚀 Quick Start

### Prerequisites
- Python 3.7+
- Jupyter Notebook

🧮 Project Workflow
1. Data Cleaning & Preprocessing
Handled missing values in critical columns

Converted budget and box_office from strings to numeric values

Extracted primary genre from the genre column

Addressed data type inconsistencies

2. Exploratory Data Analysis (EDA)
Distribution Analysis: Examined ratings, runtimes, and release years

Genre Analysis: Compared average ratings across different genres

Financial Impact: Explored relationships between budget, box office, and ratings

Correlation Analysis: Identified relationships between numerical features

3. Machine Learning Modeling
Algorithm: Random Forest Regressor

Feature Engineering: One-hot encoding for categorical variables

Model Evaluation:

Mean Absolute Error (MAE)

R-squared (R²) Score

Feature Importance: Identified most influential factors for movie ratings

📈 Key Insights
🎭 Genre Impact
Dramas and Biographies consistently receive higher ratings

Horror and Comedy genres tend to have lower average scores

💰 Financial Factors
Moderate positive correlation between budget and rating

Box office success shows weak correlation with critical acclaim

⏱️ Runtime Analysis
Optimal movie length appears to be between 90-150 minutes

Extremely short or very long movies often receive lower ratings

🎯 Model Performance
Random Forest model achieved solid predictive performance

Most important features: votes, budget, runtime, and year
