# EasyVisa Case Study: Visa Application Prediction

## Business Problem
To facilitate the visa approval process by predicting the outcome of visa applications using the historical data from previous visa applications. This helps both the applicants and the visa processing system to preemptively identify visa applications that have a higher chance of approval or denial.

## Dataset Description
- Dataset contains information about visa applications
- Features include case status, continent, education level, occupation
- Target variable: Visa application status (Certified/Denied)
- Time period: 2011 to 2016

## Technical Approach
1. Data Preprocessing
   - Handling missing values
   - Feature engineering
   - Encoding categorical variables

2. Model Development
   - Random Forest Classifier
   - XGBoost
   - Support Vector Machine

3. Model Evaluation
   - Cross-validation
   - ROC-AUC scoring
   - Confusion matrix analysis

## Key Insights
- Wage rate type significantly impacts visa approval chances
- Certain job categories have higher approval rates
- Education level correlates with visa approval probability

## Solution Files
- EasyVisa_Solution.html: Detailed solution notebook
- data/EasyVisa.csv: Dataset file

## Technologies Used
- Python 3.x
- Scikit-learn
- Pandas
- NumPy
- Matplotlib/Seaborn
- XGBoost
