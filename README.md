Project Description: House Price Prediction
This project is about predicting house prices using a very simple linear regression model that I built from scratch (without using machine learning libraries like Scikit-Learn).

What I did in this project:

1. Loaded the dataset – I used a CSV file that contains house details like area, location, garage availability, etc.

2. Cleaned the data – I removed unnecessary columns like Id and checked for missing values.

3. Converted text data to numbers – For example, I changed Garage: Yes/No to 1 or 0, and used One-Hot Encoding for columns like Location and Condition.

4. Prepared features and target – I used Area as the input (X) and Price as the output (y).

5. Built Linear Regression from scratch – I implemented gradient descent by hand to find the best slope (m) and intercept (b) for the price prediction line.

6. Visualized results – I kept track of how the loss (error) decreases during training, and plotted the line of best fit.

Why I made this project?
This is one of my first machine learning projects, and I wanted to understand the math behind linear regression instead of just using a library. It helped me learn how models actually “learn” by adjusting parameters step by step.
