# Churn Prediction in Telecom Industry

## Overview
This project aims to predict customer churn in the telecom industry using machine learning techniques. By analyzing customer behavior and service usage patterns, the model helps identify high-risk customers and provides actionable insights to improve retention strategies.

## Dataset
The dataset contains customer-related features such as tenure, monthly charges, total charges, and customer service interactions. The target variable is customer churn (Yes/No).

## Key Steps
1. **Data Preprocessing**  
   - Handled missing values and outliers.  
   - Encoded categorical variables.  
   - Scaled numerical features.
   
2. **Exploratory Data Analysis (EDA)**  
   - Identified key patterns in customer churn behavior.  
   - Visualized distributions and correlations.
   
3. **Class Imbalance Handling**  
   - Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the dataset.

4. **Model Training & Evaluation**  
   - Tested multiple models, including Logistic Regression, Decision Trees, and Random Forest.  
   - The **Random Forest model** performed best with:  
     - **Accuracy:** 92.95%  
     - **Balanced F1-score for both classes**  
   
5. **Feature Importance & Insights**  
   - Customers with **frequent customer service interactions** and **higher charges** were more likely to churn.

## Recommendations
- Improve customer service quality to reduce churn rates among frequently contacting customers.
- Evaluate pricing strategies to ensure affordability, especially for high-charge customers.
- Implement targeted retention strategies for high-risk customers identified by the model.

## Requirements
To run the notebook, install the following dependencies:
```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/churn-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd churn-prediction
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Churn_Prediction.ipynb
   ```

## Results
The trained model helps businesses identify at-risk customers and take proactive measures to retain them, reducing churn and improving revenue stability.

