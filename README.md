<h1 align="center">Congestive Heart Failure Classification 🩺 </h1>

## Objective
This repository will contain input dataset - heart.csv from Kaggle. The main aim of the project is to predict if a person will have heart failure based on various other factors or attributes like Age, Gender, Cholestrol, ChestPainType, Oldpeak, ExerciseAngina etc. There are multiple models used for the training purposes and various features like the F1 score, Accuracy, Precision, Recall etc are compared to get the best results for prediction.

## About data source:
This dataset was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:

Cleveland: 303 observations
Hungarian: 294 observations
Switzerland: 123 observations
Long Beach VA: 200 observations
Stalog (Heart) Data Set: 270 observations
Total: 1190 observations
Duplicated: 272 observations

Final dataset: 918 observations

## Attributes in the data source
As discussed above there are 11 features which are used for predicting the 12th feature (HeartDisease). The details of the 11 attributes are as follows.

1. Age: age of the patient (years)

2. Sex: sex of the patient (M: Male , F: Female)

3. ChestPainType: chest pain type (TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic)

4. RestingBP: resting blood pressure (mm Hg)

5. Cholesterol: serum cholesterol (mm/dl)

6. FastingBS: fasting blood sugar (1: if FastingBS > 120 mg/dl, 0: otherwise)

7. RestingECG: resting electrocardiogram results (Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of  > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria)

8. MaxHR: maximum heart rate achieved (Numeric value between 60 and 202)

9. ExerciseAngina: exercise-induced angina (Y: Yes, N: No)

10. Oldpeak: oldpeak = ST (Numeric value measured in depression)

11. ST_Slope: the slope of the peak exercise ST segment (Up: upsloping, Flat: flat, Down: downsloping)

12. HeartDisease: output class (1: heart disease, 0: Normal)

## Analysis done
Various analysis like gender and age distribution, the number of outliers, pairplot, correlation heatmaps were plotted to decide on various features which will affect the heart failure outcome.
- Gender wise Analysis
<p align="center">
  <img src="https://github.com/AshiniAnantharaman/Congestive-Heart-Failure-Classification/blob/main/Gender-wise%20Distribution.png" />
</p>

- Age distribution and outliers
<p align="center">
  <img src="https://github.com/AshiniAnantharaman/Congestive-Heart-Failure-Classification/blob/main/Age%20Outliers.png" />
</p>


## Online dataset link
https://www.kaggle.com/fedesoriano/heart-failure-prediction.

Every dataset used can be found under the Index of heart disease datasets from UCI Machine Learning Repository on the following link: https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/

## Citation
fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [Date Retrieved] from https://www.kaggle.com/fedesoriano/heart-failure-prediction.

## Acknowledgements
Creators of Dataset:

1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.
