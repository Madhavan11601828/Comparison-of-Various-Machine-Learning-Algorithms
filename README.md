# Comparison-of-Various-Machine-Learning-Algorithms
This work is intended to show the basic working nature of various machine learning algorithms using Iris Dataset.

# Iris Dataset
Iris Dataset can be available in multiple sources. [Source1](https://archive.ics.uci.edu/ml/datasets/iris) [Source2](https://www.kaggle.com/uciml/iris)

# Dataset Description
The Iris dataset was used in R.A. Fisher's classic 1936 paper, The Use of Multiple Measurements in Taxonomic Problems, and can also be found on the UCI Machine Learning Repository. It includes three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other. The columns in this dataset are:
1. Id
2. SepalLengthCm: It represents Iris flower's sepal length in centimeters. 
3. SepalWidthCm: It represents Iris flower's sepal width in centimeters.
4. PetalLengthCm: It represents Iris flower's petal length in centimeters.
5. PetalWidthCm: It represents Iris flower's petal width in centimeters.
6. Species: It includes three different species of Iris flower exist. They are: setosa, versicolor, and virginica.

# Working structure of the methodology
Step-1: Link colab environment with google drive.
Step-2: Kaggle dataset imported into colab environment through google drive.
Step-3: Load the required libraries
Step-4: Loding the data into working environment
Step-5: Obtain summarization of the data, in otherwords, Descriptive Statistics of the data.
Step-6: Checking the existence of NULL values in the dataset. If they exist, replace or delete them (In this case there are no NULL values)
Step-7: Visua;lize the data using box-plot and histogram to identify the outliers and distribution of the data.
Step-8: Pre process the data. This Step includes
        Dividing the dataset into independent(X) data and dependent(Y) data.
        Divide both X and Y into training and testing datsets.
Step-9: Build the classification models using various ML methodologies such as logistic regression, decision tree, KNN, naive bayes, linear discriminent analysis, and support             vector machine.
Step-10: Compare the models using their corresponding accuracies
Step-11: Evaluate and predict the models using test dataset.
Step-12: Model can be saved using pickle library.

# Utilized libraries
NUMPY
PANDAS
PICKLE
SKLEARN
MATPLOTLIB
