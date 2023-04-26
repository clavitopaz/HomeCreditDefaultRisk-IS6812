# HomeCreditDefaultRisk-IS6812
Exploratory Data Analysis and Modeling for Home Credit Capstone Project

# [Home Credit EDA: Results Overview](https://clavitopaz.github.io/HomeCreditEDA/)
- Identified predictive power in customer data that is 'NA'. However, we removed the normalized housing data as there was too many NA fields in their columns, and we may not be able to extract any useful information from that data if we find any correlations.

- In reviewing the number and percentage of contracts for each customer by contract type, family status, car ownership, etc., we got a better idea of the makeup of our customer base. It seems that customers with trouble paying off their loan (in majority) own realty, make on average $160,000, are married and have no children. 

- We've made note to not explore gender as a predictive power for our project. Note - we have more women customers than men!

- If I had more time, I would have segmented the normalized housing dataset for all non-"NA" fields. It would have been interesting to see if there were any stark differences from that dataset to the one we explored in this assignment. 

- This EDA project has gotten me to feel more comfortable in using R. I have been able to create my own plots andI've pivoted and mutated many data tables. This also has given me more appreciation for performing EDA for a project - as it provides the user value in understanding the dataset before executing a project.

# Home Credit Modeling: Results Overview
- I was able to create a predictive model using Random Forest that was close to Accuracy and ROC-AUC of the testing dataset. This model will be able to predict characteristics of a customer who may have issues paying their loan based off the information in this dataset.

- I believe it would have been more useful to use other datasets like installment payments or credit bureau information when running the final model. However, for the sake of time, we only used the application_train dataset.

- In conclusion, going forward I feel better equipped to identify which model should be ran for predictive purposes. I also feel like my coding skills have signficantly improved, as well as my interpretation of the metrics.

# Capstone Presentation
- Powerpoint presentation of Exploratory Data Analysis and Modeling by myself and Biva Sherchan.
