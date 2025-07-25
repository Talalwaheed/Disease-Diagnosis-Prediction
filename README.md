
**Objective:** To develop a machine learning model for early disease diagnosis, specifically focusing on diabetes, to aid in proactive medical intervention and improved patient outcomes.

**Dataset:** The project utilized the Pima Indians Diabetes Dataset, which includes medical parameters like pregnancies, glucose levels, blood pressure, BMI, and age, along with an outcome variable indicating diabetes presence.

**Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (including train_test_split, StandardScaler, SelectKBest, f_classif, classification_report, roc_auc_score, roc_curve), GradientBoostingClassifier, SVC, and MLPClassifier.

**Project Activities & Methodology:** I began with exploratory data analysis (EDA) to understand data distributions and correlations. Data preprocessing involved handling missing values (zeros) by replacing them with the median, followed by feature selection using SelectKBest and data scaling with StandardScaler. Several machine learning models (Gradient Boosting, Support Vector Machine, Neural Network) were then trained and evaluated using metrics like classification reports and AUC-ROC curves to assess their predictive performance.

**Benefits:** This project provides a robust predictive tool for healthcare professionals, enabling earlier and more accurate diagnosis of diseases like diabetes. This leads to timely treatment, better management of conditions, and ultimately, enhanced patient health and reduced healthcare burden.
