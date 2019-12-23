# Predicting Churn - Sparkify Music Platform
-------
##### Please Checkout my [Blog Post]() for Detailed Documentation
------

## Project Definition
Sparkify is a digital music service where users stream music just like Spotify or Pandora. Users can stream music using a free tier with ads or a paid subscription that has a monthly flat fee with no ads. Service users can upgrade from free tier, downgrade to free tier or Cancel the service.

The problem that Sparkify faces is that their customers are likely to cancel or downgrade their service leading to Customer churn. The objective therefore is to predict customer churn in advance by explolatory analysis on user activities and machine learning to identify users who are likely to Cancel the service (churn) and with this the business can offer them discounts and other marketing incentives to keep them in the platform.

I have used spark to explore user activities and Random Forest Classifier to predict customer churn

#### Data
The data provided consists of logs that contain user information, demographics and user interactions with the platform. We will generate features from this data set to train a classification model
#### Model Performance Metrics
To ensure an optimal performing model, we will use  **Accuracy Score** and **F1 Score** metrics to measure performance
f1 score is the optimal metric for a small dataset since it is the weighted average of precision and recall it takes both false positives and false negatives into account

### Methodology
Below are the steps we 'll follow;
1. Data Extraction
2. Data Exploration
3. Customer Churn Definition
4. Feature Engineering
5. Modeling
6. Model Evaluation

### Tools Used
- Pyspark
- Amazon EMR service - 3 instances
- Jupyterlab - Pyspark Kernel
- Pyspark Documentation & Stackoverflow - for most of the debugging research