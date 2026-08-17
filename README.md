Iris Classification uses a Neural Network model in Machine Learning to classify Iris flowers into three species: Setosa, Versicolor, and Virginica, based on their sepal length, sepal width, petal length, and petal width.
The Iris dataset is loaded from Scikit-learn using the load_iris() function. It contains 150 samples, 4 input features, and 3 target species.
A Neural Network is a Machine Learning model that consists of layers of interconnected nodes that learn patterns from input data and use them to make predictions.
A Neural Network is used because it can learn complex patterns and relationships between input features and target classes. In this project, the model has one hidden layer containing 10 neurons.
The dataset is divided into training and testing sets using an 80-20 split, with 80% of the data used for training and 20% used for testing.
The performance of the model is evaluated using Accuracy Score.
The trained model is also used to predict the species of a new Iris flower by providing its sepal and petal measurements.
