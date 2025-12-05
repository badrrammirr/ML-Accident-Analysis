## 1. Project Overview
This project focuses on building a robust, production-ready machine learning pipeline using Python and Scikit-learn to analyze and predict the occurrence of road accidents based on geographical and contributing factors.

The primary goal was to create a modular and efficient workflow that handles data preprocessing and modeling steps systematically, culminating in a clear, actionable prediction model.

## 2. Key Features
The analysis demonstrates competency in several core data science areas:

* **End-to-End Scikit-learn Pipeline:** Utilized `Pipeline` and `ColumnTransformer` to consolidate all preprocessing and modeling steps, ensuring data integrity and ease of deployment.
* **Comprehensive Preprocessing:** Handled missing values (imputation), converted ambiguous categorical data, and engineered date-based features from the `Timestamp` column.
* **Feature Scaling & Encoding:** Employed `StandardScaler` for numerical features and `OneHotEncoder` for categorical features within the transformer.
* **Classification Modeling:** Trained a **Random Forest Classifier** to accurately predict the binary outcome (`Accident_Occurred`).
* **Geospatial Analysis:** Visualized accident locations to identify and report on **geographical high-risk hotspots**.

## 3. Results and Key Insights
The final model achieved a high prediction accuracy (0.9854545454545455) on the test set.

* The geographical visualization effectively isolates clusters of high accident frequency, providing clear guidance for potential infrastructure improvements or targeted safety campaigns.
* The use of a pipeline guarantees that the model receives data in the exact same format it was trained on, making it ready for deployment and automated scoring.

## 4. Technologies Used
* **Language:** Python
* **Core Libraries:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (Pipeline, ColumnTransformer, RandomForestClassifier)
* **Visualization:** Matplotlib
