# Heart Disease Prediction: Project Overview
## Problem Definition
A system/project by using a number of different features (pieces of information) about a person to predict whether they have heart disease or not. In this case, the problem of is binary classification (a sample can only be one of two things).<br>
Given clinical parameters about a patient, can we predict whether or not they have heart disease?<br>
## Dataset
- The original data came from the [Cleveland database](https://archive.ics.uci.edu/ml/datasets/heart+Disease) from UCI Machine Learning Repository.
- However, I've downloaded it in a formatted way from [Kaggle](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset).
- The original database contains 76 attributes, but here only 14 attributes will be used. 
- Attributes (also called features) are the variables that I have used to predict the target variables.
- Attributes and features are also referred to as independent variables and a target variable can be referred to as a dependent variable.
- Used the independent variables to predict the dependent variable (Target).
- The independent variables are a patient's different medical attributes and the dependent variable is whether or not they have heart disease.
### Correlation between Features of Data
![image](https://user-images.githubusercontent.com/115410634/204327791-7269ea18-dbf5-4705-adfd-e363d32b20cf.png)

### Heart Disease Data Dictionary
A data dictionary describes the data we're dealing with. Not all datasets come with them so this is where we may have to do our research or ask a subject matter expert (someone who knows about the data) for more.<br>

The following are the features that are used to predict the target variable (heart disease or no heart disease).<br>

1. age - age in years
2. sex - (1 = male; 0 = female)
3. cp - chest pain type
- 0: Typical angina: chest pain related decrease blood supply to the heart
- 1: Atypical angina: chest pain not related to heart
- 2: Non-anginal pain: typically esophageal spasms (non-heart related)
- 3: Asymptomatic: chest pain not showing signs of disease
4. trestbps - resting blood pressure (in mm Hg on admission to the hospital)
anything above 130-140 typically causes concern
5. chol - serum cholesterol in mg/dl
- serum = LDL + HDL + .2 * triglycerides
- above 200 is cause for concern
6. fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- '>126' mg/dL signals diabetes
7. restecg - resting electrocardiographic results
- 0: Nothing to note
- 1: ST-T Wave abnormality
- can range from mild symptoms to severe problems
- signals non-normal heartbeat
- 2: Possible or definite left ventricular hypertrophy
- Enlarged heart's main pumping chamber
8. thalach - maximum heart rate achieved
9. exang - exercise-induced angina (1 = yes; 0 = no)
10. oldpeak - ST depression induced by exercise relative to rest
- looks at the stress on the heart during exercise
- unhealthy heart will stress more
11. slope - the slope of the peak exercise ST segment
- 0: Upsloping: better heart rate with exercise (uncommon)
- 1: Flatsloping: minimal change (typical healthy heart)
- 2: Downslopins: signs of an unhealthy heart
12. ca - number of major vessels (0-3) colored by fluoroscopy
-colored vessel means the doctor can see the blood passing through
- the more blood movement the better (no clots)
13. thal - thalium stress result
- 1,3: Normal
- 6: fixed defect: used to be a defect but ok now
- 7: reversible defect: no proper blood movement when exercising
14. target - have disease or not (1=yes, 0=no) (= the predicted attribute)
