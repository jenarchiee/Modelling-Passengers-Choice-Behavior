# Modelling Passengers' Airport and Airline Choice Behavior

This is my academic project. Data, codes, and report are unable to be published due to privacy. 

## Problem

#### What drives passengers’ choice of airport and airline? 

Two international airports in Seoul Metropolitan Area: 
* Gimpo airport: Smaller and old, but closer to the city 
* Incheon airport: Larger and new hub airport, but farther from the city 

![air](https://user-images.githubusercontent.com/60991189/101312936-e43d0f00-3809-11eb-888c-b53debebcc32.PNG)

We developed models to identify what drives passengers’ choice of airport and airline. 

## Data description

* Data sets: 27 variables from survey data of 488 respondents
   * Airport choice: Gimpo, Incheon
   * Airline choice: Korean Air (KE), Asiana Air (OZ), Korean LCC, Foreign Carriers
   * Socio-demographic: age, gender, occupation, income, etc
   * Alternative-Specific : flight information, travel time, mode of transport, etc
  
## Solution and Results

#### Data Mining Procedure to Identify Passengers' Behavior Pattern  

* Cleaned data, analyzed descriptive statistics, and visualized Exploratory Data Analysis (EDA) utilizing Python. 
* Feature engineering: Re-categorizing variables
    * E.g. Airlines: Korean Carriers vs. Foreign Carriers;
    * E.g. Occupation (re-group 12 categories into 4 categories): Business, Government, Unemployment and Other). 
* Variables selection: Implemented iterative approach (Backward/Forward selection), conducted Correlation analysis, and used Holdout method to split dataset into training and testing set.
* Developed logistic regression and decision tree model, yielding the accuracy rate of 84% for airport model and 72% for airline model. 


