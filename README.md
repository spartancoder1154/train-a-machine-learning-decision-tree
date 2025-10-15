 Steps Performed


Data Loading & Preprocessing

Loaded the dataset using pandas
Converted categorical features into dummy/indicator variables using pd.get_dummies
Converted the target variable into binary format



Train-Test Split

Split the dataset into training and testing sets using train_test_split



Model Training

Created a DecisionTreeClassifier with default parameters
Trained the model on the training data



Model Evaluation

Printed the model parameters
Printed the depth of the trained decision tree
Evaluated the model using .score() and printed the test accuracy
