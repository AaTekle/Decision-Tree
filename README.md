# Decision-Tree

# Diabetes Prediction using a Decision Tree Algorithm

This project uses a decision tree 
to predict whether a patient has diabetes or not. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes.

The project is implemented in Python using the Pandas & Scikit-learn libraries. The steps involved are:

1. Importing the necessary libraries
2. Loading the dataset
3. Splitting the dataset into training and test sets
4. Building the decision tree model
5. Evaluating the model performance
6. Visualizing the decision tree
   
## Dataset

The dataset used in this project is the National Institute of Diabetes and Digestive and Kidney Diseases Diabetes Dataset. This dataset contains observations of 9 features, including:

* Pregnancies: Number of times pregnant
* Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
* BloodPressure: Diastolic blood pressure (mm Hg)
* SkinThickness: Triceps skin fold thickness (mm)
* Insulin: 2-Hour serum insulin (mu U/ml)
* BMI: Body mass index (weight in kg/(height in m)^2)
* DiabetesPedigreeFunction: Diabetes pedigree function
* Age: Age (years)
* Outcome: Class variable (0 or 1)

## Model

The decision tree model is built using the Scikit-learn - DecisionTreeClassifier model. The accuracy of the model is 71.43%.

## Visualization

The decision tree can be visualized using the Scikit-learn `export_graphviz` function.

## Conclusion

This project uses a decision tree algorithm to predict whether a patient has diabetes or not.
