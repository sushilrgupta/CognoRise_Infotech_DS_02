# CognoRise_Infotech_DS_02

# Credit Card Fraud Detection

## Task 2: 
Develop a machine learning model designed to detect fraudelent credit card transactions. Train a classification algorithm—like logistic regression or random forests—to differentiate between fraudulent and legitimate transactions. • Assess the model's efficacy using metrics such as precision, recall, and F1-score. Additionally, explore strategies like oversampling or undersampling to enhance outcomes and refine the model's performance.

## Project Overview:
In an era where digital transactions are becoming increasingly prevalent, ensuring the security of financial transactions is paramount. This project aimed to develop a robust model to identify fraudulent credit card transactions and enhance risk management strategies.

## Dataset Information
- **Source:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Files in this Repository
- `CognoRise_Credit_Card_Fraud_Detection.ipynb`: Jupyter Notebook containing the analysis.
- `README.md`: Documentation for the analysis.
- `creditcard.csv`: Train and Test Dataset.

## Analysis Highlights

1. **Exploratory Data Analysis (EDA):**
   - Explored the distribution of key variables (age, gender, class).
   - Investigated survival rates across different categories.
  
2. **Data Visualization:**
   - Used matplotlib and seaborn for data visualization
 
3. **Data Preprocessing:**
   - Applied techniques such as feature scaling like RobustScaler() and handling imbalanced data using Randomoversampling and Randomundersampling.

4. **Model Used:**
   - Employed a Random Forest Regressor for its ability to handle imbalanced datasets and robustness against outliers

5. **Classification Matrix:**
   - Utilized metrics like accuracy, precision_score, recall_score, and f1_score to assess the performance of the model.
  
## Key Findings

-	Discovered that imbalanced datasets are common in credit card fraud detection, emphasizing the need for careful handling of skewed class distributions.
-	Highlighted the importance of model interpretability for stakeholders to gain insights into fraud prediction factors.


## Running the Analysis
1. Install required libraries: `pip install -r requirements.txt`
2. Open and run the Jupyter Notebook: `jupyter notebook CognoRise_Credit_Card_Fraud_Detection.ipynb`

## Contributions and Issues
Feel free to contribute to the analysis or report any issues. Pull requests are welcome!

## Author
[Sushil Gupta]
