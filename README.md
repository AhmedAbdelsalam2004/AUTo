# 🚗 Auto MPG Prediction

A machine learning project for predicting **automobile fuel efficiency (MPG)** using regression techniques on the **UCI Auto MPG dataset**.  
The project is implemented in a Jupyter Notebook (`Auto_mpg.ipynb`) and demonstrates the complete data science workflow — from data preprocessing to model evaluation.

---

## 📘 Overview

The goal of this project is to predict a car's **miles per gallon (MPG)** based on various features such as:
- Cylinders  
- Displacement  
- Horsepower  
- Weight  
- Acceleration  
- Model year  
- Origin  

This dataset is a popular benchmark for regression algorithms and helps illustrate how feature relationships impact vehicle fuel efficiency.

---

## 💾 Dataset Description

**Source:** [UCI Machine Learning Repository – Auto MPG Dataset](https://archive.ics.uci.edu/ml/datasets/auto+mpg)

| Feature | Description | Type |
|----------|--------------|------|
| `mpg` | Miles per gallon (target variable) | Continuous |
| `cylinders` | Number of cylinders | Integer |
| `displacement` | Engine displacement (cu. inches) | Continuous |
| `horsepower` | Engine horsepower | Continuous |
| `weight` | Vehicle weight (lbs) | Continuous |
| `acceleration` | Time to accelerate from 0–60 mph (s) | Continuous |
| `model year` | Year of manufacture | Integer |
| `origin` | Origin of car (1: USA, 2: Europe, 3: Japan) | Categorical |

---

## ⚙️ Installation & Setup

To run this project locally:

### Clone the repository
git clone https://github.com/<your-username>/Auto_mpg.git

### Navigate to the project folder
cd Auto_mpg

### Install dependencies
pip install -r requirements.txt

### Launch Jupyter Notebook
jupyter notebook Auto_mpg.ipynb
Recommended environment:
Python 3.8+
Jupyter Notebook or JupyterLab

### Common dependencies:

text
Copy code
pandas
numpy
matplotlib
seaborn
scikit-learn
## 🧠 Model Training
The notebook walks through:

Data Cleaning & Preprocessing

Handling missing values in horsepower

Encoding categorical features

Exploratory Data Analysis (EDA)

Correlation heatmaps

Feature distributions

Model Building

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Evaluation

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

## 📈 Results & Evaluation
Model	MAE	MSE	R² Score
Linear Regression	example 2.3	example 10.4	example 0.82
Random Forest	example 1.7	example 7.1	example 0.89

(Replace “example” values with your actual results.)

Visualizations include:

Predicted vs. Actual MPG plot

Feature importance ranking

Residual analysis

## 🚀 How to Run
You can open the notebook in Jupyter Notebook or Google Colab:

Open in Google Colab

Simply execute the cells sequentially to reproduce all results and plots.

## 📊 Visual Results
Below are screenshots from the model training and result visualization phases:
<img width="719" height="713" alt="image" src="https://github.com/user-attachments/assets/f1d67fcb-5547-42d2-a5c6-df7060332e98" />


## 📚 References
UCI Machine Learning Repository: Auto MPG Data Set

Scikit-learn Documentation

Pandas Documentation

👨‍💻 Author
Ahmed Abdelsalam
Systems & Biomedical Engineer, Cairo University
Passionate about Embedded Systems and Machine Learning
