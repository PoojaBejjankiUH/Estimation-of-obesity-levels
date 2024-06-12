# Estimation-of-obesity-levels
Project Overview
This project estimates obesity levels in individuals based on their eating habits and physical conditions using various machine learning (ML) models. By analyzing patterns in dietary habits and physical health metrics, we aim to predict obesity levels to aid in early intervention and personalized health recommendations.

## Dataset
The dataset includes features related to eating habits, physical activity, and demographic information. Key attributes are:

This dataset include data for the estimation of obesity levels in individuals from the countries of Mexico, Peru and Colombia, based on their eating habits and physical condition.

## Dataset Characteristics
Multivariate

### Subject Area
Health and Medicine

### Associated Tasks
Classification, Regression, Clustering

### Feature Type
Integer

# Instances
2111

# Features
16

## Dataset Information
This dataset include data for the estimation of obesity levels in individuals from the countries of Mexico, Peru and Colombia, based on their eating habits and physical condition. The data contains 17 attributes and 2111 records, the records are labeled with the class variable NObesity (Obesity Level), that allows classification of the data using the values of Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II and Obesity Type III. 77% of the data was generated synthetically using the Weka tool and the SMOTE filter, 23% of the data was collected directly from users through a web platform.

## Has Missing Values?

No

## Introductory Paper
Dataset for estimation of obesity levels based on eating habits and physical condition in individuals from Colombia, Peru and Mexico
By Fabio Mendoza Palechor, Alexis De la Hoz Manotas. 2019

## Published in Data in Brief

Variables Table
Variable Name	Role	Type	Demographic	Description	Units	Missing Values
Gender	Feature	Categorical	Gender			no
Age	Feature	Continuous	Age			no
Height	Feature	Continuous				no
Weight	Feature	Continuous				no
family_history_with_overweight	Feature	Binary		Has a family member suffered or suffers from overweight?		no
FAVC	Feature	Binary		Do you eat high caloric food frequently?		no
FCVC	Feature	Integer		Do you usually eat vegetables in your meals?		no
NCP	Feature	Continuous		How many main meals do you have daily?		no
CAEC	Feature	Categorical		Do you eat any food between meals?		no
SMOKE	Feature	Binary		Do you smoke?		no
CH2O	Feature	Continuous		How much water do you drink daily?		no
SCC	Feature	Binary		Do you monitor the calories you eat daily?		no
FAF	Feature	Continuous		How often do you have physical activity?		no
TUE	Feature	Integer		How much time do you use technological devices such as cell phone, videogames, television, computer and others?		no
CALC	Feature	Categorical		How often do you drink alcohol?		no
MTRANS	Feature	Categorical		Which transportation do you usually use?		no
NObeyesdad	Target	Categorical		Obesity level		no


## Class Labels

Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, and Obesity Type III
