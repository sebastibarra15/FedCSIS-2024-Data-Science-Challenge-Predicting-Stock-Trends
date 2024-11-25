Predicting Stock Trends - README
=================================

Overview
--------
This project is part of the FedCSIS 2024 Data Science Challenge, which focuses on 
predicting stock trends using financial data for 300 companies across 11 sectors of 
the S&P 500 over the past 10 years. The provided dataset includes 58 financial indicators 
and their yearly changes, which can reveal trends. The goal is to develop a predictive 
model that accurately forecasts stock trend movements, providing insights for algorithmic 
or manual trading decisions.

Dataset Requirements
--------------------
The project requires the following input files:
1. `training_data.csv`:
   - Contains historical data for training the predictive model, including 58 financial 
     indicators and their 1-year changes for 300 companies.
2. `test_data_no_target.csv`:
   - Contains test data without the target variable, used to evaluate the model’s 
     ability to predict stock trends on unseen data.

Make sure both files are in the same directory as the notebook or script before running the code.

What the Code Does
------------------
1. **Data Preprocessing**:
   - Loads and cleans the training and test datasets.
   - Handles missing or inconsistent data to ensure robust analysis.
   - Normalizes or scales features for improved model performance.

2. **Feature Engineering**:
   - Extracts meaningful insights from the 58 indicators and their changes.
   - Identifies important features correlated with stock trend predictions.

3. **Model Development**:
   - Trains a predictive model using machine learning techniques.
   - Optimizes the model with cross-validation to improve accuracy.

4. **Prediction**:
   - Applies the trained model to `test_data_no_target.csv`.
   - Outputs predictions for stock trends (e.g., buy, sell, hold) in a new file.

5. **Output**:
   - Generates a CSV file containing the predictions for the test dataset.
   - Provides insights on model performance metrics such as accuracy, precision, 
     or recall (depending on implementation).

How to Run the Code
-------------------
1. Place the files `training_data.csv` and `test_data_no_target.csv` in the same 
   directory as the project.
2. Open the provided Jupyter Notebook or script:
   - If using a notebook, ensure that all dependencies are installed (e.g., pandas, 
     scikit-learn, etc.).
3. Execute the code step by step to preprocess the data, train the model, and 
   generate predictions.
4. The output CSV file with predictions will be saved in the same directory.

Required Libraries
------------------
Ensure the following Python libraries are installed before running the project:
- pandas
- numpy
- scikit-learn
- matplotlib (optional for data visualization)

Install missing libraries using pip:
```bash
pip install pandas numpy scikit-learn matplotlib
