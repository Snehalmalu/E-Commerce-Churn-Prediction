E-Commerce Churn Prediction
E-Commerce revolutionizes the shopping experience, bringing convenience to consumers and global reach to businesses. With just a click, customers access a vast array of products, making transactions secure and personalized. In this digital era, E-Commerce is not just a marketplace; it's a transformation, offering unparalleled flexibility and choice to both buyers and sellers. ecommerce3-2

INTRODUCTION
The rise of E-commerce is undeniable, witnessing a surge in businesses embracing the online marketplace. Success in this realm depends on a deep understanding of customer behavior, with customer churn being a pivotal metric. It signifies the pace at which patrons end their association with an online retailer. pngtree-business-concept-of-online-shopping-e-commerce-png-image_5345089

IMPORTANCE
E-commerce businesses secure a strategic advantage by foreseeing and addressing customer churn promptly. Proactively managing concerns ensures the retention of valuable customers. Financially, retaining existing customers proves more cost-effective than acquiring new ones, making predictive models crucial for resource allocation and maintaining a healthy bottom line. qivos_commerce_ecommerce_implementation_2-1076x675

AIMS AND OBJECTIVES
Project Objective: This initiative seeks to build a predictive model, utilizing machine learning algorithms, to analyze customer attrition in the e-commerce sector.

Key Focus:
Feature Exploration: Identify crucial features impacting customer attrition in the e-commerce domain.
Algorithm Optimization: Evaluate the effectiveness of Logistic Regression, Decision Trees, and Random Forest algorithms. Emphasis on precision in predicting customer churn using comprehensive performance metrics.
Strategic Insights: Derive customer retention strategies from analytical findings for informed decision-making.
1658305855779

ABOUT THE DATSETS
The "E-commerce Customer Behavior and Purchase Dataset" is an artificial dataset generated with the Faker Python library, simulating a comprehensive e-commerce environment. Ideal for data analysis and predictive modeling in the e-commerce domain, it facilitates tasks such as forecasting customer churn, market basket analyses, recommendation systems, and trend scrutiny.

What-is-Ecommerce

MODEL USED
I am planning to apply three algorithms: Logistic Regression,Random Forest, & Xgboost, as they are effective in handling imbalanced datasets.And working best on larger datasets.

LOGISTIC REGRESSION RANDOM FOREST XGBOOST

WhatsApp Image 2024-02-15 at 18 06 44_e3ea0003

ROC AUC SCORE METRICS AFTER HYPERPARAMETER TUNING
The ROC-AUC score is like a report card for a model in a binary test (yes or no). It checks how well the model can separate positive from negative things. The ROC curve is a graph that shows how good the model is at making this separation. The higher the ROC-AUC score, the better the model is doing overall Following hyperparameter tuning, the ROC scores indicate advancements across models: Logistic Regression (0.501610), Random Forest (0.501714), and XGBoost (0.503356). Opting for XGBoost post-tuning seems favorable, boasting the highest ROC score and signaling improved model performance compared to Logistic Regression and Random Forest in this refined state.

CONCLUSION
Data Overview:
250,000 rows, 13 features. No duplicates, mainly numeric columns. Target Variable (Churn): 20.05% churn, 79.95% retention. Product Category, Payment Method, Quantity, and Gender show balanced distributions. Returns and Purchase Trends:

Balanced churn/retention for returns. Seasonal purchase variations, with peaks in January and August. XGBoost, post-tuning, excels with an improved ROC score. Preprocessing:

Converted "Purchase Date" to datetime, extracted year/month. Label encoding for gender, one-hot encoding for categories/methods. Handled nulls, dropped irrelevant features, and used SMOTE for balance. Applied standard scaling on specific numeric features. In summary, the dataset is well-prepared, imbalances addressed, and XGBoost stands out post-hyperparameter tuning. Ready for further analysis or deployment. Presented by: Snehal Malusare.

conclusion-5859031_960_720

DASHBOARD
Screenshot 2024-02-28 163053

About
No description, website, or topics provided.
Resources
