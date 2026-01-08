Hotel Booking Demand Analysis and Prediction(CSE422 project)

This project explores a hotel booking dataset to understand factors influencing cancellations and uses machine learning models to predict whether a booking will be canceled. It encompasses data preprocessing, exploratory data analysis (EDA), and the implementation of various supervised and unsupervised learning algorithms.

Dataset Overview

The project utilizes a dataset containing 119,390 records and 32 columns representing booking information for a Resort Hotel and a City Hotel.

Target Variable: is_canceled (Indicates if the booking was canceled).

Key Features: lead_time, arrival_date, stays_in_weekend_nights, adults, children, meal, country, market_segment, and adr (Average Daily Rate).

Data Source: The notebook fetches data directly from a GitHub repository.

Project Objectives

Exploratory Data Analysis: Identify patterns in hotel bookings and cancellations across different months and hotel types.

Data Preprocessing: Handle missing values (found in company, agent, and country columns), encode categorical variables, and scale numerical features.

Predictive Modeling: Build and evaluate models to accurately predict booking cancellations.

Clustering: Use unsupervised learning to identify distinct customer segments.

Technologies Used

Language: Python

Libraries:

Data Manipulation: pandas, numpy.

Visualization: matplotlib, seaborn.

Machine Learning: scikit-learn (Pipeline, ColumnTransformer, SimpleImputer, StandardScaler, OneHotEncoder).

Key Features & Analysis

The notebook includes detailed steps for:

Data Cleaning: Dropping or imputing missing data. For instance, the company column had 112,593 missing values.

EDA: Visualizing the distribution of cancellations and booking trends.

Pipeline Integration: Utilizing Scikit-Learn pipelines to streamline preprocessing and model training.

Machine Learning Models

The following algorithms are implemented to analyze the data:

Supervised Learning:

Logistic Regression

Random Forest Classifier

Multi-layer Perceptron (MLP) Classifier (Neural Network)

Unsupervised Learning:

K-Means Clustering

Models are evaluated using metrics such as Accuracy, Precision, Recall, and F1-score, along with confusion matrices and classification reports.
