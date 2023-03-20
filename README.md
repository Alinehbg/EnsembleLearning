PREDICTING AIRBNB PRICES IN NEW-YORK CITY

Airbnb has become a popular alternative to traditional hotels and has disrupted the hospitality industry. Through Airbnb, individuals can list their own properties as rental places. In New York City alone, there are around 47,000 listings. While traditional hotels have teams that carefully measure demand and supply to adjust pricing, as a host, it can be challenging to determine the optimal price for a listing. The variation in types of listings can also make it difficult for renters to get an accurate sense of fair pricing. In this project, we will use ensemble learning methods to predict the price of Airbnb listings in New York City.

The data set for this project is obtained from Kaggle and contains the listings in New York City in 2019. The data set includes 15 features on listings, including: Name of the listing, Neighborhood, Price, Review information, Availability, etc. The data set contains over 48,000 listings and can be downloaded on Kaggle here: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data.

Before starting the project, the data has been pre-processed by cleaning and transforming it into a format that can be used. This includes removing missing values, converting categorical variables to numerical variables, and excluding outliers.

Here, we apply different approaches taught in the course and practiced in lab sessions (Decision Trees, Random forests, AdaBoost, XGBoost, Stacking) on the data set. The goal is to predict the target variable (price of the listing) and compare the performances of models using various metrics learned in class (mainly RMSE).

The final, grouped work can be found inside the notebook 'Main_Stacked_Ensembles.ipynb'. It combines the data cleaning process, and shows optimized model performance as well as the stacking step. To see how the models have been optimized, go into the notebooks referring to the specific models (e.g: 'Adaboost.ipynb'). 


BUILDING A DECISION TREE FROM SCRATCH

The second part of this repository is the implementation of a decision tree from scratch, which handles both classification and regression tasks. Decision trees are widely used in machine learning as a simple, interpretable model for making predictions based on a set of features. A decision tree consists of a root node, interior nodes, and leaf nodes. The root node represents the data set, while the internal nodes represent a feature and corresponding decision rule, and the leaf nodes represent a predicted outcome.

The code can be found in the notebook "DecisionTreeFromScratch.ipynb". The file provides commented code for our decision tree implementation, as well as a test of our algorithm on classification and regression data sets, and finally a comparison of its performance with the Python implementation of the scikit-learn library.
