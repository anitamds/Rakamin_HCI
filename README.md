📊 Credit Risk Prediction using Machine Learning
Case Study: Home Credit Indonesia

📌 Project Overview
- This project focuses on building an end-to-end machine learning pipeline to predict credit default risk using customer application and historical credit data.
- The objective is to support risk-aware lending decisions by combining robust data preprocessing, predictive modeling, and actionable business insights.
- The project simulates a real-world credit scoring scenario, emphasizing not only model performance but also business interpretability and deployment considerations.

🎯 Business Objectives
1. Predict the probability of customer loan default.
2. Minimize credit risk while maintaining approval efficiency.
3. Generate data-driven insights to support credit policy and portfolio strategy.

🔑Key characteristics:
- 307,511 records with 122 features
- Highly imbalanced target variable (~8% default rate)
- Extensive missing values and high-cardinality categorical features
- Data includes demographics, credit history, and payment behavior

🧹 Data Preprocessing
1. The preprocessing stage was designed to ensure data quality and modeling readiness, including:
2. Handling missing values using statistical and domain-aware imputation
3. Encoding categorical variables
4. Feature scaling and transformation
5. Feature selection to reduce noise and redundancy
6. rain–test split with class distribution awareness
7. Oversampling / undersampling strategies to mitigate class imbalance

🤖 Modeling Approach
Two classification models were developed and compared:
Logistic Regression (baseline, interpretable model) and Random Forest (ensemble-based model)
These models were selected to balance interpretability, performance, and practical deployment considerations in a financial context.

📈 Model Evaluation
Model performance was evaluated using metrics aligned with imbalanced classification problems:
Accuracy, Precision, Recall, F1-score, Confusion Matrix, and AUC-ROC

🔍 Key Results
Accuracy: ~91.9%
AUC-ROC: 0.735
Both models showed strong performance on the majority class.
Prediction performance on the minority (default) class remained limited, highlighting the risk of accuracy bias in imbalanced datasets.
⚠️ This finding emphasizes the importance of threshold tuning and cost-sensitive learning before real-world deployment.
💡 Business Insights & Recommendations

Key insights derived from exploratory analysis and model outputs include:
U-shaped default risk pattern across loan amounts, with medium-sized loans showing the highest default rate (~10.05%).
Revolving loans exhibited ~35% lower default rates compared to cash loans.
Income level alone does not directly correlate with default risk, indicating the need for multidimensional credit assessment.

📌 Business Recommendations:
Apply stricter screening for medium-sized loans.
Expand revolving loan products with tailored risk policies.
Implement differentiated credit strategies by loan type and customer segment.

⚠️ Limitations & Future Improvements
Severe class imbalance limited minority-class prediction performance.
Further improvements could include:
SMOTE or advanced resampling techniques
Cost-sensitive learning
Threshold optimization
Gradient boosting models (e.g., XGBoost, LightGBM)

🛠️ Tools & Technologies
Python
Pandas, NumPy
Scikit-learn
Matplotlib / Seaborn
Jupyter Notebook

🔗 Project Links
GitHub Repository: https://github.com/anitamds/Rakamin_HCI
LinkedIn: https://www.linkedin.com/in/anitasilalahi

👩‍💻 Author
Anita Margareth D Silalahi
Data Scientist / Data Analyst
Universitas Brawijaya
📧 anitasilalahi18@gmail.com
