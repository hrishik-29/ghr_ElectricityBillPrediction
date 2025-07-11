# Electricity Bill Prediction – AI/ML Hackathon

### Problem Statement
With rising electricity consumption, predicting monthly bills using appliance usage, location, and tariff data is crucial for planning and optimization. This project builds a supervised regression model to predict electricity bills from such features.

---

### Dataset
- `electricity_bill_dataset.csv`
- Contains data like appliance count, usage hours, city, company, and tariff.

---

### Approach
1. **Data Cleaning**
   - Checked for nulls and found no null values and then removed a reductant column named Motor Pump.
2. **Feature Engineering**
   - One-hot encoding for categorical features like City and Company.
3. **Model Training**
   - Tried multiple models: Linear Regression, Decision Tree, Random Forest.
   - Used GridSearchCV for tuning, but not implemented in the notebook because of time constraint and the grid search code is commented out .
4. **Evaluation**
   - Metrics: RMSE, R² Score
   - Random Forest performed the best.

---

### Results
- Best model: Random Forest
- R² Score: 0.9999748318494079
- RMSE: 5.355097450479262
- Visualizations: predicted vs actual plots, Feature Importance Plot

---

### Requirements
See `requirements.txt`

---

### Authors
- Hrishik
