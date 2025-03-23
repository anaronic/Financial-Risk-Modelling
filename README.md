# Financial-Risk-Modelling

## Overview
This project focuses on financial risk modeling using credit data from the Bank of Baroda. The primary objective is to analyze internal product files and CIBIL reports, clean and preprocess the data, and apply machine learning techniques to assess credit risk.

## Dataset
- **Case Study 1**: Internal product file (Bank of Baroda)
- **Case Study 2**: CIBIL report for the same dataset

## Steps Involved
### 1. Data Preprocessing
- Uploading and loading the datasets
- Cleaning missing values (e.g., removing rows with excessive null values)
- Merging datasets based on common parameters
- Handling imbalanced data

### 2. Exploratory Data Analysis (EDA)
- Statistical summary of features
- Visualizations to identify trends and correlations
- Checking for multicollinearity using Variance Inflation Factor (VIF)

### 3. Machine Learning Model
- Splitting the dataset into training and testing sets
- Implementing a **Random Forest Classifier**
- Evaluating performance using:
  - Accuracy Score
  - Precision, Recall, and F1-score
  - Classification Report

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install numpy pandas matplotlib scikit-learn statsmodels
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/Financial-Risk-Modelling.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Financial-Risk-Modelling
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Credit_Modelling_Project_BOB.ipynb
   ```

## Results
- The model's predictions on credit risk classification
- Insights derived from data analysis
- Potential areas for further optimization

## Future Enhancements
- Implementing additional ML models (Logistic Regression, XGBoost, etc.)
- Enhancing feature engineering
- Deploying the model as a web application

## Contributors
- [Your Name](https://github.com/your-profile)

## License
This project is licensed under the MIT License.

