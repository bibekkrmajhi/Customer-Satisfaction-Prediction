# Customer Satisfaction Prediction

## Data Science Internship Project

### 📌 Project Overview

Customer satisfaction is a critical metric for any business.
This project focuses on analyzing customer support ticket data and building a machine learning model to predict whether a customer is Unhappy or Not Unhappy based on their support interaction.

The project follows the complete Data Science lifecycle:

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Building
5. Model Evaluation
6. Model Saving & Prediction

### 🎯 Problem Statement

Initially, customer satisfaction ratings were available on a 1–5 scale.
However, predicting exact ratings is difficult due to the subjective nature of customer feedback.

To make the solution business-friendly and practical, the problem was reframed as a binary classification task:

#### Rating	Category
**1–2	Unhappy**

**3–5	Not Unhappy**

## 🗂️ Dataset Description

The dataset contains customer support ticket information, including:
Customer demographic details
Product purchased
Ticket type, subject, priority, and channel
First response time & resolution time
Customer satisfaction rating (1–5)
Only tickets with available satisfaction ratings were used for modeling.

### 🔧 Tools & Technologies Used

- Python

- Pandas & NumPy – Data manipulation

- Matplotlib & Seaborn – Data visualization

- Scikit-learn – Machine learning

- Joblib – Model saving & loading

### 🧹 Data Preprocessing & Feature Engineering

**Key preprocessing steps:**

- Removed irrelevant columns (IDs, names, emails, text fields)

- Handled missing values

- Converted date-time columns to resolution duration (in hours)

- Applied ordinal encoding for ordered features (Ticket Priority)

- Applied one-hot encoding for non-ordered categorical features

### 📊 Exploratory Data Analysis (EDA)

**EDA was performed to understand:**

- Distribution of customer satisfaction ratings

- Relationship between ticket priority and satisfaction

- Ticket trends across different channels

- Impact of resolution time on customer satisfaction

- Visualizations such as bar plots, box plots, and histograms were used to extract insights.

### 🤖 Model Building

Model Used: Random Forest Classifier

**Why Random Forest?**

- Handles non-linear relationships well

- Works effectively with mixed feature types

- Robust to noise and outliers

- A pipeline was created to ensure preprocessing and modeling happen together.

### 📈 Model Evaluation

#### The model was evaluated using:

**Accuracy**

**Precision, Recall, and F1-Score**

**Confusion Matrix**

#### Final Result:

**Accuracy: ~57%**

The model performs significantly better than random guessing and is suitable for real-world noisy data.

Special focus was given to identifying unhappy customers, which is most important from a business perspective.

### 💾 Model Saving & Usage

The trained model was saved using joblib, allowing reuse without retraining.

The saved model can be loaded later to:

Predict satisfaction for new customer tickets

Integrate into applications or dashboards



### 🧠 Key Learnings

Importance of correct problem framing in machine learning

Handling categorical data properly (ordinal vs one-hot encoding)

Understanding why accuracy alone is not enough

Translating ML results into business-friendly insights



### 📌 Conclusion

This project demonstrates a practical application of machine learning to solve a real-world business problem.
By reframing the problem into binary classification, the solution becomes more interpretable, actionable, and aligned with industry practices.

### 👤 Author

**[Bibek Kumar Majhi]**

Machine Learning / Data Analytics Intern




