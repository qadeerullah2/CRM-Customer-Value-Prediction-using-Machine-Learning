📊 CRM Customer Value Prediction using FLO Retail Data
📌 Project Overview

This project is a CRM (Customer Relationship Management) analytics solution built using Machine Learning.
The objective is to predict high-value customers based on their purchase behavior using historical retail data from FLO, a footwear and fashion retail brand.

The project demonstrates a complete end-to-end ML workflow, from data cleaning to model deployment readiness.

🎯 Business Problem

In CRM systems, not all customers contribute equally to revenue.
Identifying high-value customers helps businesses:

Improve customer retention

Run targeted marketing campaigns

Optimize sales and promotional strategies

🧠 Solution Approach

We analyze customer transaction and interaction data and apply machine learning models to classify customers as:

High Value Customer

Low Value Customer

This prediction supports data-driven decision-making in CRM systems.

🗂️ Dataset Description

The dataset contains customer-level information such as:

Customer ID

Order channels (online/offline)

First and last purchase dates

Number of orders

Total purchase value

Product category interests

📌 Note: The dataset represents real-world CRM transactional data.

🔧 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn (Data Visualization)

Scikit-learn

Google Colab (Model Training)

GitHub (Version Control)

Django (for model integration – optional extension)

⚙️ Project Workflow

Data loading and understanding

Data cleaning and preprocessing

Feature engineering (total orders, total value, recency, tenure)

Exploratory Data Analysis (EDA)

Target variable creation

Model building

Logistic Regression

Random Forest

Model evaluation

Accuracy

Classification report

Confusion matrix

ROC curve

Model export for deployment

📈 Model Performance

Logistic Regression used as a baseline model

Random Forest achieved better performance and accuracy

Final model selected based on evaluation metrics

🧩 CRM Use Case

This project can be directly used in CRM systems for:

Customer segmentation

Identifying high-value customers

Personalized marketing

Loyalty and retention strategies

🚀 Future Enhancements

Integrate with Django REST API

Build a CRM dashboard using Power BI

Add churn prediction

Deploy on cloud (AWS / Azure)

▶️ How to Run the Project

Clone the repository

git clone <repository-url>


Open the notebook in Google Colab or Jupyter

Run all cells in sequence

Train the model and export .pkl files if needed

👨‍💻 Author

Syed Qadirullah Hussaini
Full Stack Software Engineer | CRM & ML Enthusiast
