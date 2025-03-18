# 📊 Telco Customer Churn Prediction  

## 🚀 Overview  

This project uses **machine learning** to predict **customer churn** for a telecommunications company. It applies **data preprocessing, feature selection, dimensionality reduction, and model evaluation** to help businesses identify **at-risk customers** and take proactive measures to **improve retention**.  

## 📂 Dataset  

The dataset is obtained from **[Kaggle: Telco Customer Churn](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset/data)** and contains **7,043 customer records** with features related to demographics, service subscriptions, billing, and churn labels.  

## 🏗️ Project Workflow  

- **Data Preprocessing:** Handling missing values, encoding categorical variables, and scaling numerical features.  
- **Feature Selection:** Comparing **SelectKBest (5 features)** vs. **PCA (15 components)** to optimize model performance.  
- **Handling Imbalance:** Using **SMOTE** to balance the dataset.  
- **Model Training & Evaluation:** Testing multiple classifiers (**KNN, Decision Tree, Random Forest, Gradient Boosting, and XGBoost**) and fine-tuning them with **GridSearchCV**.  
- **Comparison:** Evaluating models with and without **PCA**, analyzing accuracy, precision, recall, and F1-score.  

## 🏆 Key Findings  

- **XGBoost consistently achieved the highest accuracy** (~96.6%), proving its effectiveness in predicting churn.  
- **SelectKBest vs. PCA:** PCA retained more data, but SelectKBest provided strong accuracy with fewer features, making it more efficient.  
- **Feature Importance:** Online Security, Tech Support, Contract, Churn Score and Churn Reason were key predictors of churn.

## 🔧 Dependencies
This project utilizes various Python libraries, all of which are listed and used within the notebook.

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgments
A big thank you to [Kaggle](https://www.kaggle.com) for providing the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset/data), and to everyone who contributed to making this project possible.
