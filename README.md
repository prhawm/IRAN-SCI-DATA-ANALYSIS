# IRAN-SCI-DATA-ANALYSIS
Analysis and Clustering of Household Income and Expenditure Data

📜 Project Overview

This project analyzes the household income and expenditure data provided by SCI (Statistical Center of Iran), covering rural (R) and urban (U) data. The study spans various years and aims to generate insights into income, expenses, consumption patterns, and other socio-economic metrics. Furthermore, the project applies machine learning techniques like clustering to categorize households based on their income and expenditure patterns.

📊 Objectives

Statistical Analysis

	1.	Descriptive Statistics:
	•	Analyze the distribution of:
	•	Household characteristics (education level, age, relationship with head of household, employment status).
	•	Household vehicle usage (car, motorcycle, bicycle, etc.) over the years.
	•	Pension income and property rental costs over the years in a cumulative chart.
	•	Plot trends in household expenditure on:
	•	Prepared food, hotels, and restaurants.
	•	Generate a correlation matrix for:
	•	Clothing and footwear costs.
	•	Food expenses.
	•	Housing, utilities, fuel, and lighting costs.
	•	Healthcare and medical expenses.
	2.	Real vs. Nominal Income Trends:
	•	Define Real Income (inflation-adjusted) and Nominal Income (not adjusted for inflation).
	•	Visualize the trend of real and nominal income.
	3.	Hypothesis Testing:
	•	Determine if:
	•	Rural and urban household incomes in Chaharmahal and Bakhtiari Province are statistically equivalent.
	•	The average value of urban and rural houses shows a significant difference.
	•	Annual income differs significantly between those who attended university and those who didn’t.
	•	A claim that urban household incomes improved in 1401 vs. 1400 holds true, analyzing both income and living standards.

Machine Learning - Clustering

	1.	Problem Statement:
	•	Redefine deciles of household categorization based on their income and expenditure (data from 1398 and 1401).
	2.	Clustering Tasks:
	•	K-Means Clustering:
	1.	Cluster households into 10 clusters based on income and expenses, plotting results with cluster centers.
	2.	Experiment with different values of k (1 to 20) and determine the optimal k using Within-Cluster Sum of Squares (WCSS).
	•	DBSCAN Clustering:
	•	Perform clustering with DBSCAN and tune hyperparameters to generate 10 meaningful clusters.
	•	Plot results and explain the effect of hyperparameters on clustering output.
