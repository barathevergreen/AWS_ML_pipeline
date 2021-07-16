### Dataset: 
#### Kaggle: Women's E-Commerce Clothing Reviews
https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews

#### AWS ML Pipeline: 
#### 1.Ingest, Register and Transform: 
- Register - boto3
- AWS Data Wrangler - Pandas
- AWS Glue - CSV data with AWS Glue Catalog
- Athena - SQL queries from Athena

#### 2.Data Bias - SM Clarify
- Class Imbalance
- SM Clarify Processing Job
- Cloud Watch for Logs
- Balance Data Bias and Rerun Processing Job
- Bias Report generation

#### 3.Model Training - SM Auto Pilot
- Autopilot Job configuration
- automl.fit - Launch Job
- Tracking and Review
- View generated notebooks
- Feature Engineering
- Model Training 
- Hyperparameter Tuning
- Candidate model comparisons
- Deploy and Test

#### 4.SM Blazing Text - NLP Classifier - Built in Algorithm:
- Load and Transform Dataset, Tokenize
- Train Test Validations Split
- Model Training
	- Set Container Image
	- Estimator instance
	- Train data Channel
	- Validation data channel
- Cloud Watch Logs
- Deploy and Test
