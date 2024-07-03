# Patients Health Analysis using Machine Learning


## Project Overview
This project explores the application of machine learning techniques in analyzing patient health data to improve healthcare outcomes. The primary objective is to develop a predictive model that can forecast patient health conditions based on a variety of input features such as heart rate, body mass index (BMI), and temperature.

## Table of Content
1. [Introduction](#Introduction)
2. [Data Description](#Data-Description)
3. [Project Structure](#Project-structure)
4. [Installation](#Installation)
5. [Data Preprocessing](#Data-preprocessing)
6. [Machine Learning](#Machine-Learning)
7. [Classifiers](#Classifiers)
8. [Prediction](#Prediction)
9. [Results](#Results)

## Introduction
- As technology advances, vast improvements have been made in the medical field. It is important to know the health status of the patient.
- A proper analysis is needed to find the root cause of the death. Many researchers use their own method to assess the patient's health. However, in this we show how to analyze the patient’s health using the latest data science and machine learning tools and provide insights from that analysis.

## Data-Description
The data is collected from HealthData.gov, a U.S. government health data repository, to take the data as input
- age
- gender
- basic heatlth reading

## Project-Structure
- Home
- User
  - Data View
  - [ML](#Machine-Learning)
    - data preprocessing
    - train
    - test
  - Prediction
- Admin
  - User Details
- Register
  - User Registration Form

## Installation
- **Install Django**
  - `pip install django`
- **Installing requirements.txt**
  - `pip install -r requirements.txt`
    - Use the above command to install the packages listed in the requirements file.
- **Runserver**
  - `py manage.py runserver`
    - Use the above command to start the server.
   
## Data-Preprocessing
- Data Collection
- filter data
  - filter data based on the country code, rename columns, drop unnecessary columns, and convert the DataFrame to HTML.
- Render Template

## Machine-Learning
- Data collecton
  - Imputing missing values
  - Normalizing and scaling features
  - Encoding categorical variables
  - Initializes a dictionary classifiers containing different machine learning models
- Model Training
  - Train the Classifier
  - Make Predictions
  - Calculate Accuracy
  - Generate Classification Report
  - Generate Confusion Matrix for each classifier
- Model Testing
  - Stores the accuracy
  - plot confusion matrix
  - save the plot
  - display
 
## Classifiers
- RandomForestClassifier
- RidgeClassifier
- ExtraTreesClassifier
- LogisticRegression
- GradientBoostingClassifier
- AdaBoostClassifier
- KNeighborsClassifier
- GaussianNB
- DecisionTreeClassifier
- XGBClassifier

## Prediction
- Takes the data given
- shows the condyion of the patient

## results
- **Home Page**
  ![Home Page](media/patienthome.png)
- **Admin Page**
  ![Admin Login](media/patientadminlogin.png)
  ![Admin Home](media/patientadminhome.png)
  ![User Details](media/patientuserdetails.png)
- **User Page**
  ![User Login](media/patientuserlogin.png)
  ![User Home](media/patientuserhome.png)
- **User Registration**
  ![User Register Form](media/patientuserregister.png)
- Confusion matrix
  ![AdaBoostClassifier](confusion_matrix_AdaBoostClassifier.png)
  ![DecisionTreeClassifier](confusion_matrix_DecisionTreeClassifier.png)
  ![ExtraTreesClassifier](confusion_matrix_ExtraTreesClassifier.png)
  ![GradientBoostingClassifier](confusion_matrix_GradientBoostingClassifier.png)
  ![KNeighborsClassifier](confusion_matrix_KNeighborsClassifier.png)
  ![LogisticRegression](confusion_matrix_LogisticRegression.png)
  ![NaiveBayes](confusion_matrix_NaiveBayes.png)
  ![RandomForestClassifier](confusion_matrix_RandomForestClassifier.png)
  ![RidgeClassifier](confusion_matrix_RidgeClassifier.png)
  ![XGBoostClassifier](confusion_matrix_XGBoostClassifier.png)
- classifer scores
  ![score](media/patientalgo1.png)
  ![score](media/patientalgo2.png)
  ![score](media/patientalgo3.png)
- Data set
  ![data set](media/patientdataset.png)
- **Crime Prediction**
  ![prediction](media/patientprediction.png)
