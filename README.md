# QR

This is a repo for past data science tests.

* `ga_test_ryan.ipynb` - Past GA technical assessment. Given a biking dataset, perform EDA, plot some graphs, data cleaning, etc. Predict ride duration (regression task) or end station (multiclass classification task). Conclusion  was that dataset lacks predictive power (poor accuracy, f1, etc). Models used were `catboost` and `vaex.ml` and  `vaex` for large dataframes. Suggestions would be to naively predict end station by tracking user history and suggesting most frequent destination station conditioned on starting station. This would likely outperform the model while being more practical/achieving the objective better without any use of ML in the first place. On hindsight, I guess I shouldn't have told them that directly ...  