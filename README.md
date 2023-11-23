# Heart-Disease-Prediction
![image](https://github.com/LHLFOREVER/Heart-Disease-Prediction/assets/97744180/b580dbdc-dfac-439e-bd27-66415961b434)
# Introduction 
Coronary heart disease has been the leading cause of death worldwide for decades; as we can see from figure 1, heart disease caused 614,348 deaths in 2014, 23.4% of the total deaths in America. CHD continues to kill more people than any other cause. 
Risk factors for CHD include age, sex, family history, smoking, high blood pressure, high cholesterol, obesity, diabetes, chronic kidney disease, lack of exercise, lack of sleep, stress, an unhealthy diet, and alcohol use. 
![image](https://github.com/LHLFOREVER/Heart-Disease-Prediction/assets/97744180/8ee8364f-987c-4fe5-a8fb-3cf402a6b41e)


The research question for this project is, “What feature selection methods can improve the accuracy for predicting coronary heart disease, and what machine learning models can give us a higher accuracy and recall for an imbalanced dataset?”.  By improving feature selection methods and implementing better-performing machine learning models, we can improve the accuracy of predicting coronary heart disease, potentially leading to a cheaper and earlier diagnosis. This can also give patients more accurate results when trying to find out whether they have CHD or not in the early stages, improving outcomes as a result. 

In addition, this research can provide new insights for handling imbalanced datasets. Imbalanced datasets show up frequently in medical data, where the positive cases are vastly outnumbered by the negative cases. If our selected techniques show success here, they may be useful on similarly imbalanced datasets for other diseases.
# Dataset 
The dataset we are using is the NHANES data from 1999-2000 to 2015-2016. It has a total of 37,079 cases, with 1300 CHD-positive cases and 35,779 CHD-negative cases. Our dataset is highly imbalanced: We have significantly more CHD-negative cases than CHD-positive cases, and this will be one of the challenges we need to overcome. Some important features of our dataset include height, weight, blood pressure, BMI, and more. We have a total of 30 continuous variables and 6 categorical variables to predict coronary heart disease. 

During the data preprocessing phase we are going to split the data into a training set, a testing set, and a validation set. The training set will include 25,955 total cases which is about 70% of the entire dataset, the testing set is going to include 5,561 cases which is about 15% of the overall dataset and the validation set is going to include 5,561 cases which is about 15% of the overall dataset as well.

