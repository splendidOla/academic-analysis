# academic-analysis
Predictive and prescriptive modeling of student academic performance. Uses Scikit-learn to identify at-risk students and provides a data-driven intervention framework based on behavioral and socio-economic features.

# Title:
A Prescriptive Framework for Predicting and Managing Student Academic Risk.

# Description:
This project moves beyond simple grade prediction to categorize student academic performance into actionable risk tiers. By analyzing the intersection of study habits, parental education, and attendance, the model identifies "at-risk" students with high precision. The core value of this work lies in its prescriptive insights, which distinguish between students who need intensive support versus those who require light-touch intervention, ensuring efficient resource allocation.

# My Contributions:
In this project, I engineered a complete machine learning pipeline that transforms raw demographic and behavioral data into a predictive engine for student outcomes. I performed a deep-dive analysis into model errors, specifically examining the characteristics of "False Negatives"—students who the model missed despite their high study hours—to reveal that effort alone is an insufficient predictor of success. I developed a classification framework using Logistic Regression and Random Forest, achieving high validation accuracy. Furthermore, I translated these statistical findings into strategic recommendations, advocating for personalized learning plans and diagnostic assessments rather than one-size-fits-all academic support.

# Methodology:
Socio-economic feature encoding, behavioral correlation analysis, supervised classification modeling (Logistic Regression, Decision Trees, Random Forests), hyperparameter optimization via GridSearchCV, and error analysis of false positives vs. false negatives.

# Tools Used:
Python, Scikit-learn, Pandas, NumPy, Seaborn, and Matplotlib.


# Key Features
1. Multi-Algorithmic Approach: Evaluates Logistic Regression, Decision Trees, and Random Forests to ensure the most robust prediction of academic success.
2. Strategic Error Analysis: Specifically analyzes "False Negatives" to understand why high-effort students (those with high study hours) might still be at risk.
3. Actionable Insights: Recommends "light-touch" workshops for false positives and "intensive diagnostic" coaching for false negatives to maximize institutional resources.
4. Feature Importance: Highlights the critical roles of attendance and parental education over sheer study hours in predicting final outcomes.
