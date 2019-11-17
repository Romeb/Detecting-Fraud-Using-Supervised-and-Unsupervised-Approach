# Detecting-Fraud-Using-Supervised-and-Unsupervised-Approach
Supervised and Unsupervised Approach to Detecting Fraud

Previously I took the approach in using Superised Learning to detect fraud. A new approach I have taken is by using Supervised and Unsupervised learning combined to detect fraud. The approach was used on the same Kaggle credit card dataset (https://www.kaggle.com/mlg-ulb/creditcardfraud) and a Transfers Dataset from Datacamp. Both datasets had a imbalance problem, so I took the approach in using SMOTE, under-sampling, over-sampling and ROSE to tackle this issue. 

To implement Unsupervised learning into the fraud detection model I used K-means Clustering. K-means clustering was implemented in SAS, I have attached the code used in PDF format. 

I used h2o to implement the Supervised approach, using the open source machine learning library saved me valuable time in finding the best algorithm and parameters to use. 

To finalize, the supervised approach for detecting fraud on the SMOTE credit card dataset achieved 65% whereas the supervised and unsupervsied approach achieved 67%. 

The transfers dataset supervised approach achieved 72% whereas the supervised and unsupervised approach achieved 71%
