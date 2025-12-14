# 🎬 Rotten Tomatoes Movies Analysis

This project is an end-to-end data analysis and machine learning exploration using a Rotten Tomatoes movies dataset.  
The goal of this project was not just to build charts or models, but to understand **how audiences and critics perceive movies differently**.

I worked on this project as a learning exercise to strengthen my skills in:
- Data cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Sentiment analysis (NLP)
- Unsupervised machine learning

## 📊 Dataset Overview

The dataset contains information about movies including:
- Movie title and release year
- Critic score
- Audience (people) score
- Genre and type
- Runtime
- Box office revenue
- Review-related text

The raw dataset contained missing values and inconsistent formats, which were cleaned before analysis.

## 🧹 Data Cleaning & Preparation

Key cleaning steps included:
- Removing unnecessary columns
- Handling missing values
- Converting runtime into numeric minutes
- Cleaning box office values (e.g. $120M, $450K → numeric USD)
- Ensuring score columns were in usable numeric form

These steps were essential to make the data suitable for analysis and modeling.

---

## 🧠 Feature Engineering

### Audience–Critic Gap
A new feature called **gap** was created:

