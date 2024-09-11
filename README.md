# SpaceTitanic

- Exploratory Data Analysis, Data Visualization and Model Training on the Space Titanic Dataset from Kaggle.
- Accuracy: 0.80547, Top 10% among submissions.

- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, LightGBM, XGBoost
- Final Model composes of:
  - Preprocessor with:
    
    - Various types of imputing
    - Unpacking and encoding categorical columns
    - Scaling and normalizing numerical columns
  - KBest with 22 best features according to their chi2 score
  - Gradient Booster with 600 Estimators, Learning Rate(Alpha) of 0.01, Max Depth of 14
