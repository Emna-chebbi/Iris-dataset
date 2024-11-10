# Iris-dataset
The Iris dataset consists of 150 samples from three species of iris flowers: Setosa, Versicolor, and Virginica. 
For each sample, the dataset includes four features of the flowers:
Sepal length
Sepal width
Petal length
Petal width
Each feature is measured in centimeters.

The tasks I have done :
- Loaded the Iris dataset from scikit-learn using load_iris() and extracted the features (X) and target labels (y).
- Split the dataset into training and testing sets using train_test_split() to evaluate the model's performance.
- Trained a Decision Tree Classifier using DecisionTreeClassifier() from sklearn, fitting it to the training data (X_train, y_train).
- Predicted the class of a new flower by providing input features (e.g., sepal length, sepal width, petal length, petal width) to the trained model using clf.predict().
- Output the predicted iris species by mapping the predicted class index to the species name from iris.target_names.
- Calculated and displayed the model's accuracy using accuracy_score() by comparing the predicted labels on the test set (X_test) to the actual labels (y_test).
- Visualized the decision tree using plot_tree() to understand how the model splits the data.
- Customized the visualization with matplotlib by setting a larger figure size (figsize=(15,12)).
- Enhanced the tree plot by adding feature names ("Sepal Length", "Sepal Width", "Petal Length", "Petal Width") and class names ("Setosa", "Versicolor", "Virginica") for better clarity.
