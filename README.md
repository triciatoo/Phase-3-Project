  SyriaTel Customer Churn Prediction

1. Project Overview

Customer churn is a major source of revenue loss for telecommunications companies. This project builds a classification model to predict whether a customer is likely to stop doing business with SyriaTel. The goal is to help the business identify at-risk customers early and take proactive retention actions.

2. Business Problem

Stakeholder: SyriaTel (telecommunications provider)

Problem: Customers cancel service unexpectedly, leading to revenue loss

Objective: Predict customer churn so SyriaTel can intervene before customers leave

3. Data

Source: Kaggle – Telecom Customer Churn Dataset

Description: Customer account information, usage patterns, service plans, and churn status

Target Variable: churn (Yes / No)


4. Methodology

Exploratory Data Analysis (EDA)

Data cleaning and preprocessing

Feature engineering and encoding

Baseline model for comparison

Iterative classification models 

Model evaluation using recall, precision, and F1-score

5. Model Evaluation

Focused on recall for churners to minimize missed at-risk customers

Final model evaluated on holdout test data

Trade-offs between false positives and false negatives discussed

6. Key Findings

Customers with frequent customer service calls are more likely to churn

International plan users show higher churn risk

High usage and high charges increase churn likelihood

7. Business Recommendations

Use the model to proactively identify and retain high-risk customers

Improve service resolution for customers with repeated support calls

Review and optimize international plan offerings

Integrate churn risk scores into CRM systems for targeted retention efforts

8. Repository Structure

├── data/                # Ignored (raw data files)
├── index.ipynb          # Main analysis notebook
├── README.md            # Project overview
├── .gitignore           # Ignored files

9. How to Run the Project

Clone the repository

Install required dependencies

Download the dataset from Kaggle

Run index.ipynb from top to bottom

10. Limitations & Future Work

Dataset represents historical behavior and may not capture future trends

Model performance may change as customer behavior evolves

Future work could include cost-sensitive modeling and real-time deployment