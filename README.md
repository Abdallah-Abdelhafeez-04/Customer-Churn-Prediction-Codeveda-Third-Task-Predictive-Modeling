# Customer-Churn-Prediction-Codeveda-Third-Task-Predictive-Modeling
The goal of this project is to **predict customer churn** (whether a customer leaves or stays with the company) using a dataset of customer call and service usage patterns. The project aimed to analyze telecom customer data to identify who is likely to churn — empowering businesses to act early and retain customers.

By leveraging **machine learning models**, we provide insights that help businesses:
- Identify at-risk customers
- Improve customer retention strategies
- Enhance decision-making with data-driven insights

---

## 📊 Dataset
- **Source:** `churn-bigml-20.csv`
- **Rows:** 3333  
- **Target Variable:** `Churn` (Yes/No)  
- **Key Features:**
  - Customer demographics (`State`)  
  - Service plans (`International plan`, `Voice mail plan`)  
  - Usage patterns (`Total day/eve/night minutes`, `Total calls`, `Total charges`)  
  - Customer service interactions  

---

## 🛠️ Workflow
1. **Data Preprocessing**
   - Handled categorical variables (label encoding)
   - Feature scaling (StandardScaler)
   - Train/test split

2. **Exploratory Data Analysis**
   - Distribution of churn vs. non-churn customers
   - Correlation between features
   - Visualization of important patterns

3. **Modeling**
   - Trained multiple classifiers:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Gradient Boosting
     - Support Vector Machine (SVM)
   - Hyperparameter tuning with GridSearchCV

4. **Evaluation**
   - Metrics used:
     - Accuracy
     - Precision
     - Recall
     - F1-score
     - ROC Curve & AUC
   - Feature importance analysis

---

## 🚀 Results
- **Gradient Boosting** and **Random Forest** performed the best with **high accuracy and AUC scores**, making them reliable for churn prediction.  
- Insights:
  - Customers with **high customer service calls** are more likely to churn.  
  - International plan users also show a higher churn probability.  

---

## 📈 Visuals
- Confusion Matrix
- ROC Curves
- Feature Importance plots

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

---

## 📌 Key Takeaways
- Customer churn prediction is crucial for businesses to reduce losses.  
- Identifying **early warning signals** in customer behavior can improve retention strategies.  
- Ensemble models (like Random Forest, Gradient Boosting) outperform simple models.

---

▶️ How to Run on Google Colab

Open the Notebook in Colab
Upload the file Codeveda Third Task.ipynb to your Google Drive.
Or open directly in Colab:

Go to Google Colab

Click File > Upload Notebook and select the .ipynb file.

Install required libraries
In the first cell of Colab, run:

!pip install pandas numpy scikit-learn matplotlib seaborn

Upload your dataset

Run all cells
Go to Runtime > Run all.
The notebook will:

Preprocess the data

Perform EDA

Train & evaluate machine learning models

Show visualizations of results


---

👨‍💻 **Author:** Abdallah Abdelhafeez  
📅 Internship Project — Codeveda Technologies (2025)
