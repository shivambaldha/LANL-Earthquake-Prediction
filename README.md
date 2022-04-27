# LANL-Earthquake-Prediction
## 1. Introduction
Forecasting earthquakes is one of the most important problems in Earth science because of their devastating consequences. Current scientific studies related to earthquake forecasting focus on three key points: when the event will occur, where it will occur, and how large it will be. And the reason the earthquake occurs is the rupture of the geological faults but also by the other event such as volcanic activity, landslides, mine blasts, the nuclear test, etc.
So if we predict the earthquake before the time this is very helpful for the people and we can save a life of a people.

## 2. Business Problem
The goal of this competition is to use seismic signals to predict the timing of laboratory earthquakes.
Here we have to predict the remaining time before the next laboratory earthquakes based on the seismic data. The remaining time is meant by the remaining time between the current earthquake and the occurrence of the next earthquake.
Since the seismic data is continuous and the real values and our target is also real value, so this is a regression problem.

## 3. Source Of Data
LANL Earthquake Prediction is a competition held by the Department of Physics & Astronomy of the pursue university and hosted on the Kaggle. The data set contains only two columns.
The dataset folder contains the following files:
Train.csv this file contains 2 columns and 629 million rows, the 1st one is acoustic_data which is a wave. this wave looks like sound waves & continuous segments of experimental data. And 2nd one is time_to_failure, basically, it is the remaining time before the next earthquake.
Test.csv, in this folder there are many .csv files available and each file contains a series of acoustic waves, and each test file in the test set contains only 150,000 rows of acoustic waves.
Sample_submission.csv, It is of shape 2624 x 2 which has seg_id and time_to_failure,
Dataset Overview can be found in this link.

## 4. Business Constraints
The predicted value should be the Whole Number.
Strict latency constraints.
Incorrect forecasting may lead to missed loss of human life and money.
