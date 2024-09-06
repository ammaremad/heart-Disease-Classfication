**Project Overview**
The objective of this project was to analyze a dataset related to heart disease and develop a predictive model to identify individuals at risk for heart disease. The dataset consisted of 1025 entries and 14 features, including demographic information, clinical measurements, and diagnostic indicators. The project involved data exploration, visualization, feature selection, and the application of a logistic regression model to predict the presence of heart disease.

**Data Understanding and Exploration**
- Data Structure: The dataset contained 14 columns, including both numerical and categorical variables. The target variable was binary, indicating the presence (1) or absence (0) of heart disease.
- Data Preview: Initial exploration revealed a diverse range of ages and clinical indicators, with no missing values present in the dataset.
- Statistical Overview: Descriptive statistics provided insights into the distribution of features, such as age, cholesterol levels, and maximum heart rate. The average age of individuals in the dataset was approximately 54 years, with a slight male predominance.
  
**Data Visualization**
- 1.Count Plots: Visualizations highlighted the distribution of categorical variables, revealing that:
- Males were more prevalent in the dataset compared to females.
- Certain types of chest pain were more common, indicating varying severity levels among individuals.
- A significant number of individuals had elevated fasting blood sugar levels, suggesting a potential link to diabetes.
- 2.Box Plots and Histograms: These plots illustrated the spread and distribution of numerical features, such as resting blood pressure and cholesterol levels, helping to identify potential outliers and trends in the data.
  
**Feature Selection and Engineering**
- 1.Correlation Analysis: A correlation matrix was generated to assess the relationships between features and the target variable. Key insights included:
- Chest pain type and maximum heart rate showed positive correlations with the target variable.
- Old peak and exercise-induced angina had negative correlations, indicating their potential as risk factors for heart disease.
- 2.Feature Selection: Using the SelectKBest method, features with low correlation to the target were dropped, refining the dataset to enhance model performance.
  
**Model Development**
- 1.Logistic Regression: The dataset was split into training and testing sets, and a logistic regression model was trained on the training data. The model achieved a high accuracy score of 93% on the test set.
- 2.Model Evaluation: The performance was assessed using a confusion matrix, classification report, and ROC curve analysis:
- The confusion matrix indicated a strong ability to correctly classify both positive and negative cases.
- The classification report provided precision, recall, and F1 scores, highlighting the model's effectiveness in identifying heart disease.
- The ROC curve and AUC score (0.93) confirmed the model's excellent discriminative ability.
  
**Insights and Conclusions**
- The analysis revealed significant insights into the risk factors associated with heart disease, emphasizing the importance of features such as chest pain type, maximum heart rate, and old peak in predicting heart disease.
- The logistic regression model demonstrated strong predictive capabilities, making it a valuable tool for identifying individuals at risk for heart disease.
- The project underscores the potential for data-driven approaches in healthcare, enabling targeted interventions and improved patient outcomes.
  
In conclusion, this project successfully combined data exploration, visualization, and machine learning techniques to develop a robust predictive model for heart disease. The insights gained from the analysis can inform healthcare professionals in understanding risk factors and tailoring prevention strategies, ultimately contributing to better health management and patient care.
