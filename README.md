# Data Analysis in Software Engineering - Effects of Lifestyle on Productivity
## Grde: 17.35

Academic data analysis and machine learning project developed for the **Data Analysis in Software Engineering (MESW0009)** course at the University of Porto, during the 2025/2026 academic year.

## Overview

This project investigates how lifestyle and well-being factors may influence productivity. The analysis combines exploratory data analysis, data preprocessing, visualization, and machine learning techniques to study patterns related to stress, sleep, diet, screen time, mood, and productivity outcomes.

The work was developed as part of a practical assignment focused on applying data analysis methods to real-world datasets, including descriptive statistics, correlation analysis, supervised learning, unsupervised learning, and interpretation of results.

## Project Goal

The main goal of this project is to explore whether lifestyle-related variables can help explain or predict productivity-related outcomes. In particular, the project examines three complementary analytical perspectives:

- A mental health and productivity dataset, focused on variables such as stress level, diet quality, screen time, sleep duration, mood, and productivity.
- A coffee vs. power nap dataset, used to compare two common intervention strategies related to alertness, mood, and productivity.
- A merged dataset created through K-Nearest Neighbors (KNN) matching, enabling a broader exploratory analysis across both sources.

## Datasets

The notebook works with 2 datasets to analyse lifestyle and productivity relationships.

### Dataset 1: Mental Health and Productivity
This dataset is used to study the relationship between daily habits and productivity, with features including sleep duration, daily exercise, screen time, diet quality, stress level, mood rating, and productivity rating.

### Dataset 2: Coffee vs. Power Nap
This dataset compares the effects of coffee and power naps on alertness and productivity, using variables such as intervention type, intervention duration, sleep duration, alertness before and after intervention, mood, productivity rating, and side effects.

### Merged Dataset
A synthetic merged dataset is created using KNN-based matching on shared behavioural features, allowing the project to explore broader patterns across both data sources.

## Methodology

The project follows a complete data analysis pipeline aligned with the course assignment requirements.

### 1. Data Preprocessing
Several preprocessing steps were applied before analysis, including:

- Column renaming and standardization for consistency.
- Data type validation.
- Missing value analysis and imputation.
- Duplicate detection and removal.
- Feature engineering to create more informative variables, such as lifestyle scores, interaction terms, sleep deficit, and alertness change metrics.

### 2. Exploratory Data Analysis
The project includes exploratory analysis to better understand the datasets and identify patterns before modeling.

This stage includes:

- Descriptive statistics.
- Distribution analysis.
- Outlier inspection.
- Correlation analysis between relevant variables.
- Visual exploration using plots such as histograms, boxplots, scatter plots, and PCA-based visualizations.

### 3. Machine Learning
Both supervised and unsupervised learning approaches are used in the notebook, in line with the assignment goals.

Examples of techniques used include:

- K-Nearest Neighbors (KNN), including dataset matching.
- K-Means clustering.
- DBSCAN clustering.
- Decision Tree Regressor.
- Random Forest Regressor.
- Ridge and Lasso regression.
- Dummy baseline models for benchmarking.

### 4. Evaluation
The project also emphasizes model evaluation and benchmarking, which is one of the core learning goals of the assignment.

The notebook includes evaluation-related components such as:

- Cross-validation.
- Grid search.
- Silhouette score for clustering quality.
- Mean squared error and \(R^2\) for regression tasks.
