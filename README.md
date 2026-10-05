# Adult Income Prediction Project

- Checked the data, looked at distributions and missing values
- Cleaned the data and fixed missing data
- Made some new features to make the data easier for the model to understand:
  - Age groups 
  - Education groups
  - Marital status groups
  - Work hours categories
- Turned categorical data into numbers with one-hot and ordinal encoding
Used different models like logistic regression, RFC, and KNN, but I only ran the logistic regression, because using the other models for this dataset would require optimizing them with methods like random grid search or data sampling. Since this project is just for learning purposes, I didn’t do those.
- Checked which paramaters works best with cross validation and made everything in a pipeline

---

## Results
- Best model: **Logistic Regression(The only one I ran)** (accuracy: 0.8332746196063681)

