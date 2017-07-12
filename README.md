# kaggle_mercedes
The 11th place solution of Mercedes-Benz Greener Manufacturing competition on Kaggle
The descriprion is here: https://www.kaggle.com/c/mercedes-benz-greener-manufacturing/discussion/36242

List of files:
1. cluster_target_encoder.py - the class for generating the cluster labels. See: https://www.kaggle.com/daniel89/mercedes-cars-clustering/
2. sep_estimator.py - the class which fits four independent estimators. When predicting it splits the DataFrame by 'labels' columns and use the corresponding estimator to predict targets for corresponding 'labels' values.
3. solution_11_place.ipynb - the main script
4. submit_mercedes_11_place.csv - the output of the main script
