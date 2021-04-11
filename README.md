# Heart-Disease-UCI-Kaggle
This repository contains code for classification of normal and abnormal state of heart using UCI Heart disease database. SVM classifier has been used for the purpose. An important step for dealing with categorical variables in SVM is to convert them to dummy variables. However, the idea of using dummy variables when number of categories are large, is not preferred method. Yet in this code, we show a usual framework which can be followed for obtaining preliminary results.   

The database can be obtained at https://www.kaggle.com/ronitf/heart-disease-uci. The data base contains following attributes-

1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defec
