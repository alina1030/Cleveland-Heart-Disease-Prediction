# Cleveland-Heart-Disease-Prediction

**AIM/OBJECTIVE**

To predict wether a person is having heart disease or not based on input feature values such as age,sex,cp,trestbps,chol,fbs,restecg,thalach,exang,oldpeak,slope,ca,thal,num

**METHODOLOGY**

1.Read the dataset
2.Preprocess the dataset(data cleaning)
3.Assign input(x) and output(y) values for training and testing
4.Standardize input values
5.Split the dataset into training & testing dataset
6.Use Classification models to fit and predict
7.Evaluation of metrics

**KEY FEATURES OF THE PROJECT**

**1. PCA and LDA for dimensionality reduction**

**PCA**
Principal Component Analysis is an unsupervised learning algorithm that is used for the dimensionality reduction in machine learning. It is a statistical process that converts the observations of correlated features into a set of linearly uncorrelated features with the help of orthogonal transformation. These new transformed features are called the Principal Components.

PCA generally tries to find the lower-dimensional surface to project the high-dimensional data.

PCA works by considering the variance of each attribute because the high attribute shows the good split between the classes, and hence it reduces the dimensionality.

**LDA**

Linear discriminant analysis is supervised machine learning, the technique used to find a linear combination of features that separates two or more classes of objects or events.

Linear discriminant analysis, also known as LDA, does the separation by computing the directions (“linear discriminants”) that represent the axis that enhances the separation between multiple classes.

**2. Hypertuning of parameters**

We pass predefined values for hyperparameters to the GridSearchCV function in the form of dictionary.

GridSearchCV tries all the combinations of the values passed in the dictionary and evaluates the model for each combination using the Cross-Validation method. Hence after using this function we get accuracy/loss for every combination of hyperparameters and we can choose the one with the best performance.
