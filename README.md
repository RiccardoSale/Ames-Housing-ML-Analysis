# Ames-housing dataset description

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.
Regression Task !

# Project phases
* Cleaning
* Data Preprocessing
* Analysis of the dataset and creation of different models : CatBoost, ANN, DecisionTree, RandomForest, LinearRegression, Knn

# Cleaning 
* Analyzing null/NaN
* Removing redundant features
* Removing skewed features
* Transformation of categorical qualitative features
* Feature correlation and observation
* Splitting with Stratified K-fold
# Data PreProcessing
* Creation of multiple new features that add information to the different models
* One-Hot encoding
* Min-Max scaler option
* Standard scaler option
# Training and analysis on multiple algorithms
* Best accuracy and stability achivied with CatBoost algorithm 
* ANN with adjusted LR can be a fast option to train the model and immediately obtain results on new data
