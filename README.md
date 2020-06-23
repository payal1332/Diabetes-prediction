# Diabetes-prediction
Predicting the patient being diabetic or not, based on the given set of variables.

Dataset: 768 observation 9 variables (No. of times pregnant, BMI(Body Mass Index), Blood Pressure, Insulin, Glucose, Skin thickness, Diabetes Pedigree Function, Age, Class (Output Variable).

Data Preparation, EDA: Univariate(Histogram, boxplot) & Bivariate analysis (Scatter plot, correlation both with input/output variables). Data was partitioned into train & test datasets to train the model,and generalize for the new data.
Using DecisionTree algorithm, a model was build on the training with the best accuracy achieved by hypertuning the parametes(Criterion, max_depth,min_sample_leaf).
Made predictions using the test data. Also used the feature importance to show their contribution to the model.

Once the model was built, Flask was used for the deployment of the model, where one has to input the values which provides result of a person being Diabetic/not.
