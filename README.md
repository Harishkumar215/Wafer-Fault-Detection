# Wafer Fault Detection

* Extracted data in batches from Big Query and performed data cleaning operations  

* Applied K-Means clustering to create groups from large data and trained different ML models to each group with Random Forest as base model 

* Selected XGBoost model with hyperparameter tuning as final model with avg. Accuracy 0.96 from each group. 

* Built a Flask API endpoint that was hosted on the local web server, API endpoint takes in values from different sensor and classify whether the wafer is in good working condition. 
