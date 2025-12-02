# Student Mental Health Analysis Project
This project is a part of the Final Project at [America On Tech's Fall 2022 Data Science Fellowship](https://www.americaontech.org/).
#### -- Project Status: [Completed]

## Project Intro/Objective
This project represents a complete end-to-end application of machine learning principles to address a pressing issue in higher education: understanding and predicting mental health patterns among university students.

## Dataset
* **Data Type:** Synthetic dataset
* **Purpose:** This dataset was synthetically generated for educational and analytical practice within the America on Tech Data Science Fellowship. It simulates student mental health survey data to provide a realistic, privacy-safe environment for practicing the full data science workflow—from curation to predictive modeling—without exposing sensitive personal information.
* **About:** This dataset contains anonymized student profiles with demographic, academic, and mental health indicators for 25,000 simulated university students. It is structured to reflect real-world patterns and challenges in mental health data, including missing values, categorical variables, and class imbalances. The synthetic nature allows for ethical practice in data science while maintaining the statistical relationships and complexities typical of genuine psychological research data.

## Objectives
- [x] Explore demographic distributions (gender, age, major, class status) in the student population.
- [x] Explore demographic distributions (gender, age, major, class status) in the student population.
- [x] Investigate relationships between academic performance (GPA) and mental health indicators.
- [x] Examine treatment-seeking behavior patterns and barriers.
- [x] Build and evaluate a predictive model for depression risk using student attributes.
- [x] Identify key features and risk factors contributing to mental health outcomes.
- [x] Practice the complete data science workflow: curation, exploration, engineering, modeling, and evaluation.
- [x] Create clear, actionable visualizations to communicate insights to non-technical stakeholders.

## Project Workflow
1. **Data Curation** – Handling missing values, encoding categorical variables, and cleaning the dataset
2. **Exploratory Data Analysis (EDA)** – Statistical analysis and visualization of demographic and mental health patterns
3. **Feature Engineering** – Log transformations, dummy coding, and Principal Component Analysis (PCA)
4. **Model Development** – Building and tuning a Decision Tree classifier for depression prediction
5. **Model Evaluation** – Assessing performance using confusion matrix, precision, recall, and other metrics
6. **Insights & Visualization** – Creating actionable visualizations and summarizing key findings

## Features
The dataset includes 11 features across demographic, academic, and mental health domains:
- `id` – Unique identifier
gender – Gender identity (categorical)
- `age` – Age of student (numeric)
- `major` – Field of study (categorical)
- `gpa` – Grade point average (numeric)
- `class_status` – Academic year (categorical)
- `marital_status` – Marital status (binary)
- `have_depression` – Depression indicator (binary)
- `have_anxiety` – Anxiety indicator (binary)
- `have_panicattacks` – Panic attack indicator (binary)
- `seeked_treatment` – Treatment-seeking indicator (binary)

## Key Findings
- Demographic distribution revealed a predominantly freshman student population, comprising 49.8% of the sample, with sophomores (24.8%), juniors (13.0%), and seniors (12.5%) following.
- Mental health prevalence varied significantly by academic year, with clear patterns in anxiety, depression, and panic attack rates across different class statuses.
- GPA distribution showed negative skewness, with mean (2.90) < median (2.91) < mode (3.88), indicating most students perform above average academically.
- Low variance in both age (3.99) and GPA (0.40) suggests the student population is relatively homogeneous in these attributes, with data points clustered close to their respective means.
- Log transformation successfully normalized the GPA distribution, converting the skewed original data to a more symmetrical distribution suitable for machine learning algorithms.
- Principal Component Analysis revealed evenly distributed variance across all features, with each principal component explaining approximately 10% of variance, suggesting no single feature dominates the dataset's structure.

## Tools & Libraries
* Jupyter Notebook
* Python
* Libraries:
    * pandas, numpy – Data manipulation
    * matplotlib, seaborn - Data visualization
    * scikit-learn - Machine learning
    * mlxtend - Machine learning
    * xgboost / lightgbm - Ensemble modeling
* Excel

## Featured Deliverables
* [AOT Student Mental Health Analysis Presentation](./Student%20Mental%20Health%20Analysis/Student%20Mental%20Health%20Analysis%20Presentation.pdf)
* [Final Project Codefile](./Student%20Mental%20Health%20Analysis/student%20mental%20health%20analysis.ipynb)

## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](./Student%20Mental%20Health%20Analysis/Raw%20dataset/final_project_student_mental_health_dataset.csv) within this repo.    
