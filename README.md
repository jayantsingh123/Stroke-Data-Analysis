## Stroke-Data-Analysis
This project looks at a predictive model analyzing relation between the features which are most likely to cause stroke. The dataset is arranged as follows;
target variable denoting stroke happened or not(1 vs 0). In addition, there are several predictors defined including;
* Hypertension; binary variable indicating presence of High Blood Pressure
* Heart Disease; Binary variable denoting heart disease issues
* Smoking; categorical variable denoting different levels; such as active smoker, never smoked, unknown or non-smoker
* Gender; categorical variable denoting whther the subject is Male, Female or Unknown
* BMI; float variable denoting the BMI of the patient
* Glucose level; Similar to BMI, it is a float variable.
* Age; Age of the patient 

## Classification Problem
The main approach here is; given the above features, how likely is a patient to get the stroke.  It is well known that medical issues with a patient decide how likely h/she is to get a stroke. For the present analysis, logistic regression has been used. The dataset is small, around 6K records, hence linear model seems to be a suitable choice.
