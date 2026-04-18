🫁 Lung Cancer Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting the likelihood of lung cancer using supervised machine learning algorithms based on patient lifestyle and health-related features. The model classifies individuals into YES (Lung Cancer) and NO (No Lung Cancer).

🎯 Objective

To build and compare multiple machine learning models to identify the most effective algorithm for lung cancer prediction.

⚙️ Technologies Used

Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

🤖 Machine Learning Models

Logistic Regression, Random Forest Classifier, Support Vector Machine (SVM)

📊 Model Performance

Logistic Regression - Accuracy: 96.77%, Precision: 0.98, Recall: 0.98, F1-Score: 0.98
Random Forest - Accuracy: 96.77%, Precision: 0.98, Recall: 0.98, F1-Score: 0.98
SVM - Accuracy: 95.16%, Precision: 0.98, Recall: 0.97, F1-Score: 0.97

📌 Key Insights

Logistic Regression and Random Forest achieved the highest accuracy (96.77%). SVM performed slightly lower (95.16%). The dataset is imbalanced with very few “No Cancer” cases.

📈 Evaluation Metrics Used

Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC Curve

📊 Visualizations

Accuracy Comparison Bar Chart, Confusion Matrix, Feature Importance (Random Forest), ROC Curve

🧪 Example Prediction

Input: Age = 60, Smoking = YES, Fatigue = YES → Output: Lung Cancer Prediction = YES

🧠 What I Learned

End-to-end Machine Learning pipeline, Model comparison and evaluation, Handling imbalanced datasets, Feature importance and interpretation

⚠️ Limitations

Dataset is small and imbalanced, Model performance on minority class is lower, Not suitable for real-world medical diagnosis

🚀 Future Improvements

Apply data balancing techniques (SMOTE), Hyperparameter tuning, Deploy as a web application

📌 Conclusion

Machine learning models can effectively predict lung cancer risk based on input features. Among the models tested, Random Forest and Logistic Regression performed best.

🙌 Acknowledgment

This project is developed as part of a learning exercise to gain practical knowledge in machine learning.
