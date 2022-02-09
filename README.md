# Customer-churn-analysis
1.In this data we have to find out how many customers have churned or continued their service with the same company and the reson for their churning.
2. After taking out the churn percentage I found out that there are 76% who has not churned and 23% have churned.
The distribution of data is not proper so I have to check what can be done to get the appropriate info from the data.
3.There are 7043 rows and 21 columns.
4. While checking the data types of the churn data found out that Total charges is showing as Object type but it should be int or float type.
5. After changing the data type into numeric found out that there are 11 missing values in the data.
6.Since the missing value is very low(0.15%) we can drop the row and it wont effect our data much. 
7.After that I have converted the tenure group data into bins to do the visualization according the tenure they have taken from the company.
8.Exploring the data by using visualization library.
9.converting the target variable churn into 0 or 1 from Yes or No.
10.Converting all categorical values into dumming varaible.
11.Seeing the relationship between the monthly cahrges and total charges.They are highly corelated because if monthly charges increase then total charges will aslo increase.
12.Tried to corelate monthly charges,total charges and churn together.Found that churn is high when monthly charges are getting higher.
13.After combining the 3 parameters tenure,monthly charges , total charges...Higher monthly charge into lower tenure result to lower total charges.
14.High churn in case of month to month contracts,no online security,no tech support,first year subscription and fibre optics Internet.
    Low churn is seen in case of long term contracts ,Subscriptions without internet service, and the customers engaged for 5+ yrs.
    Factors like Gender,Availability of phone service  have almost no impact on churn.
15.In this next step I have done Bivaraite analysis in which I have created two data frame one for churner and another for non churner.
16.Electronic check who are maintaining they are more churner and most females user who are using credit card are also more churners and monthly contract also.
17. Creating X and Y varaible where X is our Independent variable and Y is our dependent varaible(i.e, Churn data).
18.While doing Decision tree classifier I have found out that the precision ,recall,f1 score are very low becz we have imbalance data set 
19.For dealing with this problem we will use smotten analysis which helps us to perform over sampling using smote and cleaning ENN.
20.After using smotteen analysis we have got good percentage in our model and now we will check the score with other classifiers also.
21.In Random forest also we faced the same problem of imbalance data set so here also we will use smottenn analysis.
