# Early Identification of At-Risk Students: Dropout Prevention

This project utilizes data-driven techniques to identify students at risk of academic dropout in higher education. By analyzing early-stage student data, the model predicts potential academic failure, enabling timely interventions. The ultimate goal is to reduce dropout rates by providing insights and support strategies for at-risk students.

**Dataset:** [Classification with an Academic Success Dataset](https://www.kaggle.com/competitions/playground-series-s4e6)

**Citation:**  
Walter Reade, Ashley Chow. (2024). *Classification with an Academic Success Dataset*. Kaggle. https://kaggle.com/competitions/playground-series-s4e6

## Methodology

1. **Exploratory Data Analysis (EDA):**  
   We began by performing a high-level exploratory data analysis using visualization libraries such as:
   - `seaborn` (`sns`)
   - `plotly.express` (`px`)
   - `matplotlib.pyplot` (`plt`)

2. **Feature Engineering:**  
   Following the EDA, feature engineering was carried out to enhance the dataset. This process involved handling missing values, encoding categorical variables, and creating new features to improve model performance.

3. **Model Evaluation:**  
   We evaluated three different machine learning models:
   - XGBoost
   - CatBoost
   - LightGBM (LGBM)

4. **Feature Importance:**  
   Since the dataset contains some irrelevant features, we calculated feature importance for each model. We identified the least important features by analyzing the bottom 10 features common across all models and dropped them from the dataset.

5. **Ensemble Model:**  
   After retraining the dataset with the reduced feature set, we blended the model scores to create an ensemble prediction, improving overall accuracy.

## Conclusion

This project aims to help educational institutions proactively identify at-risk students and take necessary steps to prevent dropouts. By leveraging data analysis and machine learning, this approach offers a scalable solution for dropout prevention in higher education.
