# Customer Support Ticket Analysis and Satisfaction Prediction

## Project Overview

This project analyzes customer support ticket data and uses Machine Learning to predict Customer Satisfaction Rating.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Logistic Regression
* Exploratory Data Analysis (EDA)
* Data Preprocessing

## Project Workflow

1. Load the customer support ticket dataset
2. Perform Exploratory Data Analysis
3. Check missing values
4. Remove unnecessary columns
5. Handle missing Customer Satisfaction Rating values
6. Check duplicate records
7. Encode categorical features using Label Encoding
8. Split the dataset into training and testing data
9. Train a Logistic Regression model
10. Evaluate the model using Accuracy

## Machine Learning Model

**Algorithm:** Logistic Regression

The dataset is split into:

* 70% Training Data
* 30% Testing Data

## Evaluation

The model prediction is evaluated using Accuracy Score.

## Project Structure

```text
customer-support-ticket-ml/
│
├── customer_support_ticket_prediction.py
├── customer_support_tickets.csv
├── requirements.txt
└── README.md
```

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then run:

```bash
python customer_support_ticket_prediction.py
```
