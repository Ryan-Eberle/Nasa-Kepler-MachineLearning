# Nasa-Kepler-MachineLearning
Nasa's Kepler telescope has been on a mission to find new exoplanets outside of our solar system. Use multiple Machine Learning models to predict planets from the raw data. 


## Analysis Report
Used 3 different ML models to test accuracies across the models. Models used were: SVM, Random Trees, and Logistical Regression. 
Model Results:
SVM(.6)
Random(.89) 
LR(.64)
The Random Forests model was the only model to present an accuracy of over 80%. In further investigation on how to predict exoplanets, one would be best to work on tuning the Random Forests model more. First steps would be to limit the features used in modeling. For this project, I did not remove any of the features presented in the data set. The possibility of erroneous data would have affected the tuning and modeling. 


## Model Rank

### Random Forests
<img width="520" alt="RandomForest_result" src="https://user-images.githubusercontent.com/65464107/99011941-7a7f5d00-250a-11eb-812a-1d0d0ead4bee.png">

### Logistical Regression
<img width="525" alt="Logistic_reg_result" src="https://user-images.githubusercontent.com/65464107/99011963-879c4c00-250a-11eb-827b-ccbfb8a41d3c.png">

### SVM
<img width="561" alt="SVM_result" src="https://user-images.githubusercontent.com/65464107/99011973-8bc86980-250a-11eb-9130-c2b69aa08f7b.png">
