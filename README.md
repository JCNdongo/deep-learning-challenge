## Deep Learning Challenge Summary

This project consisted of creating a tool using neural networks and machine learning to help a funder predict which venture to invest in based on their success rates. The data was provided in a .csv file with 34299 rows and the following 12 variables (columns): EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, and IS_SUCCESSFUL.

#Data Preprocessing:

After opening the file on Pandas, I dropped the ventures' unique identifiers (or features), which were the variables (columns) EIN and NAME, to remove bias toward or against any of the ventures and make the process of determining which venture to fund equitable and scientifically-based.
I determined the number of unique values for each remaining variable with "APPLICATION_TYPE" and "CLASSIFICATION" as my target variables; the remaining variables were neither targets nor features. Further, I standardized the data by converting categorical data into a numerical form and created testing and training datasets to analyze the data.

#Model Compilation, Training, and Evaluation:
I defined the model for analysis by determining the number of input features and hidden nodes per layer. I trained the model and tested its fitness through multiple iterations.  

#Findings:
The project's preferred accuracy score of 75% was not attained; however, a score of 72% was attained after multiple iterations of the model. A different classification model could be used for future attempts at increasing the accuracy score. 
