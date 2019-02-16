# DI_Project

Predicting future growths and employment trends of companies from different industrial fields by machine learning
1. Extract time-dependent increasing rates (%) of followers and employees of multi-field companies from Linkedin data as features, and regard the industrial field which these companies belong to as labels.
2. Use the above-labeled data to train machine learning classification models (for example, Logistic regression, fully connected layer neural networks, etc.) to classify which industrial field a company belongs to. Compare these models through test data according to accuracy.
3. For a specific industrial field, use the above time-dependent growth information for different companies in this field to train machine learning models (for example, linear regression, fully connected layer neural networks, and even convolutional neural networks, CNN) to predict a company's future growth and employment trend. Compare these models through test data according to mean square errors (MSE).
4. Apply the above two series models to first classify which industrial field a company belongs to and then to predict how its employment trend is going to be in the future, based on the latest data which could be scraped from Linkedin. 

As for now, step 1, which aims to extract the time-dependent increasing trends of followers and employees of multi-field companies from Linkedin data, has been partly finished. Chart 1 and 2 are two example figures to show this. The first chart illustrates the time-dependent increasing rates of followers of six different investment banking companies, and the second chart illustrates the time-dependent increasing rates of employees of seven different restaurant companies. 
