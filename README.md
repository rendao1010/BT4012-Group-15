# BT4012-Group-15

Through this project, our group hopes to identify the trends and patterns amongst credit card data for both fraudulent and non-fraudulent transactions, conduct feature engineering to identify and create any features that might seem to be able to set apart fraudulent transactions, and create machine learning models that are able to successfully detect fraudulent credit card transactions.

Before conducting model training, we first conduct feature engineering and EDA on the dataset, identifying any significant trends and distributions on the features.
  - Found in EDA and Summary.ipynb file
  
We then conduct model training on a wide range of models, identifying the best two after tuning - CatBoost and LGBM.
  - Found in models folder
  - Contains 8 different models
  - All models are trained with the same dataset 

Ultimately, we determine that both models can be used in a credit card company's business workflow in order to better flag up fraudulent transactions.
