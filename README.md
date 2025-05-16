# 🔍 Predicting PCOS Diagnosis from Clinical Data

**Author:** Jane Zulu  
**Course:** BANA 7365 - Predictive Modelling  
**Date:** April 13, 2025  

## 📌 Overview
Polycystic Ovary Syndrome (PCOS) affects 1 in 10 women of reproductive age but is often underdiagnosed due to vague and inconsistent symptoms. This project applies machine learning techniques to structured clinical data to build a predictive model that supports early and accurate PCOS detection — even in unclear cases.

## 🧠 Project Goals
- Improve diagnostic accuracy for PCOS using clinical variables.
- Build a data-driven model that minimizes false negatives.
- Provide an accessible, scalable tool for clinical decision support.

## 📊 Dataset
- **Source:** [Kaggle - PCOS Diagnosis Dataset](https://www.kaggle.com/datasets/samikshadalvi/pcos-diagnosis-dataset)
- **Size:** 1,000 patient records  
- **Features:** BMI, Age, Menstrual Irregularity, Testosterone Level, Antral Follicle Count  
- **Class Balance:** 80% Non-PCOS / 20% PCOS

## ⚙️ Methodology
- Baseline: Logistic Regression
- Final Model: **Gradient Boosting Classifier**
- Techniques: Cross-validation, Hyperparameter Tuning, Feature Importance Analysis

## 🚀 Results
- **Accuracy:** 99.6%  
- **Recall:** 98%  
- **Precision:** 100%  
- False negatives reduced from 32 (baseline) to 1 with Gradient Boosting.

## 🔍 Key Features Driving Prediction
- **BMI (34%)**
- **Testosterone Level (24%)**
- **Menstrual Irregularity (22%)**
- **Antral Follicle Count (18%)**

## 🧭 Future Work
- Validate in real-world clinical settings.
- Develop a user-friendly interface for medical practitioners.
