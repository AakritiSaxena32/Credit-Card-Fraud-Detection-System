# Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions.

## What It Does
This project builds a system that can tell if a credit card transaction is real or fake, so people don't get charged for things they didn't buy.

## How It Works
1. I downloaded a dataset from Kaggle with 284,807 transactions
2. The data was split into training (80%) and testing (20%) sets
3. A Random Forest model was trained on this data
4. The model was tested to see how well it finds fraud

## Results
- **Accuracy**: 99.96% (Overall correctness)
- **Precision**: 97.47% (When it says "fraud", it's usually right)
- **Recall**: 78.57% (It catches 78.57% of actual fraud cases)
- **F1 Score**: 86.96% (Balance between precision and recall)

## Files
- `credit.ipynb` - The main notebook with all the code
- `README.md` - This file

## How to Run
1. Upload your `kaggle.json` file when the notebook asks
2. Run all cells in the notebook
3. The notebook will download the data and train the model automatically

## What's Next
The model is good at not flagging real transactions as fraud, but could be better at catching actual fraud. Future work could try different methods to handle the class imbalance.