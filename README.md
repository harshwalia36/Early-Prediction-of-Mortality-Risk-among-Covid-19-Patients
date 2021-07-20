# EARLY PREDICTION OF MORTALITY RISK AMONG COVID-19 PATIENTS
### Btech Thesis project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-xKr6dSdk1LKg3aN6wEy0hbMoaNjyF32#scrollTo=oPgH_GRDbJqi)
<br>


<!-- ![image](https://user-images.githubusercontent.com/43993467/125559094-178dcdcf-a718-41cc-a082-ab14db24605b.png) -->

<img src="https://user-images.githubusercontent.com/43993467/125559094-178dcdcf-a718-41cc-a082-ab14db24605b.png" width="256">

- **In this study, our primary aim is to Detect the Severe Covid-19 patient in the Early
Stages by looking at the information on demographics, comorbidities, admission
laboratory values, admission medications, admission supplemental oxygen orders,
discharge and mortality.**

- ***Motivation*** behind the Project is to help the overwhelmed hospitals by predicting the Severe Covid-19 Patients in Early Stages on the basis of their
comorbidities, admission laboratory test values, admission medications, admission supplemental oxygen orders.
While knowing the number of patients which may require a **Intesive-Care-Unit(ICU)**
in the future, Hospitals can arrange the ICU beds accordingly, which can lead to
**Save the Patients life** or knowing which patients don't need any ICU support or
Not Severely affected by COVID-19 can go for home quarantine.

- **4711 patients dataset with conirmed SARS-CoV-2 infection were included in the study which contain 85 features.**

Since, the dataset contain very large number of features(85 features) so we have used 7 features selection algorithm to Selct the Most Important features in the dataset.<br>
We filtered out the feature  which is most common in all 7 algorithms.

**The Seven Features selection(FS) algo used are:-**
1. FS with Pearson Correlation
2.  FS by the SelectFromModel with LinearSVC
3.  FS by the SelectFromModel with Lasso
4.  FS by the SelectKBest with Chi-2
5.  FS by the Recursive Feature Elimination (RFE) with Logistic Regression
6.  FS by the Recursive Feature Elimination (RFE) with Random Forest
7.  FS by the VarianceThreshold

**After Selecting the best Features out of all features I have implemented 17 different models and check their accuracy, precision, recall, F1-Score and AUC_ROC and finally a voting classifier is made which includes the top best models out of all 17 models and vote is made by each model to predict the class 0/1 .
The class which get most votes is our predicted class.**

***Models which are used in this project are***
1. **Linear Regression**
2. **Logistic Regression**
3. **Support Vector Machines**
4. **Linear SVC**
5. **MLP Classifier**
6. **Decision Tree Classifier**
7. **Random Forest Classifier**
8. **Ada Boost Classifier**
9. **Gradient Boost Classifier**
10. **XGBoost Classifier**
11. **LightGBM**
12. **Ridge Classifier**
13. **Bagging Classifier**
14. **ExtraTree Classifier**
15. **KNN**
16. **Naive Bayes**
17. **NN with Keras**
18. **Voting classifier**


## RESULT

![image](https://user-images.githubusercontent.com/43993467/126252838-6fb03f00-8bd0-4314-b3d9-5cbd48a79cbe.png)

