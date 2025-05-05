## DIABETIC_HEALTH_INDICATORS

## Overview

This project aims to analyze and predict diabetes outcomes using data from the Behavioral Risk Factor Surveillance System (BRFSS) 2015 survey. This dataset, collected by the Centers for Disease Control and Prevention (CDC), contains responses from 253,680 individuals across the United States, providing valuable insights into lifestyle choices, healthcare accessibility, and health-related risks. By employing machine learning techniques, the project seeks to identify significant predictors of diabetes and evaluate the performance of predictive models.

## Dataset Details

Source / Dataset link: https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

The dataset originates from the BRFSS, a health-related telephone survey conducted annually by the CDC since 1984. The 2015 dataset used in this project includes:

Number of Instances: 253,680

Number of Features: 21

Target Variable: Diabetes_binary

0.0: Non-diabetic (negative class)

1.0: Diabetic (positive class)

## Features

The dataset includes:

Demographic attributes (e.g., age, gender, income level)

Lifestyle factors (e.g., physical activity, smoking status, alcohol consumption)

Healthcare accessibility metrics (e.g., health insurance status)

Chronic health indicators (e.g., BMI, blood pressure levels)

## Objective

The primary objective of this project is to:

Build a machine learning model to predict diabetes outcomes based on the survey data.

Identify key features that influence diabetes prediction.

Address challenges such as class imbalance to ensure robust and fair model performance.

Provide actionable insights for healthcare practitioners and policymakers to design effective interventions.

## About Columns:

Diabetes_binary : you have diabetes (0 = no diabetes | 1 = prediabetes or diabetes)

HighBP : Adults who have been told they have high blood pressure by a doctor, nurse, or other health professional (0 = no high BP | 1 = high BP)

HighChol : Have you EVER been told by a doctor, nurse or other health professional that your blood cholesterol is high? (0 = no high cholesterol | 1 = high cholesterol)

CholCheck : Cholesterol check within past five years (0 = no cholesterol check in 5 years | 1 = yes cholesterol check in 5 years)

BMI : Body Mass Index

Smoker : Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes] (0 = no | 1 = yes)

Stroke : (Ever been told) you had a stroke. (0 = no | 1 = yes)

HeartDiseaseorAttack : Respondents that have ever reported having coronary heart disease (CHD) or myocardial infarction (MI) (0 = no | 1 = yes)

PhysActivity : Adults who reported doing physical activity or exercise during the past 30 days other than their regular job (0 = no | 1 = yes)

Fruits : Consume Fruit 1 or more times per day (0 = no | 1 = yes)

Veggies : Consume Vegetables 1 or more times per day (0 = no | 1 = yes)

HvyAlcoholConsump : Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week)(0 = no | 1 = yes)

AnyHealthcare : Do you have any kind of health care coverage, including health insurance, prepaid plans such as HMOs, or government plans such as Medicare, or Indian Health Service? (0 = no | 1 = yes)

NoDocbcCost : Was there a time in the past 12 months when you needed to see a doctor but could not because of cost? (0 = no | 1 = yes)

GenHlth : Would you say that in general your health is: rate (1 ~ 5) (1 = excellent | 2 = very good | 3 = good | 4 = fair | 5 = poor)

MentHlth : Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days was your mental health not good? (0 ~ 30)

PhysHlth : Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good? (0 ~ 30)

DiffWalk : Do you have serious difficulty walking or climbing stairs? (0 = no | 1 = yes)

Sex : Indicate sex of respondent (0,1) (0 = female | 1 = male)

Age : Fourteen-level age category (1 ~ 14) (1 = 18-24 | 2 = 25-29 | 3 = 30-34 | 4 = 35-39 | 5 = 40-44 | 6 = 45-49 | 7 = 50-54 | 8 = 55-59 | 9 = 60-64 | 10 = 65-69 | 11 = 70-74 | 12 = 75-79 | 13 = 80 and older)

Education : What is the highest grade or year of school you completed? (1 ~ 6) (1 = Never attended school or only kindergarten | 2 = Grades 1 through 8 (Elementary) | 3 = Grades 9 through 11 (Some high school) | 4 = Grade 12 or GED (High school graduate) | 5 = College 1 year to 3 years (Some college or technical school) | 6 = College 4 years or more (College graduate))

Income : Is your annual household income from all sources: (If respondent refuses at any income level, code "Refused.") (1 ~ 8) (1 = <10000 | 2 = <15000 | 3 = <20000 | 4 = <25000 | 5 = <35000 | 6 = <50000 | 7 = <75000 | 8 = 75000 and more)
