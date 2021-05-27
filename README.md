# ML-Disease-prediction


Dataset did not have any missing values but outliers are present in age, trestbps,chol,oldpeak,thalach columns 

**1.Earlier without removing outliers accuracy:DecisionTreeClassifier**

![image](https://user-images.githubusercontent.com/68188457/119838329-f37f5880-bf20-11eb-8cf7-06b77e3cf424.png)

**XGboost Classifier:**

![image](https://user-images.githubusercontent.com/68188457/119839351-b9628680-bf21-11eb-93cc-d2f634ff527a.png)


**2.After removing Outliers : DecisionTreeClassifier**

![image](https://user-images.githubusercontent.com/68188457/119839137-93d57d00-bf21-11eb-8fe0-ba2ef8627415.png)

**XGboost Classifier**

![image](https://user-images.githubusercontent.com/68188457/119839465-cf704700-bf21-11eb-8344-3eb6d0c4f2d9.png)



**3.MinMaxSacler Vs SatandardScaler**

StandardScaler performed really well

**4.Test Data Analysis:**

age, trestbps,chol,thalach columns are having outliers.

**output data is stored in test_data_analysis.csv file**





