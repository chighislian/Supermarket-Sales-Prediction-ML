# 🛒 Supermarket Sales Prediction System

## 📌 Project Overview

This project builds a machine learning model to predict total sales per transaction for a supermarket.

Accurate sales forecasting helps improve:

    •	Inventory management
	•	Staffing decisions
	•	Revenue planning
	•	Business strategy

The model was trained using a public dataset from Kaggle and evaluated using multiple regression algorithms.



## 📊 Dataset
	•	Source: Supermarket Sales Dataset (Kaggle)
	•	Features include:
	•	Branch
	•	City
	•	Customer type
	•	Gender
	•	Product line
	•	Unit price
	•	Quantity
	•	Payment method
	•	Date & Time
	•	Tax
	•	Rating
	•	Target Variable:
	•	Total Sales



## 🔍 Data Preprocessing

The following steps were performed:

	•	Checked for missing values
	•	Converted categorical variables using One-Hot Encoding
	•	Branch
	•	City
	•	Customer type
	•	Gender
	•	Product line
	•	Payment
	•	Split dataset into training and testing sets
	•	Feature scaling where necessary



## 🤖 Models Used

The following regression models were trained and evaluated:

	•	Linear Regression
	•	Random Forest Regressor

Random Forest was used for feature importance analysis to understand which variables most influence total sales.



## 📈 Model Evaluation

Performance was evaluated using:

	•	Mean Absolute Error (MAE)
	•	Mean Squared Error (MSE)
	•	R² Score

The Random Forest model showed strong predictive performance and captured nonlinear relationships in the dataset.



## 📊 Feature Importance

Random Forest feature importance was visualized to identify key drivers of total sales.

Important features included:

	•	Quantity
	•	Unit Price
	•	Product Line
	•	Payment Method

This helps the supermarket understand what factors most impact revenue.



## 🛠 Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Scikit-learn
	•	Matplotlib
	•	Jupyter Notebook



## 📂 Project Structure
````
supermarket-sales-prediction/
│
├── data/
├── notebook.ipynb
├── model_training.py
├── README.md
````
## 🚀 How to Run the Project
### 1.	Clone the repository
### 2. Install dependencies
	
````
pip install pandas numpy scikit-learn matplotlib
````
### 3. Open Jupyter Notebook 
### 4.  all cells



## 💡 Future Improvements
	•	Deploy as a web app (Streamlit or Django)
	•	Add hyperparameter tuning
	•	Try Gradient Boosting / XGBoost
	•	Add time-series forecasting for daily revenue prediction


## 🎯 Business Impact

This project demonstrates how machine learning can:

	•	Improve operational efficiency
	•	Support data-driven decisions
	•	Increase profitability