# Bio-Signal Analysis for Smoking Prediction

## Overview

This repository contains a machine learning project focused on predicting smoking habits using bio-signal data. The project aims to build a classification model that can accurately determine the presence or absence of smoking in an individual based on a dataset of biological and health-related attributes.

## Problem Statement

The goal is to develop an intelligent system that can analyze a person's bio-signal data and classify whether they are a smoker or not. This can be valuable for global companies and research institutions looking to understand smoking patterns and develop targeted interventions.

## Dataset

The dataset used in this project is a collection of basic health biological signal data, containing approximately 55,000 records with 27 attributes. The dataset includes features such as:

*   **ID:** Index
*   **gender:** Gender of a person (M or F)
*   **age:** Age of a person (5-year gap)
*   **height(cm):** Height of a person
*   **weight(kg):** Weight of a person
*   **waist(cm):** Waist circumference length
*   **eyesight(left):** Left eyesight
*   **eyesight(right):** Right eyesight
*   **hearing(left):** Hearing pulse in left ear
*   **hearing(right):** Hearing pulse in right ear
*   **systolic:** Blood pressure (systolic)
*   **relaxation:** Blood pressure (relaxation)
*   **fasting blood sugar:** Blood test
*   **Cholesterol:** Total cholesterol
*   **triglyceride:** Lipid found in blood
*   **HDL:** HDL cholesterol type
*   **LDL:** LDL cholesterol type
*   **hemoglobin:** Transporting oxygen in blood
*   **Urine protein:** Excess of bloodborne proteins in urine
*   **serum creatinine:** Amount of creatinine in blood
*   **AST:** Glutamic oxaloacetic transaminase type
*   **ALT:** Glutamic pyruvic transaminase type
*   **Gtp:** γ-GTP
*   **oral:** Oral Examination status
*   **dental caries:** Tooth decay
*   **tartar:** Tartar status
*   **smoking:** Smoker (0 or 1) - *Target Variable*

## Tasks Performed

The following tasks were performed in this project:

1.  **Data Loading:**
    *   Loading the data using Pandas.
    *   Removing irrelevant columns (if any).
    *   Checking the shape and datatypes of the dataframe.
    *   Calculating statistical data (mean, std, min, max, etc.).

2.  **Data Cleaning:**
    *   Checking for missing values.
    *   Handling missing values (if any).
    *   Performing One-Hot Encoding for categorical features (gender).

3.  **Data Visualization:**
    *   Visualizing the distribution of smokers vs. non-smokers.
    *   Analyzing smoking prevalence by gender.
    *   Analyzing smoking prevalence by age group.
    *   Detecting outliers using box plots (and deciding whether to remove or keep them based on domain knowledge).

4.  **Feature Selection:**
    *   Calculating feature importance using a suitable method (e.g., Random Forest, SelectKBest).
    *   Selecting the top N features based on their importance scores.

5.  **Model Building & Evaluation:**
    *   Splitting the dataset into training and testing sets.
    *   Building and evaluating the following classification models:
        *   Logistic Regression
        *   Decision Tree
        *   Bagging Classifier
        *   Extra Trees
        *   Random Forest
    *   Calculating accuracy and generating classification reports for each model.
