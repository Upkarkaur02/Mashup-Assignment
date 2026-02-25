Title: Data Generation using Modelling and Simulation
1. Introduction:
   Machine Learning models require large and well-structured datasets. However, real-world data is often unavailable, expensive, or time-consuming to collect.

To overcome this limitation, modelling and simulation can be used to generate synthetic datasets that resemble real-world behavior.

In this project, we use:

🔹 SimPy

SimPy is a Python-based discrete-event simulation library used for modeling queue systems, manufacturing systems, network traffic, and other dynamic processes.
2. Problem Statement:
  We simulate a Single Server Queue System (M/M/1 model) and generate synthetic data using different system parameters.
  The goal is:

  - Generate 1000 simulation runs
  
  - Create a dataset
  
  - Apply multiple ML models
  
  - Compare their performance
  
  - Identify the best performing model

3. Simulation model Description:
   We implemented an M/M/1 queue system with:
   - Random customer arrivals

  - Single service counter
  
  - Exponentially distributed service time

4. ML Models Used:
   We trained and compared the following regression models:

  1. Linear Regression
  
  2. Decision Tree Regressor
  
  3. Random Forest Regressor
  
  4. Support Vector Regressor (SVR)
  
  5. K-Nearest Neighbors (KNN)
  
  6. Gradient Boosting Regressor
  
  7.Neural Network (MLP Regressor)

All models were trained using an 80–20 train-test split.
5. Evaluation Metrices: 
  - Mean Squared Error (MSE)
  - R² Score (Coefficient of Determination)
6. Best Model
  - Rando, forest Regressor
7. Result:

<img width="548" height="321" alt="image" src="https://github.com/user-attachments/assets/d6c2744b-ce60-4f3c-a385-ac6aae973b9e" />
- Visualization Result:
  
  <img width="644" height="508" alt="image" src="https://github.com/user-attachments/assets/f30ff561-e182-4b27-9891-9bf4eeded2c7" />
  
8. Live Link:
   
  https://colab.research.google.com/drive/1pbEZUWIfAXHLtBZHe3o2BmY0Z3AHbjjz#scrollTo=ya_krEc4aMz9
