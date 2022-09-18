# Breast-Cancer-Detection

This is a binary classification problem and depending on several features the target value is either rock or mine.
All the labels are cleaned and EDA stuff has been done. Then, LogisticRegression, KNN and Support Vector Classifiers applied to the 
data. Best accuracy was with LogisticRegression as it seems in accuracy score and confusion matrix. </br></br>
Accuracy score on Train data: 97.80676328502416 </br> 
Accuracy score on Test Data: 97.36842105263158


Data Source
------
Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter) </br>
b) texture (standard deviation of gray-scale values) </br>
c) perimeter </br>
d) area </br>
e) smoothness (local variation in radius lengths) </br>
f) compactness (perimeter^2 / area - 1.0) </br>
g) concavity (severity of concave portions of the contour) </br>
h) concave points (number of concave portions of the contour) </br>
i) symmetry </br>
j) fractal dimension ("coastline approximation" - 1) </br>

Needed Librares
------
* Pandas, matplotlib, seaborn, sklearn
