# QR

This is a repo for past data science tests.

* `ga_test_ryan.ipynb` - Past GA technical assessment. Given a biking dataset, perform EDA, plot some graphs, data cleaning, etc. Predict ride duration (regression task) or end station (multiclass classification task). Conclusion - dataset lacks predictive power (poor accuracy, f1, etc). Models used were `catboost` and `vaex.ml` and  `vaex` for large dataframes. Suggestion - naively predict end station by tracking user history and suggesting most frequent destination station conditioned on starting station.