# T5-EDA-Heart-Disease

#Data Overview:

All the values in the dataset were collected at the time of medical examination and provided information about the signs of Cardiovascular Disease. This Dataset has 70,000 observations(rows) and 12 features(columns).

#Source:

Kaggle.com :
To download the dataset Click_here
https://www.kaggle.com/sulianova/cardiovascular-disease-dataset

#Columns description:

#There are 3 types of input columns:

Objective: factual information ,
Examination: results of medical examination;
Subjective: information was given by the patient.

#Columns description
Objective Feature
Feature name	ShortCut	Data type
Age	age	int (days)
Height	height	int (cm)
Weight	weight	float (kg)
Gender	gender	categorical
Examination Feature
Feature name	ShortCut	Data type	Description
Systolic blood pressure	ap_hi	int	-
Diastolic blood pressure	ap_lo	int	-
Cholesterol	cholesterol	int	1: normal, 2: above normal, 3: well above normal
Glucose	gluc	int	1: normal, 2: above normal, 3: well above normal
Subjective Feature
Feature name	ShortCut	Data type	Description
Smoking	smoke	binary	-
Alcohol intake	alco	binary	-
Physical activity	active	binary	-
Presence or absence of cardiovascular disease	cardio	binary	Target Variable

#Question:

The goal is to do exploratory data analysis (EDA) to answer these questions :
What is the most gender is exposed to be Cardiovascular Disease that has?

Is there a relationship between smoking and getting Cardiovascular Disease?

Is there a relationship between age and getting Cardiovascular Disease?

what is the age that has the most patient number of Cardiovascular Disease?

How many Smokers and Non-Smokers do not have a Cardiovascular Disease?

How many Smokers and Non-Smokers have a Cardiovascular Disease?

Is their a relationship between doing physical activity and not having a Cardiovascular Disease?

Is there a relationship between being overweight and having Cardiovascular Disease?

How many cholesterol patients have a Cardiovascular and at what level they are?

What is the cholesterol level that has a large number of Cardiovascular Disease?

How many alcoholics are Cardiovascular Disease?

#Tools:

Libraries: pandas, numpy, matplotlib, geopandas, geopy, plotly_express
Softwares: VSCode, Jupyter, GitHub

#MVP goals:

Answer all the questions.
