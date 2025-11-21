# 💳 Credit Card Fraud Detection 🚀

This project is an **end-to-end implementation** for detecting fraudulent credit card transactions. The goal is to build a system that can accurately identify suspicious transactions and reduce financial fraud.

💡 **Why this project?**  
Credit card fraud is a major problem worldwide. Detecting fraud early can save banks and customers from significant financial losses. This project uses **Machine Learning** and **Deep Learning** to analyze transactions and detect anomalies.

---

## 🛠️ Project Steps

1. **🗂️ Data Generation:** Created a synthetic dataset with 10,000 transactions. Fraudulent transactions represent 2% of the total dataset.  
2. **📊 Exploratory Data Analysis (EDA):** Checked for missing values, outliers, and correlations. Visualized patterns in fraudulent vs. non-fraudulent transactions.  
3. **⚙️ Data Preprocessing:** Standardized numeric features, split data into training and testing sets using stratified sampling, and handled class imbalance using **SMOTE**.  
4. **🤖 Modeling:** Trained **Machine Learning models** (Logistic Regression, Random Forest, XGBoost) and a **Deep Learning model** using Dense layers and Dropout to reduce overfitting.  
5. **📈 Evaluation:** Used accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC curve to measure performance. Compared models to select the best performing one.

📁 Project Structure

data/                
notebooks/             
src/                  
README.md              
requirements.txt    


📊 Results

Achieved high accuracy in detecting fraudulent transactions.

Deep Learning model ROC-AUC score: 0.98.

Demonstrates how AI can assist in real-world financial fraud detection.

