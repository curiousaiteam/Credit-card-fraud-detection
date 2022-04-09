# Credit-card-fraud-detection

We try to reduce error i.e. improve accuracy whenever building a machine learning model. But accuracy doesn't consider class imbalance. In everyday scenarios, we find that lot of our data is imbalanced data i.e data belonging to one class is significantly lower than other. 
eg: Detection of rare diseases, fraudulent cyber activities etc.
In such cases, the model tends to predict the class that has more proportion and the accuracy deludes us to believe that it is working well. 
Also, in detection of such anomalies, we cannot afford false negatives.
For example, a person has a rare disease and our model predicts 'not infected' because most of our data belongs to the 'not infected' class.

# Handling imbalanced datasets
Therefore , there are two things that could be done:
1. We can make the data balanced by upsampling or downsampling. But this would mean manipulating the nature of data. So, instead we can find better models which are robust to imbalanced datasets. eg: # Ensemble methods
2. Work with better metrics to understand the capability of the machine learning models instead of just accuracy.
eg: Kappa score takes into account the class distribution. 

