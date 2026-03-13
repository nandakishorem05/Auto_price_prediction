🚗 Automobile Price Prediction

A Machine Learning project that predicts the price of automobiles based on different car features such as engine size, fuel type, horsepower, dimensions, and other specifications.

This project performs Exploratory Data Analysis (EDA) and builds a predictive model to understand which factors influence car prices the most.

📌 Project Overview

Car prices vary depending on many technical and design factors such as:

Engine performance

Fuel system

Vehicle dimensions

Number of cylinders

Drive wheels

Body style

This project analyzes these attributes and uses machine learning techniques to predict the price of a car.

🎯 Problem Statement

The goal of this project is to:

Perform Exploratory Data Analysis (EDA) on automobile data.

Identify key features affecting car prices.

Build a machine learning model that predicts the price of automobiles.

📊 Dataset Description

The dataset contains various specifications of cars used to determine their prices.

Target Variable

Price – The selling price of the automobile.

📥 Important Features
Car Information

Carname

Symboling

Engine Details

Engine_type

Engine_location

Cylinders_num

Horsepower

Enginesize

Fuel System

Fueltype

Fuelsystem

Aspiration

Car Body

Body_style

Door_num

Drive_wheels

Vehicle Dimensions

Length

Width

Height

Wheelbase

Performance

City_mpg

Highway_mpg

🔎 Exploratory Data Analysis

Several visualizations were used to understand the dataset:

Price Distribution

Car Name vs Price

Fuel Type vs Price

Body Style vs Price

Engine Type vs Price

Cylinders vs Price

Fuel System vs Price

Vehicle Dimensions vs Price

Libraries used for visualization:

Matplotlib

Seaborn

⚙️ Project Workflow
1️⃣ Data Loading

Load the automobile dataset using Pandas.

2️⃣ Basic Data Checks

Check missing values

Check duplicate values

Understand dataset structure

3️⃣ Exploratory Data Analysis

Analyze relationships between car features and price using plots.

4️⃣ Feature Analysis

Identify features that strongly affect car price.

5️⃣ Model Building

Use machine learning algorithms to predict car prices.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

📂 Project Structure
Auto-Price-Prediction
│
├── Auto_price_pred.ipynb
├── automobile.csv
├── README.md
▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/yourusername/auto-price-prediction.git
2️⃣ Install Required Libraries
pip install pandas numpy matplotlib seaborn scikit-learn
3️⃣ Run the Notebook

Open the notebook in Jupyter Notebook or Google Colab

Auto_price_pred.ipynb
📈 Key Insights

Some important factors affecting car prices include:

Engine size

Horsepower

Number of cylinders

Car dimensions

Fuel system

Drive wheels

Cars with larger engines and more cylinders generally have higher prices.

🚀 Future Improvements

Possible improvements for the project:

Feature engineering

Hyperparameter tuning

Try advanced models (Random Forest, XGBoost)

Deploy the model using Flask or Streamlit

Create a web app for car price prediction


👨‍💻 Author

Nandakishore M
Data Science Student

GitHub: https://github.com/nandakishorem05
