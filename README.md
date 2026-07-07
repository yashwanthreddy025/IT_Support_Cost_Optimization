# IT Support Cost Optimization Using Data Analysis

## Project Overview
This project analyzes IT support ticket data to identify cost-saving opportunities and improve operational efficiency using data analysis and machine learning.

## Objective
- Analyze IT support ticket data
- Handle missing values (20% missing data)
- Perform Exploratory Data Analysis (EDA)
- Predict ticket support cost using Machine Learning
- Generate business insights

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

## Dataset
The project uses a synthetic dataset of 10,000 IT support tickets with the following fields:
- Ticket ID
- Issue Category
- Priority
- Resolution Time
- Engineer Cost
- Client Type
- Escalation Count
- Customer Rating

## Project Workflow
1. Generated a synthetic dataset.
2. Cleaned missing values using the median.
3. Performed Exploratory Data Analysis (EDA).
4. Created a new feature: Total Cost.
5. Trained a Random Forest Regressor to predict support costs.
6. Evaluated the model using MAE, RMSE, and R² Score.

## Business Insights
- Resolution Time has the greatest impact on support cost.
- High-priority tickets generally cost more.
- Enterprise clients tend to require higher support costs.
- Reducing resolution time can reduce annual support expenses.
- Better ticket routing can minimize escalations.

## Repository Structure

```text
IT-Support-Cost-Optimization/
│
├── data/
│   └── support_tickets.csv
├── notebooks/
│   └── IT_Support_Cost_Optimization.ipynb
├── models/
│   └── cost_prediction_model.pkl
├── README.md
├── requirements.txt
└── .gitignore
```

## Future Improvements
- Interactive dashboard using Streamlit
- Real-time prediction API
- Automated ticket routing system