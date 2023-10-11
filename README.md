# Stroke prediction
**Author**: Jaime Ross

## The goal of this analysis project is to create a model that is able to predict the likelihood of a patient experiencing a stroke based on factors such as age, gender, various diseases, etc.

## SOURCE OF DATA - https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

<p align = "center"> 
  <img src = "https://github.com/JaimeRoss/Data-Science/blob/main/images.png">
</p>

## According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. This dataset is used to predict whether a patient is likely to get a stroke based on input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relevant information about the patient


#### Count plot for stroke VS work type

<p align = "center"> 
  <img src = "https://github.com/JaimeRoss/Data-Science/blob/main/1.PNG">
</p>
### Those who worked in the private sector had the highest count for strokes as well as the highest count for no strokes.

#### Smoker status VS stroke

<p align = "center"> 
  <img src = "https://github.com/JaimeRoss/Data-Science/blob/main/2.PNG">
</p>
### Those who have never smoked have the highest count for no stroke as well as the highest count for stroke.

# Model Metrics:

Train
               precision    recall  f1-score   support

           0       0.99      0.75      0.85      3645
           1       0.14      0.79      0.24       187

    accuracy                           0.75      3832
   macro avg       0.56      0.77      0.54      3832
weighted avg       0.94      0.75      0.82      3832

Test
               precision    recall  f1-score   support

           0       0.98      0.74      0.84      1216
           1       0.13      0.77      0.22        62

    accuracy                           0.74      1278
   macro avg       0.56      0.76      0.53      1278
weighted avg       0.94      0.74      0.81      1278



# Description of model:
##The model chosen for this problem would be a logistic regression model. This model achieved an accuracy of 74%. The model still had quite a bit of false negatives, however it is less than all other models that were created.

# Summary:
## The final model chosen was able to make predictions with an accuracy of 74%, however consideration should still be taken with patients due to the number of false negatives within the model.
