# Diabetes_Prediction
Streamlit webapp featuring a machine learning classification model for positive or negative for diabetes based on dataset of the Pima Indians.

## Parameters
1. Pregnancies (integer)
2. Glucose level (decimal)
3. Resting Blood Pressure (decimal)
4. Skin Thickness (decimal)
5. Insulin (decimal)
6. Body Mass Index (decimal)
7. DiabetesPedigreeFunction (decimal)
8. Age (integer)
9. Outcome (binary)

## Results
The Model showed a weighted average of 88% for each: precision, recall, f1-score.  Support: 154.
Glucose Level and Diabetes Pedigree Function saw the highest correlation with the target variable. 

## Considerations
This model, while accurate on this particular population, is limited to a single sample population of the entire human global population and does not therefore take into account certain genetic mutations that may account for greater or lower predisposition to Diabetes whether type 1 or type 2.  Further testing of the model on outside populations is required and will help resolve bias in the model.  If you would like to contribute using the parameters specified and whether you know for a fact if you have this disease or not I would love to add it to make a better model
