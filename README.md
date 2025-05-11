# Financial_Fraud_Detection_Using_XAI
Financial fraud is a complex challenge due to the increase in transaction and data volume in the modern digital economy. Fraud can occur from simple credit card fraud to complex and systemic money laundering and can cause significant economic damage and distrust in financial institutions. Fraud detection using models respectively based on machine learning and deep learning are important but are often deployed as "black-box" models, leaving stakeholders with no way of knowing how the model reached the anomaly flag.
To mitigate the issue of a "black-box" in traditional machine learning and deep learning models, "explainable artificial intelligence" (XAI) has now can take the trade-off into account in a productive way. As previously noted, XAI is used to build interpretability into predictive models, therefore elevating the use of financial fraud detection. 
Stakeholders receive some sense of the factors contributed to a fraud flag, and therefore their stake in statistical method will help build trust. The value of "explainable" models is critical from a business perspective as models have regulatory and compliance factors to consider within a complex regulatory environment. Further, the explicit understanding of possibilities to predict leads to an opportunity for data scientists to investigate and identify possible bias or errors in the model.

Although financial services have seen substantial progress, organizations are still struggling to detect increasingly complex fraudulent activity. Existing systems are often not transparent enough, which hampers their ability to be implemented in real world settings. The primary objective of this project is to build an explainable AI-based financial fraud detection framework that meets the dual objectives of high prediction accuracy and clear, interpretable insight into its process of decision-making.

This project utilized a dual-process approach with the use of advanced machine learning techniques and explainability techniques. Advanced, robust classification algorithms were employed to sort through high-dimensional financial data and determine outliers. At the same time, post-hoc explanation methodologies - such as feature importance ranking, SHAP - SHapley Additive exPlanations and LIME - Local Interpretable Model-agnostic Explanations - were used to yield transparency of the model's decisions, while also providing actionable recommendations.

I utilized the Kaggle Credit Card Fraud Detection Dataset to develop and evaluate the proposed explainability approach to detecting fraud in finances, which is considered a standard benchmark in financial anomaly detection research.
This transaction dataset we utilized consists of anonymized transactions of US consumers over the course of 1 year (2019 to 2020). The dataset is challenging for realistic settings as there is an extreme class imbalance with only 0.52% of total samples classed as fraudulent.

#Dataset	Description
Total Samples:	3,39,607 
Legitimate Transactions:	3,37,825 (99.47%)
Fraudulent Transactions:	1782 (0.52%)
Features:	15
Label	Class: (0 = Legitimate, 1 = Fraud)
Feature Type:	Numeric (PCA transformed except Time and Amount)
Time Period:	365 days
Imbalance Ratio:	~1:190



