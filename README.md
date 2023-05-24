# TelecomChurn_PredictionModel

# Probelm Definition 
The goal of this project is to develop a predictive model that can estimate churn Prediction and also evaluate reason for churing. Based on input variables. The The Random Forest Technique is found to be effective technique to predict the churn prediction.

# Dataset Link - 
URL = "https://raw.githubusercontent.com/chandanc5525/Dataset/main/Data/"

df = pd.read_csv(URL + 'telecom_churn.csv')


# Dataset Information -
   Column                  Non-Null Count    Dtype  
   ---------              --------------     -----  
 0   State                   3333 non-null   object 
 
 1   Account length          3333 non-null   int64  
 
 2   Area code               3333 non-null   int64  
 
 3   International plan      3333 non-null   object 
 
 4   Voice mail plan         3333 non-null   object 
 
 5   Number vmail messages   3333 non-null   int64  
 
 6   Total day minutes       3333 non-null   float64
 
 7   Total day calls         3333 non-null   int64  
 
 8   Total day charge        3333 non-null   float64
 
 9   Total eve minutes       3333 non-null   float64
 
 10  Total eve calls         3333 non-null   int64  
 
 11  Total eve charge        3333 non-null   float64
 
 12  Total night minutes     3333 non-null   float64
 
 13  Total night calls       3333 non-null   int64  
 
 14  Total night charge      3333 non-null   float64
 
 15  Total intl minutes      3333 non-null   float64
 
 16  Total intl calls        3333 non-null   int64  
 
 17  Total intl charge       3333 non-null   float64
 
 18  Customer service calls  3333 non-null   int64  
 
 19  Churn                   3333 non-null   bool   
 
# Usage -
To run the project and reproduce the results, follow these steps:

1. Clone the repository:

2. Clone the repository:

3. Execute the main script: python main.py

# Conclusion - 

In this project, we developed a Classification model to predict Telecom Churn Prediction. The model achieved promising accuracy after cross-validation and pruning. By using this model, Telecom companies and individuals can estimate the Churn Causes and also this model helps to make competitive decision-making statergies.
Feel free to customize the README.md file according to your project's specific details and requirements.

# Note - 
For More Information Feel Free to Contact : chaudhari.chandan22@gmail.com 
