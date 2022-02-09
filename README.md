# Credit Risk Analysis
---
## The purpose of this analysis:

Fast lending wants to use machine learning to predict credit risk and they believe it will provide a quicker and more reliable loan experience long with lower default rates. The company wants me to build several machine learning models to test this theory out. 

## Results:

### Naive Random Oversampling:

Balance accuracy score: 66.6%

Precision scores: high-risk 0.01 ; low-risk 1.00

Recall scores: high-risk 0.70 ; low-risk 0.63

Avg/Total: .99 for precision & .63 for recall

![naive](https://user-images.githubusercontent.com/88864493/153117687-5796610f-8826-4df1-bcb0-58dee0652de1.png)


### SMOTE Oversampling:

Balance accuracy score: 66.2%

Precision scores: high-risk 0.01 ; low-risk 1.00

Recall scores: high-risk 0.63 ; low-risk 0.69

Avg/Total: .99 for precision & .66 for recall

![smote](https://user-images.githubusercontent.com/88864493/153117792-ac6cfd77-3854-4104-958f-06eaf814dccf.png)


### Undersampling:

Balance accuracy score: 54.4%

Precision scores: high-risk 0.01 ; low-risk 1.00

Recall scores: high-risk 0.68 ; low-risk 0.57

Avg/Total: .99 for precision & .57 for recall

![undersampling](https://user-images.githubusercontent.com/88864493/153118116-7520583c-34cf-401f-92ff-0a94b46508e6.png)


### Balanced Random Forest Classifier:

Balance accuracy score: 78.9%

Precision scores: high-risk 0.03 ; low-risk 1.00

Recall scores: high-risk 0.70 ; low-risk 0.87

Avg/Total: .99 for precision & .87 for recall

![randomforest](https://user-images.githubusercontent.com/88864493/153118483-a1d73006-54da-41b1-b374-b886a9f7cc2a.png)


### Easy Ensemble AdaBoost Classifier:

Balance accuracy score: 93.1%

Precision scores: high-risk 0.09 ; low-risk 1.00

Recall scores: high-risk 0.92 ; low-risk 0.94

Avg/Total: .99 for precision & .94 for recall

![easy](https://user-images.githubusercontent.com/88864493/153118819-fc0535b5-19ab-456b-9df8-836c33590b1f.png)


### Combination (Over and Under) Sampling:

Balance accuracy score: 64.4%

Precision scores: high-risk 0.01 ; low-risk 1.00

Recall scores: high-risk 0.72 ; low-risk 0.57

Avg/Total: .99 for precision & .57 for recall

![combo](https://user-images.githubusercontent.com/88864493/153118950-0f8e1319-c37e-46ac-869f-2f65212f9f01.png)


##Summary:
I would recommend using the Easy AdaBoost Classifier as it has the highest accuracy rate coming it at 93.1%. It also has the highest precision scored as well. 
