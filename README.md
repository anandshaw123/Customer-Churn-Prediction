# Customer-Churn-Prediction-Analysis



![Customer-Churn-Prediction](https://github.com/user-attachments/assets/60915fc4-db38-44a9-8962-2bfa7c397c6d)






## **Objective**
The primary objective of this project was to analyze **Customer churn** and find which **churn's** are active or not and build **ML Model** to derive actionable insights and provide data-driven recommendations. The project involved several key phases: **Exploratory Data Analysis (EDA)** , **Feature Engineering & Modelling** , and **Findings & Recommendations.**


## **Tools**
#### The project utilized the following tools and technologies:

**Python:** Programming language for data analysis and modeling.

**Pandas:** For data manipulation and cleaning.

**NumPy:** For numerical operations.

**Matplotlib and Seaborn:** For data visualization.

**Scikit-Learn:** Importing the libraries for build Machine Learning model.

**Machine Learning** Using Machine Learning Algorithm to Build Prediction model.


```
├── data/
│   ├── Client_Data/
│   └── Price_Data/
|
|
├── notebooks/
│   ├── Churn_Prediction_Model.ipynb/
|
|
├── Exploratory_Data_Analysis_(EDA)/
│   ├── Data_quality_checks/
│   └── Missing_Values/
│   ├── Duplicates/
│   └── Univariate_Analysis/
│   ├── Churn_distribution/
│   └── Customer_business_split/
│   ├── Bivariate/Multivariate Analysis/
│   └── Tenure_vs_Churn/
│   ├── Monthly_charges_vs_Churn/
│   └── Customer_business_split/
│   ├── Contract_type_vs_Churn/
│   └── Customer_business_split/
|
|
├── Data_Preprocessing/
│   ├── Handling_missing_values/
│   └── Encoding_categorical_variables/
│   ├── Label_Encoding/One-Hot_Encoding/
│   └── Feature_scaling/
│   ├── StandardScaler/MinMaxScaler/
│   └── Train-Test_Split/
│   ├── (80%-train,20%-test)/
│   └── Class-imbalance-handling/
|
|
├── Feature-Engineering/
|   ├── Tenure-grouping-(New-/-Medium-/-Loyal-customers)/
│   ├── Monthly-to-total-charges-ratio/
│   └── Binary_flags_for_high-risk_customers/
│   ├── Feature selection/
│   └── Correlation_analysis/
│   ├── Importance_from_tree-based_models/
|
|
├── Model-Building/
│   ├── Baseline-Model/
│   └── Logistic-Regression/
│   ├── Machine_Learning_Models/
│   └── Decision_Tree/
│   ├── Random_Forest/
│   └── XGBoost/Gradient_Boosting/
│   ├── Hyperparameter_tuning/
│   └── GridSearchCV/RandomizedSearchCV/
|
|
├── Model_Evaluation/
│   ├── Evaluation_Metrics/
│   └── Accuracy/
│   ├── Precision/
│   └── Recall/
│   ├── F1_Score/
│   ├── Confusion_Matrix/
│   └── Business-focused-evaluation/
|
|
├── Tools/
│   ├── Programming:Python/
│   └── Advance_Machine_Learning/
|
├── Libraries/
│   ├── Programming:Python/
│   └── Advance_Machine_Learning/
│   ├── Pandas/
│   └── NumPy/
│   ├── Matplotlib/
│   └── Seaborn/
│   ├── Scikit_learn/
│   └── XGBoost/
│   ├── Jupyter-Notebook/
```








## **Insights**
#### Through comprehensive exploratory data analysis and modeling, several key insights were uncovered:

- Around **9.72%** of the customers change their providers.
- Net margin on power subscription and consumption over **12 months** is a top driver for churn.
- customers who first subscribed to different electricity campaigns, the proportion of churning customers ranges from **6.0% to 12.6%.**
- Nearly **10%** **(9.7%)** of the customers have churned and **90%** of the customers have not churned.
- Forecasted bill of meter rental for the next 2 months also is an influential driver.
- Most cutomers started their contracts from **2009 to 2013.** Among these cutomers, it seems newer customers are more likely to switch to other providers.
- Most cutomers stayed with the current providers for **3 to 6 years.** Among these customers, it seems newer customers are more likely to switch to other providers.
- Only **18.15%** of the clients were also gas clients.
- Electricity clients are more likely to churn than electricity and gas clients.
- the cutomers whose off-peak enery prices increased, around **9.72%** of customers changed their providers.



## **Recommendations**
Time seems to be an influential factor, especially the number of months they have been active, their tenure and the number of months since they updated their contract.Based on the results above, it seems offering a discount to the predicted churning customers can increase the expected profit from these customers.




