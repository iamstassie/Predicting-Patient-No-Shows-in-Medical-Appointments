# Predicting-Patient-No-Shows-in-Medical-Appointments

## Overview
Analysis of 110,000+ medical appointments from Brazil's public health system to predict whether a patient will attend their scheduled appointment.

## Problem
No-show rates in public healthcare can reach 20–30%. Each missed appointment means a wasted slot, delayed care, and system cost with no outcome. Predicting likely no-shows allows clinics to prioritise reminders and optimise scheduling.

## What's inside
- Exploratory data analysis with clinical interpretation
- Wait time feature engineering
- Class imbalance analysis
- Logistic regression with train/test split
- Evaluation using recall as primary metric (not accuracy)

## Key findings
- Wait time is one of the strongest predictors: longer waits → more no-shows
- SMS reminders show a counterintuitive pattern explained by selection bias
- Chronic condition patients (hypertension, diabetes) attend more consistently
- Class imbalance (~80/20) makes accuracy a misleading metric for this task

## Stack
Python · pandas · scikit-learn · seaborn · matplotlib

## Dataset
[Kaggle — Medical Appointment No Shows]

## Notebook
Full analysis also available on [Kaggle] <www.kaggle.com/code/iamstassie/predicting-patient-no-shows-in-medical-appointment>
