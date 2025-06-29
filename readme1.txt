🚢 Titanic Data Preprocessing
This project demonstrates a full preprocessing pipeline on the Titanic dataset for machine learning.

✅ Steps Performed
Handled Missing Values:
Filled Age with mean, Embarked with mode, Fare with median and drop null values using dropna().
Encoded Categorical Features:
Used one-hot encoding for Sex and Embarked.
Standardized Numerical Features:
Scaled Age, Fare, SibSp, Parch, Pclass using StandardScaler.

Removed Outliers:
Applied IQR method after visualizing with boxplots.

🎯 Result
Cleaned, encoded, and normalized dataset ready for ML modeling.

🛠️ Tools Used
Python, Pandas, Scikit-learn, Seaborn, Matplotlib
