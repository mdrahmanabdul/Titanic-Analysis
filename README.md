# Titanic Survival Prediction
This project aims at predicting who has survived based on various features(independent variables) using machine learning algorithms.

# Project Overview
The Titanic dataset is well-known dataset that contains information about passengers on the Titanic, including their fair price,Pclass,Embarked and whether they survived or not. The mail goal of this project is to build a ML model that can predict the survival of the passengers based on the features that are available.

# Technologies Used
 1.Python 
 2.Jupyter Notebooks<br>    
 3.Pandas<br>    
 4.Numpy<br>    
 5.Matplotlib<br>     
 6.Seaborn<br>    
 7.scikit-learn<br>    

# Dataset Description
The Titanic dataset contains two files : 'attachment_titanic.csv' and 'test.csv'. The 'attachment_titanic.csv' file contains the training set, which includes passenger information along with their survival outcome. The 'test.csv' file contains the test set, where the outcome is not provived. The dataset can be obtained from [Kaggle](https://www.kaggle.com/competitions/titanic/data)

# Key Findings and Insights
After exploring and analyzing the dataset, the following key findings and insights were discovered :
> There is correlation between passenger class and survival, with passengers with first-class survived more.  
> Females have higher chance of survival.  
> Passengers with higher fare tickets also have higher chances of survival.  
> Age also plays crucial role in chances of survival of the passenger. Childrens have survived the more.   

# Data Visualizations 
To illustrate the insights gained from the analysis, various data visualizations were created, including : 
- Barplot : To show the survival rate based on passenger gender, class, Age and fare price.
- Boxplot : To find any outliers in the data and also to know the mean range
- Countplot : To see the count of people based on gender and also to see the of how many of them survived
- heatmap : To find the correlation amoong the features
- Swarmplot : To find any outliers in the data
- Tree : To get an idea how the decision tree is working internally

# Model building and Prediction 
Two machine learning models were trained on the Titanic dataset for predicting the survival : 
1. DecisionTreeClassifier
2. RandomForestClassifier

# How to Run the Notebook 
To run this jupiter notebook in your local environment follow the below steps : 
1. Clone the repo
2. Install necessary dependencies including scikit-learn,Pandas,Numpy,Matplotlib and seaborn. It is good to have anaconda installed where you can open jupiter notebooks very easily without messing up it in the terninal/command-prompt if you don't have any idea about command prompt or terminal.
3. Open the jupiter notebooks and change the path of the dataset to where you have downloaded it.
4. Run all the cells in the jupiter notebooks in sequential manner.

# Author 
Name : Mohammed Abdul Rahman  <br> Linkedin : [Mohammed Abdul Rahman](https://www.linkedin.com/in/rahmanabdul003/)

# License 
This project is under Eclipse Public License 2.0

