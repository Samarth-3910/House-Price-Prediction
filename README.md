# 🏠 House Price Prediction

This project is about predicting house prices using a **simple linear regression model** that I built **from scratch** (without using machine learning libraries like Scikit-Learn).

---

## 📌 What I Did
- **Loaded the dataset** – Used a CSV file with house details like area, location, and garage availability.  
- **Cleaned the data** – Removed unnecessary columns like `Id` and checked for missing values.  
- **Converted text data to numbers** – Changed `Garage: Yes/No` to `1/0` and applied **One-Hot Encoding** for categorical columns like `Location` and `Condition`.  
- **Prepared features and target** – Used **Area** as the input (X) and **Price** as the output (y).  
- **Built Linear Regression from scratch** – Implemented **gradient descent manually** to find the best slope (`m`) and intercept (`b`) for the price prediction line.  
- **Visualized results** – Plotted how the **loss (error) decreased** over epochs and drew the **line of best fit**.

---

## 🎯 Why I Made This Project
This is one of my first machine learning projects, and I wanted to understand the **math behind linear regression** instead of just using a library. It helped me learn how models actually “learn” by adjusting parameters step by step.

---

## 🛠️ Technologies Used
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**

---

## 🚀 How to Run
1. Clone the repository.  
2. Install the required libraries:  
   ```bash
   pip install numpy pandas matplotlib
