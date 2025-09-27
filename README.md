💳 Fraud Detection using Machine Learning
📌 Project Overview

This project demonstrates fraud detection using various machine learning algorithms.
The dataset contains details of credit card transactions, and the goal is to classify whether a transaction is Fraudulent (IsFraud = 1) or Genuine (IsFraud = 0).

👉 Fraud detection is highly important in the banking & finance industry to prevent monetary losses and enhance customer trust.

🛠️ Technologies Used

🐍 Python

📊 Pandas → Data manipulation

🔢 NumPy → Numerical operations

🎨 Matplotlib / Seaborn → Data visualization

🤖 Scikit-learn (sklearn) → Machine learning models (Logistic Regression, Random Forest, Gradient Boosting, etc.)

📂 Dataset

The dataset includes transaction details such as:

TransactionID → Unique transaction identifier

Amount → Transaction amount

Time → Timestamp of transaction

Location → City/Region of transaction

MerchantCategory → Type of merchant (Groceries, Electronics, Travel, Entertainment, etc.)

CardHolderAge → Age of the cardholder

IsFraud → Target variable (1 = Fraud, 0 = Genuine)

🔑 Steps Involved
1️⃣ Data Loading & Exploration

Loaded dataset using pandas

Performed exploration with .head(), .info(), .describe()

2️⃣ Exploratory Data Analysis (EDA)

Distribution of Transaction Amounts

Most frequent Merchant Categories

Transactions per Location

Fraud vs Non-Fraud imbalance visualization

Time-series analysis of transactions

3️⃣ Data Preprocessing

Removed missing values

Applied OneHotEncoding on categorical features (Location, MerchantCategory)

Feature scaling on Amount & CardHolderAge

Train-Test split

4️⃣ Model Training

Trained and evaluated multiple ML models:

Logistic Regression

Naive Bayes (Gaussian, Multinomial, Bernoulli)

Decision Tree Classifier

Random Forest Classifier

Gradient Boosting Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

5️⃣ Model Evaluation

Accuracy

Precision, Recall, F1-score

Confusion Matrix

📊 Results & Insights

Certain locations & merchant categories showed higher fraud risk

Fraudulent transactions often had unusual amounts & timings

Ensemble models like Random Forest & Gradient Boosting gave better accuracy compared to simple models


✨ Author
Aman Mani Tripathi
📍 Data Science Enthusiast | Machine Learning
