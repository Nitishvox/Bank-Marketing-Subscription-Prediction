# Bank-Marketing-Subscription-Prediction

Predicting term deposit subscriptions using a Decision Tree classifier on bank customer data.  
Insightful, interpretable, and marketing-ready.

## Project Overview

This project focuses on understanding customer behavior and predicting whether a bank customer will subscribe to a term deposit product. Using Exploratory Data Analysis (EDA) and a Decision Tree Classifier, we derive insights and build a model for targeted marketing.

## Dataset

- **Source**: [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Contains attributes related to customer demographics, past marketing interactions, and bank account information.

## 📊 Key Features Explored

- Age
- Job
- Marital Status
- Education
- Account Balance
- Contact Method
- Call Duration
- Subscription Outcome (`y`)

## Key Insights from EDA

- **Imbalanced Data**: Most customers do not subscribe; needs special handling during modeling.
- **Middle-aged customers** (30–60) are more likely to subscribe.
- **Students and retired individuals** show higher subscription rates.
- **Single customers** subscribe more than married/divorced ones.
- **Cellular contact** and **longer call durations** lead to more subscriptions.
- **Higher account balances** generally correlate with successful subscriptions.

## Techniques Used

- Python (Pandas, Seaborn, Matplotlib)
- Exploratory Data Analysis (EDA)
- Decision Tree Classifier (Scikit-learn)

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/Bank-Marketing-Subscription-Prediction.git
   cd Bank-Marketing-Subscription-Prediction

