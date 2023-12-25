
# Bike Destination Prediction Project (Boston Bike Dataset)
* I try predict the ride destination of a Bike sharing app to facilitate user recommendations. The dataset used is the [Boston Bike-Sharing Dataset](https://www.kaggle.com/datasets/jackdaoud/bluebikes-in-boston) collected from [BlueBikes](https://bluebikes.com/)
* I first performed data cleaning and EDA to understand the data set, then did feature engineering and modelling.
* Modelling libraries used were `catboost` (best for handling categorical features which were plenty) and `vaex.ml` (for processing very large datasets quickly) aside from the usual stack.
* Prediction power is fairly weak. An alternative solution would be to naively predict end station by tracking user history and suggesting most frequent destination similar to many ride-hailing apps (Uber, Grab, etc).
 
