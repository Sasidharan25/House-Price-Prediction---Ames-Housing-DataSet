# House Price prediction using regression on Ames Housing dataset




# Problem Statement

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

# Contents

1. Data PreProcessing
2. Data Exploration and Visualization
3. Feature Engineering
4. Feature Selection (via mutual information & variance threshold)
5. Feature Encoding ( Ordinal & One-Hot encoding)
6. Modeling & HyperParameter Tuning
7. Predictions

# Results

The metric used to evaluate the model is Root Mean Squared Error (RMSE) with lower the RMSE, better the model. The model (xgboost) built for the project showed a rmse value of ~ 0.14 on train data and ~ 0.1517 on test data. The model's perfomance on the competition dataset is 0.15153 (Leaderboard rank : 2092/3916)
