# Welcome to my Data Science Portfolio
This portfolio showcases my work in data science and analytics, reflecting both academic learning and independent exploration. 
It features projects I've worked on, technical concepts I’ve studied, and certifications I’ve earned in order to continue my growth in this field.

<p align=center> 
  <b>LinkedIn:</b> <a href="https://www.linkedin.com/in/aileen-li-public/">Aileen Li</a>
  &nbsp;&nbsp;&nbsp;&nbsp;<b>E-mail:</b> <a href="mailto:aql254@utexas.edu">aql254@utexas.edu</a>
  <!-- &nbsp;&nbsp;&nbsp;&nbsp;<b>Website:</b> <a href="LINK">Aileen Li</a>                       work on professional website someday -->
</p>

## SQL Portfolio 
This [repository](https://github.com/TartFroYo/Cs327e-Databases) showcases my work from CS 327E: Elements of Databases, a course focused on modern database management and data processing techniques. 
The coursework covered SQL querying, database design, and various database technologies, providing hands-on experience in both operational and analytical database systems.

## Projects
<!-- Micro Project
✅ Smaller in scope – Focuses on a specific task or a single aspect of a larger problem.
✅ Shorter time commitment – Typically takes a few hours to a couple of days to complete.
✅ Simpler implementation – Involves basic data analysis, visualization, or applying a single model.
✅ Limited dataset & techniques – Works with small, clean datasets and minimal preprocessing.

Project
✅ Larger in scope – Addresses a broader question or business problem with multiple steps.
✅ Longer time commitment – Takes days to weeks and often involves iterative improvements.
✅ More complex implementation – Requires a full pipeline (data collection, cleaning, modeling, evaluation).
✅ Diverse dataset & techniques – Works with large or messy data, using multiple ML models or statistical methods. -->

### Predictive Modeling

**Regression**

<!-- [Predicting Air Pollution Hotspots Using Machine Learning](link) :
This project is a reimagined version of a previous academic project where me and my partner originally developed 4 ML models in R to [predict air pollution levels across the U.S](https://github.com/TartFroYo/Predicting-Ambient-Air-Pollution-PM2.5-Across-the-Contiguous-U.S/blob/main/README.md). 
The initial project focused on finding the most accurate prediction model out of four of our choosing based on RMSE and interpret it. In this updated version, I have rebuilt the project in Python, leveraging new datasets and machine learning techniques to improve predictive accuracy and real-world applicability. 
The goal is to create a model that can predict high-risk pollution zones, helping policymakers and urban planners make informed decisions about air quality management. -->

[Predicting Ambient Air Pollution Across the U.S](https://github.com/TartFroYo/Predicting-Ambient-Air-Pollution-PM2.5-Across-the-Contiguous-U.S/blob/main/README.md) :
Air pollution poses a serious health risk, especially for vulnerable populations. 
This project used machine learning models, including XGBoost and Random Forest, to predict annual PM2.5 concentrations across the U.S., with XGBoost achieving the best performance (RMSE: 1.38).applicability.
Feature selection identified key predictors, such as CMAQ, latitude, and aerosol optical depth, that had the most significant impact on PM2.5 concentration predictions.

**Classification**

[Predicting Alzheimer's Disease in Patients](https://github.com/kristenlowe/predicting-alzheimers-diagnosis) :
This project applies machine learning to predict Alzheimer's disease using the Alzheimer's Disease Dataset from Kaggle. 
After exploratory data analysis and feature engineering, various models, including logistic regression, KNN, and tree-based methods, were evaluated for accuracy, sensitivity, and specificity. 
Random forest achieved the highest accuracy at 95%, highlighting the role of machine learning in healthcare analytics.

<!-- This project applies machine learning techniques to predict Alzheimer's disease using the Alzheimer's Disease Dataset from Kaggle. 
The analysis begins with exploratory data analysis, including feature engineering, one-hot encoding, and visualizing trends in the data. 
Several models are implemented, including K-Nearest Neighbors (KNN), logistic regression, lasso and ridge regression, stepwise selection, and tree-based models such as classification trees, random forests, bagging, and boosting. 
Model performance was assessed not only based on overall accuracy but also by evaluating sensitivity and specificity to ensure a balanced assessment of false positives and false negatives. 
Random forest emerged as the most effective model, achieving approximately 95% prediction accuracy. 
This project demonstrates the impact of machine learning in healthcare analytics and the importance of carefully selecting and evaluating models for medical diagnosis. -->

[Predicting Hazardous Near-Earth Objects ](https://github.com/TartFroYo/Predicting-Hazardous-Near-Earth-Objects/tree/main):
This project analyzed a NASA dataset of 338,000+ asteroids to predict whether a Near-Earth Object (NEO) is hazardous. 
After exploratory data analysis on key features like size, velocity, and brightness, we implemented k-Nearest Neighbors, Naïve Bayes, Decision Trees, and Random Forest, achieving 91% accuracy with Random Forest. 
This work demonstrates the role of machine learning in enhancing asteroid risk assessment and space safety.

<!--**Time Series Forecasting**

### Natural Language Processing

**Sentiment Analysis (e.g., product reviews, social media sentiment)**

**Text Classification (e.g., news categorization, email spam detection)**

**Named Entity Recognition (NER) (e.g., extracting entities from resumes or legal documents)**

**Topic Modeling (e.g., analyzing trends in research papers)**

**Text Summarization (e.g., summarizing articles or books)**

### Computer Vision

**Image Classification (e.g., identifying plant diseases, facial emotion detection)**

**Object Detection (e.g., detecting cars in traffic camera feeds)**

**Image Segmentation (e.g., medical imaging analysis)**

**OCR (Optical Character Recognition) (e.g., extracting text from scanned documents)**

### Recommender Systems

**Movie/Book/Product Recommendation (e.g., Netflix-style recommendation engine)**

**Personalized Content Recommendation (e.g., news or articles)**

### Anomaly Detection

**Fraud Detection (e.g., credit card fraud detection, cybersecurity threats)**

**Fault Detection in Manufacturing (e.g., detecting defective products using sensor data)**

**Network Intrusion Detection (e.g., identifying unusual traffic in network logs)** -->

### Data Engineering & Big Data

**Data Pipelines & ETL (e.g., automating data collection, cleaning, and storage)**

[Data Pipeline for Processing Raw Gene Data](https://github.com/TartFroYo/Portfolio/blob/main/Data%20Pipeline%20for%20Processing%20Raw%20Gene%20Data) :
As part of a research initiative, my group designed and implemented a data pipeline to process raw gene sequence data, transforming it into a structured format attached with the necessary info suitable for analysis. 
This involved data collection, cleaning, transformation, and storage to facilitate downstream gene expression analysis. 
The pipeline was built using R in R-Studio, and it automated the extraction and standardization of large genomic datasets. Despite not having access to the code, I can discuss the design choices, challenges, and impact of the project.
This experience strengthened my skills in ETL processes, data engineering principles, and optimizing workflows for large-scale biological data.

<!-- **Web Scraping (e.g., scraping job listings or real estate data)**

**Processing Large Datasets (e.g., using Spark, Dask, or distributed computing)**

### A/B Testing & Experimentation

**Marketing Campaign Analysis (e.g., testing different ad creatives)**

**Website UI/UX Experimentation (e.g., analyzing user engagement metrics)**

### Explainable AI & Model Interpretability

**SHAP/LIME for Feature Importance (e.g., understanding why a model makes certain predictions)**

**Bias & Fairness Audits (e.g., analyzing bias in hiring models)**

### Business Intelligence & Analytics

**Dashboarding & Visualization (e.g., Power BI/Tableau dashboards for financial trends)**

**Customer Segmentation (e.g., clustering customer behavior)**

**Churn Prediction (e.g., identifying customers likely to stop using a service)**

## Micro Projects
### Challenges
<p> Repo of all the code challenges I solved in their respective programming languages: 
  &nbsp;&nbsp;&nbsp;&nbsp; <a href="LINK">SQL</a>
  &nbsp;&nbsp;&nbsp;&nbsp; <a href="LINK">Python</a> 
  &nbsp;&nbsp;&nbsp;&nbsp; <a href="LINK">R</a> </p>                  work in progess
  
 Yes! Here are some great platforms to practice and improve your R coding skills:
General Coding & Algorithm Practice
HackerRank – Offers R challenges, especially in statistics and data science.
LeetCode – Primarily for Python, SQL, and general algorithms, but some problems can be solved in R.
Codewars – Has R programming challenges at various difficulty levels.
Data Science & Statistics in R
DataCamp – Interactive courses in R for data analysis, machine learning, and statistics.
Kaggle – Free R courses, datasets, and coding competitions.
TidyTuesday – Weekly R challenges using real-world datasets.
R-exercises – Tons of exercises categorized by topic (e.g., data wrangling, visualization, machine learning).
Coursera – Offers R courses from Johns Hopkins, Duke, and others.
Machine Learning & Advanced Topics
The Riddler (FiveThirtyEight) – Not R-specific but great math and probability problems you can solve using R.
Project Euler – Algorithmic and mathematical problems solvable in R. -->

## My Learning Journey
<!-- <!-- 1. Foundation-->
+ Basic Statistics & Probability:
  - Descriptive statistics (mean, median, mode, variance, standard deviation),
  - Probability distributions (normal, binomial, Poisson),
  - Central Limit Theorem, Hypothesis testing & p-values

+ Data Analysis & Visualization:
  - Excel basics (pivot tables, VLOOKUP, IF statements),
  - SQL basics (SELECT, WHERE, GROUP BY, JOINS),
  - Python basics (Pandas, Matplotlib, Seaborn),
  - R basics (dplyr, ggplot2),
  - Dashboarding (Tableau, Power BI)

+ Business Analytics & Decision-Making:
  - Business Metrics (KPIs, ROI, CLV),
  - A/B Testing Fundamentals,
  - Time Series Analysis Basics,
  - Intro to Forecasting

<!-- 2. Intermediate Topics-->
+ Machine Learning & Predictive Modeling:
  - Regression (Linear & Logistic),
  - Decision Trees & Random Forests,
  - Feature Engineering,
  - Model Evaluation (MSE, R², ROC Curve),
  - Clustering (K-Means, Hierarchical, DBSCAN)

+ Optimization & Operations Research:
  - Linear Programming (Simplex Method),
  - Supply Chain Optimization,
  - Markov Chains & Monte Carlo Simulation,
  - Dynamic Pricing Strategies

+ Data Engineering & Processing:
  - SQL Advanced Queries (CTE, Window Functions),
  - Data Cleaning & Transformation (ETL, Pandas, NumPy)
  - API Data Extraction & Web Scraping,
  - Cloud Data Storage (BigQuery, Snowflake)

+ Advanced Business Analytics:
  - Advanced A/B Testing (Multi-Armed Bandit),
  - Survival Analysis (Customer Retention Modeling),
  - Risk Analysis & Fraud Detection,
  - Text Analytics & Sentiment Analysis (NLP Basics)

<!--3. Advanced Topics -->
+ Deep Learning & AI for Business:
  - Neural Networks (TensorFlow, PyTorch),
  - Natural Language Processing (Transformers, BERT),
  - Recommendation Systems (Collaborative Filtering, Matrix Factorization),
  - Reinforcement Learning for Decision-Making

+ Big Data & Scalable Analytics:
  - Distributed Computing (Spark, Hadoop),
  - Streaming Data Analysis (Kafka, AWS Kinesis),
  - Real-Time Decision Analytics

+ Advanced Optimization & Simulation:
  - Game Theory & Decision Trees,
  - Bayesian Statistics for Decision-Making,
  - Advanced Forecasting Models (ARIMA, Prophet, LSTMs),
  - Prescriptive Analytics & Optimization

Specialized Topics (Optional Based on Interest)
- Finance & Risk Analytics – Portfolio Optimization, Credit Risk Modeling, Algorithmic Trading
-  Healthcare Analytics – Epidemiology, Patient Outcome Predictions
-  Marketing Analytics – Customer Segmentation, Personalization
-  Cybersecurity & Fraud Detection – Anomaly Detection, Behavioral Analysis -->

## Technical Skills & Tools
<!--**Programming & Scripting** 🟢 Python | SQL | R
**Data Analysis & Visualization** 📊 Pandas | NumPy | Matplotlib | Seaborn | (Power BI) | Tableau | (Excel)
**Machine Learning & Statistics** 📈 Statistical Modeling | Predictive Analytics | Hypothesis Testing | Decision Trees | Feature Engineering | Time Series Analysis
**Data Processing & Engineering** 🛠️ ETL | Data Cleaning & Wrangling | (Web Scraping) | Data Pipelines
**Databases & Cloud Technologies** 💾 SQL Server | MySQL | NoSQL | (Snowflake) | GCP 
**Business & Analytics Tools** 📝 Jupyter Notebook | Git & GitHub | (Qualtrics)
**Soft Skills** 🗣️ Data Storytelling | Communicating Technical Concepts | Problem-Solving | Cross-Functional Collaboration -->

**Methodologies:**
Machine Learning, Predictive Analytics, Time Series Analysis, Statistical Modeling, Hypothesis Testing, Feature Engineering, Decision Trees, A/B Testing, Data Wrangling, ETL

**Languages:**
Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn), R (Dplyr, Tidyr, Caret, ggplot2), SQL

**Tools:**
MySQL, SQL Server, NoSQL, GCP, Tableau, Jupyter Notebook, Git & GitHub, Excel

<!-- ## Certifications
<!--Statistical Methods & Probability.
Data Wrangling & Cleaning Techniques.
Feature Engineering & Model Tuning.
A/B Testing & Experimentation.
Time Series & Forecasting.
Optimization & Business Analytics.
-
Relevant certificates (Google Data Analytics, AWS, IBM, etc.).
Advanced courses completed (ML, deep learning, analytics). -->

Excel
Azure
Snowflake
AWS -->
tableau
power ib
data bricks
cfa
bi tools
