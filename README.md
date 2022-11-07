# ADS-508
Data Science with Cloud Computing

### Background 
This is a simulation of a real life business case that can benefit from the use of AWS SageMaker AutoML and machine learning models to improve the performance of the company.
### Problem Statement
A fictional company (Stream Co.) that focuses on streaming services is experiencing high customer turnover rates and revenue loss due to the unsatisfactory of user experience. The goal is to improve the accuracy of the prediction in order to focus on understanding the psychological and demographic factors in order to provide recommendation systems and better investment strategies in terms of licensing and original programming.

### Data Sources:
The source data mainly comes from the backend on the server internally from Stream Co. Since the data is single-sourced, we are facing potential risks of impurity of the data and lack of diversity on the data. We can see that in these data we don’t have enough information on the diversity of customers such as age, race, gender and occupation, etc to form a complete demographics / psychographics mapping. Without having other complementary data from other sources, we are risking having an underfitting final predictive model(s).
The data will be stored in Amazon S3 buckets by manual uploading in this case(Ideally it would be written to AWS Kinesis for instant ingestion or use AWS Glue Crawler for continuous ingestion), and queried and processed in Amazon SageMaker AutoML.

### Road map
- Data Preparation
- Data Exploration
- Model Training
- Future Improvement
  - Model Performance
  - Model Deployment
  - Performance Monitoring
