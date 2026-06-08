# Decoding the DNA of Real Madrid

### A Machine Learning Investigation of La Liga Teams

## Project Overview

Football is no longer driven only by what happens on the pitch. Modern clubs increasingly rely on data to understand performance, identify strengths and weaknesses, and support decision-making.

As a football fan and Real Madrid supporter, I wanted to use Machine Learning to explore a question that goes beyond simple match predictions:

**What makes Real Madrid different from other La Liga teams, and which teams are statistically most similar to it?**

This project combines football analytics and Machine Learning to analyze team performance across La Liga and understand how Real Madrid compares to the rest of the league.

---

## Objectives

The project aims to:

* Explore and understand La Liga match data.
* Build team-level performance profiles.
* Identify different playing styles among teams.
* Discover which teams are most similar to Real Madrid.
* Determine whether Real Madrid behaves as a typical elite team or an outlier.
* Identify the factors most associated with winning matches.
* Compare multiple Machine Learning techniques and evaluate their usefulness in football analytics.

---

## Dataset

**Competition:** Spanish La Liga

**Source:** Historical match statistics dataset (SP1)

The dataset contains information such as:

* Match results
* Goals scored and conceded
* Shots and shots on target
* Corners
* Fouls committed
* Yellow and red cards
* Betting odds
* Additional match statistics

A complete data audit and feature selection process was performed before applying Machine Learning techniques.

---

## Methodology

### 1. Data Preparation

* Data cleaning
* Missing value analysis
* Feature engineering
* Feature selection
* Team-level aggregation

### 2. Team Identity Analysis

Custom performance indicators were created to describe each team's football identity:

* Goals per Match
* Shots per Match
* Conversion Rate
* Defensive Strength
* Clean Sheet Rate
* Discipline Indicators
* Win Rate

---

## Machine Learning Techniques

### Clustering

Used to discover different team profiles and playing styles.

* K-Means
* K-Means++
* Hierarchical Clustering
* DBSCAN

### Classification

Used to understand which factors contribute most to match outcomes.

* K-Nearest Neighbors (KNN)
* Decision Tree
* Logistic Regression

### Ensemble Learning

Used to improve predictive performance and analyze feature importance.

* Random Forest
* AdaBoost
* Stacking Ensemble

---

## Key Questions Investigated

* What playing styles exist in La Liga?
* Which cluster contains Real Madrid?
* Which teams are most similar to Real Madrid?
* Is Real Madrid an outlier?
* What separates successful teams from the rest of the league?
* Which statistics best explain match success?

---

## Main Findings

The analysis revealed that:

* Real Madrid belongs to the elite group of teams in La Liga.
* Barcelona emerged as one of the closest teams to Real Madrid in terms of statistical profile.
* Team success is strongly linked to offensive efficiency and defensive consistency.
* Different clustering methods produced meaningful football-related team groupings.
* Ensemble methods provided valuable insights into the factors associated with winning matches.

---

## Project Structure

```text
├── data/
│   └── SP1.csv
│
├── notebook/
│   └── Real_Madrid_LaLiga_Analytics.ipynb
│
├── report/
│   └── Final_Report.pdf
│
├── images/
│   ├── PCA_Clusters.png
│   ├── Feature_Importance.png
│   └── Model_Comparison.png
│
├── README.md
└── requirements.txt
```

---

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* SciPy
* Google Colab

---

## Author

**Oussama Id Omar**

Machine Learning Project – La Liga Football Analytics

---

## Future Improvements

Potential future developments include:

* Integration of Expected Goals (xG) metrics
* Multi-season analysis
* Player-level analytics
* Advanced football performance modeling
* Deep Learning approaches for match prediction

---

## Final Note

This project was designed as a football analytics investigation rather than a traditional Machine Learning assignment. The goal was not only to apply algorithms, but also to understand how data can help explain team performance and reveal what makes Real Madrid one of the most successful clubs in La Liga.
