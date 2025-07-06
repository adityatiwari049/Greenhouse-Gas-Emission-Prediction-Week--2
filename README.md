Greenhouse-Gas-Emission-Prediction
This project focuses on applying Artificial Intelligence to real-world environmental problems.

✅  Week 1
In Week 1, we explored and analyzed greenhouse gas emission data from the U.S. supply chain using data provided in Excel format. Our objective was to understand the structure, trends, and insights from emissions data over multiple years.

✅  Week 2
In Week 2, we extended our analysis by cleaning and preprocessing the data. This included handling missing values, dropping irrelevant columns, and performing exploratory data analysis (EDA) to identify key emission contributors. We also visualized the distribution of emissions and examined the top emitting industries to prepare the dataset for machine learning models.


✅ Week 3: Model Building and Evaluation
In Week 3, we focused on applying machine learning techniques to predict greenhouse gas emissions based on our cleaned and processed dataset.

🔧 Key Steps:
Feature Scaling: Used StandardScaler to normalize features for better model performance.

Model Implementation:
Implemented Linear Regression and Random Forest Regressor models to build baseline and ensemble models.
Evaluated the models using RMSE (Root Mean Squared Error) and R² Score to assess prediction accuracy.

Hyperparameter Tuning:
Performed GridSearchCV to fine-tune the Random Forest model.
Identified the best combination of parameters to improve model accuracy.

Model Comparison:
Compared the performance of default and tuned models using a summary DataFrame.
Model Saving:
Saved the trained model and scaler using joblib for future predictions or deployment.

📊 Outcomes:
Tuned Random Forest model outperformed baseline models.
Built a scalable and reusable pipeline for future environmental prediction tasks.
