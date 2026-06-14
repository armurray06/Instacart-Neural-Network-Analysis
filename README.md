# Instacart Neural Network Analysis

# Instacart Predictive Analysis: Neural Network Implementation and Scenario Simulation
# Project Overview
# This project delivers a predictive analytics pipeline designed to optimize consumer reorder forecasting for the Instacart platform. By changing from a baseline linear model to a Multi Layer Perceptron (MLP) neural network, this research models complex nonlinear shopping habits to find out whether an item added to a cart is a routine order or a new one. 

# The project combines machine learning classification, Apriori market basket association rule mining, and scenario simulation pictured through an interactive Tableau dashboard.

# Key Findings & Results
# Model Optimization Uplift: The baseline Logistic Regression model achieved an accuracy of 69.14%. However, through hyperparameter tuning and layer optimization, the MLP Neural Network raised predictive accuracy to 71.29%.
# High Loyalty Sensitivity: The neural network successfully balanced precision and recall metrics, boosting Class 1 (Reordered Items) recall to 0.84, showing its better capability in capturing routine consumer loyalty.
# Market Basket Affinities: Apriori data mining isolated product affinities at the department level. Highly correlated groupings such as "Dry Goods, Canned Goods, Pantry Essentials" and "Frozen, Bakery, Snacks" and achieved peak Lift scores of 4.10, proving that cross purchasing is driven heavily by certain cooking styles and meal preparation habits.
# Scenario Simulation Impact:
  # Baseline: 71.29% reorder probability.
  # Scenario 1 (Mid day Operational Surge): Rose to 76.40% reorder probability.
  # Scenario 2 (High Lift Promo Bundles): Peak performance at 81.15% reorder probability, +9.86% lift.
  # Scenario 3 (Late Night Off Peak Drop): Declined to 52.30% reorder probability, validating the "impulse buy" nature of off peak/late shopping hours.

---

# Project Dependencies & Environment
# To run the Jupyter Notebook analysis locally, ensure the following libraries installed: pip install pandas numpy scikit-learn tensorflow matplotlib seaborn mlxtend
