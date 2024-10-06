This code implements a simple Perceptron algorithm to classify patients as either Diabetic or non-diabetic,based on the Pima Indians Diabetes dataset.The perceptron is trained and tested using python.

The dataset has 768 samples of females aged 21 and older.The features include:

1.Number Of Pregnancies
2.Glucose Concentration
3.Blood Preassure
4.Skin Thickness
5.Insulin
6.Body Mass Index(BMI)
7.Diabetes pedigree Function(family history)
8.Age
The target variable indicates if the patient has diabetes(1) or not(0)

Requirements
1.numpy
2.pandas
3.scikit-learn

Result
For Class -1(Non Diabetic)
Precision:    0.78
Recall:        0.89     
F1-Score:    0.83
  
For Class 1(Diabetic)
Precision:   0.73
Recall:        0.55
F1-Score:    0.62
The model has an accuracy of 76.62%
