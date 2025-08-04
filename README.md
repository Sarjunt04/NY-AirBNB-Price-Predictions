# NY-AirBNB-Price-Predictions
A report covering application of machine learning methods to predicting AirBNB prices in New York (May 2025)

This was a final year group project for LSE module ST310 (Machine Learning). In a team of three, we were given the broad objective of applying machine learning methods to provide useful insights or solve a relevant issue. We decided on predicting AirBNB listing price (base + fees) in New York, based on characteristics of the listing. For example, in today's market, how much should a guest expect to spend for a 10 night stay in a three bedroom Manhattan flat, or, indeed, how much should a host aim to charge? The overall grade was a 68.

We first loaded and cleaned the data, then ran an exploratory analysis to determine useful predictors. Then, we fitted and tuned models for each of the following ML methods: OLS, Decision Tree, Gradient Descent, Ridge Regression, Random Forest. For each model, we discussed results, concluding by acknowledging limitations and scope for further study.

We determined that the data was sufficient for predicting most listings, but failed for those with anomalously high prices. Our ridge model was the most effective, while the decision tree was the most interpretable.

My contributions to this project were: CODING - data cleaning, EDA, OLS model, decision tree, ridge setup (did not manage interactions / tune); REPORT - all previous and introduction, conclusion, ridge results
