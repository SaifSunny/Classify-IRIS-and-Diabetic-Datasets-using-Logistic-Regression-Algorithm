# Classify-IRIS-and-Diabetic-Datasets-using-Logistic-Regression-Algorithm
This project is aimed at classifying two datasets: Iris and Diabetes, using logistic regression algorithm. The Iris dataset contains information about different types of iris flowers, while the Diabetes dataset contains information about patients who have or are at risk of developing diabetes.

# Dataset Description
1. iris.csv contains data about three different types of iris flowers: Setosa, Versicolor, and Virginica. The dataset includes 150 instances and 5 columns, including the sepal length, sepal width, petal length, petal width, and the type of iris flower.
2. diabetes.csv contains data about patients who have or do not have diabetes. The dataset includes 768 instances and 9 columns, including the number of times pregnant, glucose level, blood pressure, skin thickness, insulin level, body mass index (BMI), diabetes pedigree function, age, and whether the patient has diabetes or not.

# Requirements
1. Python
2. Pandas
3. Scikit-learn

# Installation

1. Clone this repository:
    
    git clone https://github.com/SaifSunny/Classify-IRIS-and-Diabetic-Datasets-using-Logistic-Regression-Algorithm

2. Install the required libraries:

    pip install pandas scikit-learn seaborn matplotlib
    
# Logistic Regression Algorithm
Logistic regression is a supervised learning algorithm that is used for classification. It is based on the logistic function, which maps any real-valued input to a value between 0 and 1. The logistic function is used to model the probability of a certain class or event.

In this project, we use the logistic regression algorithm to classify the Iris and Diabetes datasets. The algorithm learns the relationship between the input features and the output labels, and then uses this relationship to predict the label of new, unseen samples.

# Iris Prediction Accuracy
The logistic regression algorithm achieved 100% prediction accuracy on the Iris dataset. This means that it was able to correctly predict the class of all 150 samples in the dataset.

# Diabetic Prediction Accuracy
The logistic regression algorithm achieved 75% prediction accuracy on the Diabetes dataset. This means that it was able to correctly predict the class of 75% of the samples in the dataset. While this is not perfect, it is still a reasonably good result.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
