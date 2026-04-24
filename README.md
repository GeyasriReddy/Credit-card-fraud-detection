#  Credit Card Fraud Detection using Machine Learning

## Project Overview
Credit card fraud is a critical problem in the financial industry, leading to billions of dollars in losses every year. Detecting fraudulent transactions is challenging due to the highly imbalanced nature of the data and the evolving patterns of fraud.
This project focuses on building a machine learning-based solution to identify fraudulent credit card transactions. By analyzing historical transaction data, the system learns patterns that differentiate legitimate transactions from fraudulent ones.

##  Objectives
- Develop a model to detect fraudulent transactions  
- Perform detailed data analysis to understand transaction behavior  
- Apply preprocessing techniques to improve data quality  
- Train and compare multiple machine learning algorithms  
- Evaluate models using appropriate performance metrics  

##  Methodology

###  1. Data Collection
The dataset consists of anonymized credit card transaction records with multiple numerical features and a target variable indicating fraud.

###  2. Data Preprocessing
- Loaded dataset using **Google Drive integration in Google Colab**  
- Checked for missing values and data consistency  
- Performed feature scaling to normalize data  
- Prepared training and testing datasets  

###  3. Exploratory Data Analysis (EDA)
EDA was performed to gain insights into the dataset:
- Distribution of transaction amounts  
- Comparison between fraudulent and non-fraudulent transactions  
- Correlation analysis using heatmaps  
- Visualization using histograms and plots  

###  4. Model Development
Multiple classification algorithms were implemented to compare performance:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

Each model was trained on the dataset and evaluated to determine its effectiveness in detecting fraud.

###  5. Model Evaluation
The models were evaluated using the following metrics:

- **Accuracy** – Overall correctness of the model  
- **Precision** – How many predicted frauds are actually fraud  
- **Recall** – Ability to detect actual fraud cases  
- **ROC-AUC Score** – Overall model performance  

Special focus was given to **Recall**, as missing a fraudulent transaction can be costly.

##  Key Findings
- The dataset is **highly imbalanced**, with very few fraudulent transactions compared to legitimate ones  
- Tree-based models like Random Forest perform better in capturing fraud patterns  
- High recall is essential to minimize false negatives (missed fraud cases)  

## Technologies & Tools
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **Visualization:** Matplotlib, Seaborn  
- **Platform:** Google Colab  
- **Storage:** Google Drive (for dataset access)  

##  Dataset Information
- Contains anonymized transaction features  
- Includes a binary target variable:
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction  
- Loaded directly from **Google Drive** in the notebook  

##  How to Run the Project

1. Open the notebook in Google Colab  
2. Upload the dataset to your Google Drive  
3. Mount Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')

  ##  Dataset
The dataset used in this project is publicly available on Kaggle:

##  Dataset
The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


