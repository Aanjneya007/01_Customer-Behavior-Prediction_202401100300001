# 01_Customer-Behavior-Prediction_202401100300001
Customer Behavior Prediction
This project aims to classify customers as either bargain hunters or premium buyers using machine learning techniques based on their purchase history.

Problem Statement
Businesses need to understand customer buying patterns to offer better services. By analyzing features like:

Total amount spent

Average purchase value

Visits per month

...we can classify customers into two segments:

Bargain Hunter

Premium Buyer

This helps businesses make data-driven decisions for targeted marketing and product recommendations.

Dataset
The dataset is stored in a file called:

bash
Copy
Edit
/content/customer_behavior.csv
Columns:

Column Name	Description
total_spent	Total money spent by the customer
avg_purchase_value	Average value per purchase
visits_per_month	Average store/site visits per month
buyer_type	Target label (bargain_hunter or premium_buyer)
🔧 Methodology
Data Loading using Pandas

Preprocessing:

Check for missing values

Encode buyer_type into numerical values (0 and 1)

Splitting the dataset into training and testing sets

Model Training using RandomForestClassifier

Model Evaluation using:

Confusion Matrix

Heatmap

Accuracy, Precision, Recall

Visualization of results

 Code
The model is built using the following key tools:

Python

pandas, numpy

scikit-learn for machine learning

matplotlib and seaborn for visualization

Full code is available in customer_behavior_model.ipynb

Output / Results
The model gives the following performance metrics:


Accuracy:  0.60
Precision: 0.50
Recall:    0.12

Learning Outcomes
Learned how to preprocess real-world data.

Understood classification using Random Forests.

Evaluated model performance using confusion matrix and metrics.

Created visualizations to interpret results better.

