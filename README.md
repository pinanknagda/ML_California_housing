California Housing Price Prediction 🏠

A machine learning project that predicts housing prices in California using various ML algorithms, with Support Vector Regression (SVR) emerging as the champion!
Project Overview
This project analyzes California housing data to predict median house values. The dataset includes features like:
Location (latitude, longitude)
Housing characteristics (rooms, bedrooms, age)
Population metrics
Income levels
Ocean proximity

Features & Data Processing
The pipeline includes several smart preprocessing steps:
Missing Value Handling: Median imputation for numerical features and most frequent value for categorical features
Feature Engineering:
Room-to-bedroom ratios
Population-to-household ratios
Geographic clustering for location-based features
Log transformation of income features
Scaling: StandardScaler for numerical features
Categorical Encoding: OneHotEncoder for categorical variables

Model Selection
Experimented with multiple algorithms:
Decision Trees
Linear Regression
Random Forest
Support Vector Regression (SVR)
SVR emerged as the best performer with optimized hyperparameters:
Kernel: RBF
C: 157055.11
Gamma: 0.2650

Dependencies
pandas
scikit-learn
numpy
pathlib
urllib
tarfile

Future Improvements
Add more feature engineering techniques
Experiment with ensemble methods
Add visualization of predictions vs actual values
Feel free to fork, experiment, and improve! 🚀

Happy coding! 🎉
