Customer & Marketing Analytics Team Assignment

Introduction

This project involves analyzing a dataset from an online shopping platform selling consumer electronics and PC accessories. The dataset consists of 600 customer reviews along with various variables such as rating scores, sentiment scores, topics mentioned, review length, purchase incidence, and customer background information.

Description of the Data

Rating Scores: Customers provide numeric ratings on a 1-5 scale.
Textual Reviews: Reviews have been processed into numeric variables including sentiment, topics mentioned, and review length.
Purchase Incidence: Indicates whether a purchase occurred after reviewing a product.
Total Number of Purchases: Records the total number of purchases each customer made in their relational history with the platform.
Customer & Product Background Variables: Includes demographic information such as age, country, gender, and product category.
Questions and Modeling Approach

Question 0: Data Preparation
Dummy coding for categorical variables such as product category and age ranges may be necessary.
Consider removing columns related to negative mentions or combining them into a single column.
Question 1: Rating Scores
Build a linear regression model to investigate factors influencing higher rating scores.
Assess the impact of sentiment, topics mentioned, and review length on rating scores.
Question 2: Purchase Incidence
Utilize logistic regression to predict purchase incidence based on rating scores, sentiment, topics mentioned, and review length.
Examine whether positive reviews lead to increased purchase probability.
Question 3: Total Number of Purchases
Employ Poisson regression to explain the variation in the total number of purchases.
Evaluate the effects of different variables on the expected number of purchases.
Question 4: Interactions
Choose one model from Questions 1-3 to explore interactions.
Test 1-2 potential interactions between variables to assess their significance and implications.
GitHub Readme File

Project Overview
This repository contains code and documentation for a customer and marketing analytics team assignment. The project aims to analyze the impact of customer reviews on business outcomes using regression modeling techniques.

Contents
Data Preparation: Explanation of data preprocessing steps, including dummy coding and variable recoding.
Question 1: Description of the linear regression model investigating factors influencing rating scores.
Question 2: Overview of the logistic regression model predicting purchase incidence.
Question 3: Details of the Poisson regression model explaining the total number of purchases.
Question 4: Discussion of interactions explored in the chosen model.
Conclusion: Summary of findings and marketing implications derived from the analysis.
Usage
Clone the repository to your local machine.
Ensure you have the necessary software or environment to run the code (e.g., R, Python).
Open the project files in your preferred IDE or notebook.
Run the code cells to execute the regression models.
Review the results and interpretations provided in the documentation.
