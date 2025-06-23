# Crickcast
🏏 T20 Match Winner Prediction using Boosting Algorithms
This project presents a machine learning approach to predict T20 cricket match winners using boosting algorithms and advanced feature engineering. The model leverages multi-source datasets encompassing batsman, bowler, game, and match-level statistics to forecast outcomes with improved accuracy.

🚀 Project Highlights
Developed a robust ML pipeline using boosting algorithms like LightGBM and XGBoost.

Engineered 10+ features using secondary datasets such as:

Win percentages

Average runs

Player-specific and team-level performance metrics

Employed comprehensive feature selection techniques:

Recursive Feature Elimination (RFE)

Principal Component Analysis (PCA)

Final model fine-tuned with Random Forest Classifier for evaluation and comparison.

Achieved:

📈 59.07% accuracy with LightGBM

🥈 Outperformed XGBoost, which achieved 56.01% accuracy

📊 Dataset Overview
The dataset used combines multiple sources with data categorized into:

🧍 Batsman-level statistics

🎯 Bowler-level performance

🏟️ Match and game context data

📁 3 Secondary datasets for enhanced feature generation

🧠 Model Pipeline
Data Cleaning & Preprocessing

Null handling, categorical encoding, normalization

Feature Engineering

Constructed custom features capturing contextual and performance metrics

Integrated secondary datasets to enrich data quality

Modeling Techniques

LightGBM (final model)

XGBoost (baseline)

Random Forest (benchmark)

RFE & PCA for dimensionality reduction and feature selection

Evaluation

Accuracy comparison between boosting models

Confusion matrices, classification reports, and visualizations
