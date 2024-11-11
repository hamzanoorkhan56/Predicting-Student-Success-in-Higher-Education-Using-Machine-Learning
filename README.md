# Predicting Student Success in Higher Education Using Machine Learning

This project investigates predicting student success in higher education beyond the traditional focus on grades. In the UK, educational advancement is often measured solely by grades; however, this research highlights the importance of a wider range of factors influencing student success. By using various machine learning models and hyperparameter tuning techniques, this project assesses whether it is possible to predict student outcomes based on socio-economic, personal, and academic variables. Ultimately, this work emphasises that student success is multi-dimensional, and grades alone may not accurately reflect a student's potential or educational journey.

## Project Goals
1. **Recognise the Broader Factors of Success**: Understand the influence of economic background, family circumstances, special educational needs, and other variables on student performance.
2. **Develop Predictive Models**: Use machine learning to predict student outcomes and explore the importance of non-grade factors in forecasting success.
3. **Evaluate Model Accuracy**: Fine-tune models to identify which factors most strongly correlate with successful outcomes (e.g., graduation vs. dropout).

## Dataset and Methodology
The data used in this project includes variables such as:
- **Demographics**: Age, gender, socio-economic background, parental education, and occupation.
- **Academic Indicators**: Previous qualifications, semester grades, and course information.
- **Additional Factors**: Special educational needs, family characteristics, and socio-economic indicators.

Using this data, a variety of machine learning algorithms are implemented and fine-tuned to assess the predictive value of different variables on student success.

## Project Structure

### Section 1: Data Preparation
- **Categorical Conversion**: Convert numerical values into categorical labels to facilitate data exploration and improve result interpretability.
- **Exploratory Analysis**: Examine data depth, distributions, and unique values in each column to understand variable characteristics.

### Section 2: Data Exploration
- **Outcome Ratios**: Analyse the proportions of students who graduate, remain enrolled, or drop out.
- **Variable Review**: Catalogue variables available in the dataset and hypothesise potential relationships and correlations with student success.

### Section 3: Learner Profile Analysis
- **Dropout Predictions**:
  - **Special Needs**: Assess whether students with special educational needs or those facing displacement are more likely to drop out.
  - **Age Group Trends**: Identify age groups with higher dropout rates and investigate possible causes.
  - **Course-Specific Trends**: Examine dropout patterns across different courses to find any trends.
  - **Parental Influence**: Explore if parental education and occupation are correlated with student graduation rates.
  
  Machine learning models used in this section:
  - **Logistic Regression**: To predict dropout, enrolment, or graduation, examining variable impacts and identifying key predictors.
  - **XGBoost**: Applying hyperparameter tuning for improved prediction accuracy.
  - **Random Forest Classifier**: Applied specifically to assess dropout risk per course, with feature importance analysis.

### Section 4: Academic Performance Analysis
- **Semester Grades Prediction**:
  - Predict student performance in future semesters using historical grade data and previous qualifications.
  - Assess potential difficulties for students in upcoming semesters to enable targeted support.

### Section 5: Final Grade Prediction
- Use previous qualifications and semester grades to predict final course grades.
- Fine-tune models to determine if additional variables enhance prediction accuracy and overall model performance.

## Machine Learning Techniques
This project employs several machine learning models to address various questions around student success:
- **Logistic Regression**
- **XGBoost**
- **Random Forest Classifier**

Each model is refined through hyperparameter tuning, with feature selection used to focus on the most significant variables.

## Conclusion
This project aims to show that student success is influenced by a diverse range of factors beyond grades, and that incorporating these factors can increase the predictive power of models in educational settings. The insights generated may encourage a more holistic approach to evaluating student success in higher education.
