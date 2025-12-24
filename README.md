# Diamond Price Prediction using KNN (From Scratch)
## Machine Learning Project | Regression | Algorithm Implementation
This project demonstrates a from-scratch implementation of the K-Nearest Neighbors (KNN) regression algorithm to predict diamond prices. The model is validated by comparing results with sklearn’s KNN, showcasing strong fundamentals in machine learning, data preprocessing, and model evaluation.

## What This Project Demonstrates (For Recruiters)
- Strong understanding of ML algorithms (KNN)
- Ability to build algorithms from scratch (no black-box usage)
- Real-world data preprocessing & feature engineering
- Model evaluation and performance comparison
- Clean, modular, and readable Python code
- Hands-on experience with sklearn, Pandas, NumPy

## Objective
- To design and implement a KNN regression model from scratch for predicting diamond prices, apply appropriate preprocessing techniques, and compare its performance with sklearn’s KNN model.

## Files
- <a href="https://github.com/Shareef1827/KNN-Implementation/blob/main/README.md"> ReadME </a>
- <a href="https://github.com/Shareef1827/KNN-Implementation/blob/main/Task%20-%20KNN%20from%20scratch.docx"> Task Document </a>
- <a href="https://github.com/Shareef1827/KNN-Implementation/blob/main/diamonds.csv"> Diamond Dataset </a>
- <a href="https://github.com/Shareef1827/KNN-Implementation/blob/main/KNN%20Implementation%20from%20Scratch.ipynb"> Jupyter Code File </a>

## Dataset Overview
- Dataset: Diamonds dataset
- Target Variable: price
- Features:
  Numerical: carat, depth, table, x, y, z
  Categorical: cut, color, clarity

## Project Workflow
1. Load and explore the dataset
2. Define input features (X) and target (y)
3. Split data into training and testing sets (75:25)
4. Preprocess training data
- Encode categorical variables
- Scale numerical features
5. Apply identical preprocessing to test data
6. Implement KNN from scratch
- Distance calculation (Euclidean)
- Neighbor selection
- Prediction logic
7. Evaluate model performance
8. Train sklearn KNN model
9. Compare results and analyze differences

## Tech Stack & Tools
- Programming: Python
- Libraries: NumPy, Pandas, Scikit-learn
- Visualization: Matplotlib, Seaborn
- Environment: Jupyter Notebook

## Model Evaluation
Evaluation metrics used to measure regression performance:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Result:
The scratch KNN model produced results closely aligned with sklearn’s KNN, confirming the correctness of the implementation.

## Key Learnings
- How distance-based algorithms work internally
- Importance of feature scaling in KNN
- Handling categorical and numerical features together
- Performance trade-offs in brute-force KNN
- Writing production-readable ML code

## Conclusion
The scratch implementation of KNN produced results comparable to sklearn’s implementation, validating the correctness of the algorithm and reinforcing core machine learning concepts.
