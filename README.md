
🏠 House Price Prediction Using Machine Learning
A Machine Learning project that predicts house prices using the
California Housing Dataset and Linear Regression.  
This project demonstrates the complete machine learning workflow
including data loading, preprocessing, model training, evaluation, and
visualization using Python.
---
📌 Project Overview
House price prediction is a common regression problem in machine
learning.  
In this project, a Linear Regression model is trained to predict
house prices based on several housing-related features such as income,
house age, population, and geographic location.
This project helps understand:
Supervised Machine Learning
Regression Models
Model Evaluation Metrics
Data Visualization
---
🧰 Technologies Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn
VS Code
---
📊 Dataset
The project uses the California Housing Dataset available in
Scikit-Learn.
Features
Feature      Description
---
MedInc       Median income of households
HouseAge     Median house age
AveRooms     Average number of rooms
AveBedrms    Average number of bedrooms
Population   Population in the area
AveOccup     Average occupancy
Latitude     Latitude location
Longitude    Longitude location
Target Variable:  
House Price
---
⚙️ Machine Learning Workflow
Load the California Housing Dataset
Convert dataset into a Pandas DataFrame
Split dataset into training and testing sets
Train a Linear Regression model
Predict house prices using test data
Evaluate model performance
Visualize Actual vs Predicted Prices
---
📈 Model Evaluation
The model performance is measured using:
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score
Example Output:
    MAE: 0.533
MSE: 0.556
RMSE: 0.746
R2 Score: 0.575

---
📉 Visualization
The project generates a scatter plot comparing Actual vs Predicted
house prices.
X-axis: Actual Price\
Y-axis: Predicted Price
This visualization helps evaluate how closely the predictions match the
real values.
---
📂 Project Structure
    house_price_prediction/
│
├── house_price_prediction.py
├── README.md
└── output_graph.png

---
🚀 How to Run the Project
1️⃣ Clone the repository
    git clone https://github.com/yourusername/house-price-prediction.git

2️⃣ Install dependencies
    pip install numpy pandas matplotlib scikit-learn

3️⃣ Run the project
    python house_price_prediction.py

---
🎯 Learning Outcomes
Through this project you will learn:
Basics of Machine Learning Regression
Data preprocessing with Pandas
Training models using Scikit-Learn
Evaluating regression models
Visualizing predictions using Matplotlib
---
🔮 Future Improvements
Possible improvements:
Use Random Forest Regressor
Use Gradient Boosting
Improve feature engineering
Increase model accuracy
Build a Streamlit Web App
---
👨‍💻 Author
Hemaksha Sharma  
Machine Learning Beginner | Python Developer
