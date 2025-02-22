# Railway-Journey-Refund-Prediction-System

- Tech Stack: Python (Pandas, Scikit-learn, Matplotlib, Seaborn), Machine Learning (Logistic Regression, Random Forest, Gradient Boosting)

- Data Preprocessing & Feature Engineering: Processed 300K+ railway journey records, handled missing values, corrected anomalies, and engineered features like "delay minutes" to enhance data quality and model interpretability.
- Exploratory Data Analysis (EDA): Leveraged box plots, heatmaps, and distribution graphs to uncover key insights, such as 75% of ticket prices being under £35, peak-hour delay patterns, and higher refund rates among debit card users.
- Model Development & Optimization: Trained and evaluated five classification models for refund prediction. The final Gradient Boosting model achieved 92% precision, while the Random Forest model reached 55% recall with an F1-score of 0.66, outperforming baseline models by 30%.
- Business Impact: Deployed a logistic regression model to predict refund probabilities on new data, enabling railway companies to refine refund strategies and mitigate financial losses from misjudgments.
- Key Outcomes: Built an end-to-end ML pipeline using Scikit-learn's Pipeline and GridSearchCV, integrating data preprocessing, feature selection, model training, and hyperparameter tuning. Managed model lifecycle with MLflow, ensuring efficient tracking, reproducibility, and deployment.
