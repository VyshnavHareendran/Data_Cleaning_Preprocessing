# Titanic Dataset Cleaning & Preprocessing

This project performs professional-level data cleaning and preprocessing on the Titanic dataset, preparing it for machine learning tasks such as survival prediction.

Dataset:
- [Kaggle Titanic Dataset]([https://www.kaggle.com/datasets/yasserh/titanic-dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset))
- Passenger information including age, class, fare, sex, and survival status.

Key Steps
- Data loading and initial inspection
- Handling missing values:
  - Group-wise median imputation for Age
  - Mode imputation for Embarked
- Outlier detection and capping (Age, Fare)
- Encoding categorical variables (One-Hot Encoding)
- Feature scaling
- Correlation analysis of numeric features
- Saving both raw and cleaned datasets to Google Drive

  Tools & Libraries
- Python 3
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Google Colab
- Google Drive Integration

  Conclusion
This project ensures a clean, ready-to-use version of the Titanic dataset by addressing missing values, outliers, and categorical variables, following industry-standard preprocessing techniques.
