# DS

This is a repo for past data science tests.

* `ga_bike_destination_pred.ipynb` - Technical assessment for General Atlantic Junior Data Scientist role. 
    * Given a biking dataset, I was asked to perform EDA, plot some graphs, data cleaning, feature engineering etc.
    * The objective given was to predict ride duration (regression task) or ride end station (multiclass classification task). After modelling, my conclusion was that the dataset lacked predictive power (poor accuracy, f1, etc). Modelling libraries used were `catboost` and `vaex.ml` aside from the usual stack. 
    * My suggestion given would be to naively predict end station by tracking user history and suggesting most frequent destination station conditioned on starting station. This would likely outperform the model while being more practical/achieving the objective better without any use of ML in the first place. On hindsight, maybe I shouldn't have told them that directly ...  