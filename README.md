 # 🧠 TrendFit

> A simple linear regression model to predict student placement packages based on CGPA.

This project implements a simple linear regression model from scratch to predict the salary package of a student based on their CGPA.

---

## ✒️ Author

- **Aditya Sinha**
---

## 📝 Project Overview

The goal of this project is to build a predictive model that can estimate a student's potential salary package using simple linear regression.

### Key Steps:
1. Loading and exploring the dataset  
2. Visualizing the relationship between CGPA and package  
3. Splitting the data into training and testing sets  
4. Training a custom-built linear regression model  
5. Evaluating the model using metrics like MAE, MSE, RMSE, and R² Score

---

## 📊 Dataset

The model is trained on the `placement.csv` dataset (located in the `DataSet/` directory), which contains:

- `cgpa`: The Cumulative Grade Point Average of the student  
- `package`: The salary package offered (in LPA - Lakhs Per Annum)

---

## 🏁 Getting Started

To run this project, you'll need Python and Jupyter Notebook installed.

### ✅ Prerequisites

Install necessary libraries using pip:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
