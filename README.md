 AI-Powered Student Success Assistant 
This project showcases a complete data analysis and machine learning pipeline focused on predicting student success levels. Combining Excel for exploratory data analysis and dashboarding with Python for predictive modeling, this solution demonstrates how AI can be integrated into education to drive actionable insights.

 Project Overview
Tool 1: Excel
Used for data cleaning, pivot table analysis, KPI creation, slicers, and interactive dashboards to visualize trends by student level.

Tool 2: Python (Scikit-learn)
Implemented a machine learning model (Random Forest Classifier) to predict student success outcomes.
 Machine Learning Result
model = RandomForestClassifier(random_state=42)
model.fit(X_train, y_train)

y_pred = model.predict(X_test)
print("Accuracy:", accuracy_score(y_test, y_pred))
print(classification_report(y_test, y_pred))
📈 Model Performance:
Accuracy: 72.45%

Class	Precision	Recall	F1-Score	Support
0 (Not Successful)	0.58	0.39	0.46	615
1 (Successful)	0.76	0.87	0.81	1385

Weighted Avg F1-Score: 0.71
Macro Avg F1-Score: 0.64

✅ The model performs well in identifying successful students and offers a strong foundation for decision-making.

 Insights from Excel Dashboard
Success rates vary significantly by education level (Undergraduate,High schoo and Graduate).

Interactive slicers allow filtering by Success flag , level, and session status.

KPI metrics highlight engagement and performance gaps.

🙌 Acknowledgment
Built as part of the 3MTT Knowledge Showcase to demonstrate the power of combining data analysis and AI for education.


