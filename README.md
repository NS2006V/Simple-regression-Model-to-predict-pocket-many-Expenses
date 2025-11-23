💸 Pocket Money Expense Predictor (Shiny App)

A simple and interactive R Shiny application that predicts monthly pocket money expenses based on a student's Income, Age, and Savings using a Multiple Linear Regression Model.

✨ Features

📂 Upload CSV dataset

📉 Scatter plot showing Income vs Expenses

📑 Model Summary of the regression model

📊 Model Evaluation Metrics (RMSE & R-Squared)

🔮 Predict expenses for new input values

⚡ Real-time Shiny interface

🧠 How It Works

The regression model used is:

Expenses ~ Income + Age + Savings


The user uploads a dataset with the following columns:

Income

Age

Savings

Expenses

Shiny dynamically:

Builds a regression model

Shows evaluation metrics

Plots the income-to-expense relationship

Predicts new expenses

📂 Required CSV Format

Your CSV file must include these columns:

Income, Age, Savings, Expenses


Example:

Income	Age	Savings	Expenses
1500	16	200	900
1800	17	300	1100
▶️ Running the App

Install necessary libraries:

install.packages(c("shiny", "ggplot2", "dplyr"))


Run the app:

shiny::runApp("app.R")


(Make sure the code you shared is saved inside app.R)

📊 App UI Preview

Scatter Plot: Income vs Expense

Model Summary: Coefficients, p-values, residuals

Metrics: RMSE & R²

Prediction Panel: Enter new values → Get estimated expenses

🛠️ Technology Used

R

Shiny

ggplot2

dplyr

Linear Regression

📄 License

This project is licensed under the MIT License.

👤 Author

Nekashri S
AI & Data Science Student
K. Ramakrishnan College of Technology
