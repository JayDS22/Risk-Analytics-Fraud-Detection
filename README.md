# Risk-Analytics-Fraud-Detection
Built an End to End Data Science project to analyze the risk of Fraud transactions and create a predictive model to prevent it.

# Credit Card Fraud Detection :credit_card:	

### :bulb: About the Project

The Problem Statement for the Project was to use Data Science & Machine Learning to recognize Fraudulent credit card transactions so that the customers are not charged for items that they did not purchase. 

### :notebook_with_decorative_cover: About the Dataset

The dataset was downloaded from Kaggle which contains transactions made by credit cards in September 2013 by European cardholders. Due to confidentiality issues and to protect the Identity of the Users, the original features were replaced by performing a PCA transformation on the data. The Target feature contains 1 in case of a Fraud Transaction and 0 otherwise.

Dataset Link: https://www.kaggle.com/mlg-ulb/creditcardfraud

### :open_book:	Highlights from the Dataset

- There aren't any missing values present to deal with
- All the Predictors are continuous in nature
- The dataset is highly imbalanced; the positive class (Frauds) account for only 0.172% of all transactions
- The Predictors aren't much informative to gain extra insights from the data as a result of PCA transformation

### :black_nib: Highlights from the Project

- Visualized the Imbalance nature of the dataset by performing Exploratory Data Analysis (EDA)
- Performed Random Oversampling using the Imblearn library and created extra data values in place of the existing data points
- Made sure that all the Pre-processing steps are performed separately for Training & Testing Datasets
- Trained the Resampled Data using 2 Ensembling ML models: RandomForest Classifier & XGBoost Classifier
- XGBoost model provided better results, so tuned the Hyperparameters of the same using RandomizedSearchCV
- Plotted the Performance Metrics of every model :chart:	
