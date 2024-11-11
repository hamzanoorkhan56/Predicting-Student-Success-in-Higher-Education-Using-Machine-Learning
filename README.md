# Predicting-Student-Success-in-Higher-Education-Using-Machine-Learning

This project explores the prediction of student success in higher education beyond traditional grading metrics. While grades are often the sole focus in determining educational advancement in the UK, this research emphasizes a broader range of factors influencing student success. This project uses various machine learning models and hyperparameter tuning techniques to assess whether it's possible to predict student outcomes based on a variety of socio-economic, personal, and academic variables. Ultimately, this work aims to highlight that student success is multifaceted and that grades alone may not accurately capture a student's potential or educational journey.

## Project Goals
1. **Understand the Broader Factors of Success**: Recognize the impact of economic background, household circumstances, special educational needs, and other variables on student performance.
2. **Develop Predictive Models**: Use machine learning to predict student outcomes and examine the relevance of non-grade factors in forecasting success.
3. **Evaluate Model Accuracy**: Fine-tune models to determine which factors most strongly correlate with successful outcomes (e.g., graduation vs. dropout).

## Dataset and Methodology
The data used in this project includes variables such as:
- **Demographics**: Age, gender, socio-economic background, parental education, and occupation.
- **Academic Indicators**: Previous qualifications, semester grades, and course information.
- **Additional Factors**: Special educational needs, household characteristics, and socio-economic indicators.

Using this data, a range of machine learning algorithms are implemented and fine-tuned to assess the predictive value of different variables on student success.

## Project Structure

### Section 1: Data Preparation
- **Categorical Conversion**: Convert numerical values into categorical labels to facilitate data exploration and make results interpretable.
- **Exploratory Analysis**: Examine data depth, distributions, and unique values in each column to understand variable characteristics.

### Section 2: Data Exploration
- **Outcome Ratios**: Analyze ratios of students who graduate, remain enrolled, or drop out.
- **Variable Review**: Catalog variables available in the dataset and hypothesize potential relationships and correlations with student success.

### Section 3: Learner Profile Analysis
- **Dropout Predictions**:
  - **Special Needs**: Assess if students with special educational needs or displacement are more prone to drop out.
  - **Age Group Trends**: Identify age groups with higher dropout rates and investigate potential reasons.
  - **Course-Specific Trends**: Examine dropout trends across different courses to find patterns.
  - **Parental Influence**: Explore if parental education and occupation correlate with student graduation rates.
  
  Machine learning models used in this section:
  - **Logistic Regression**: To predict dropout, enrollment, or graduation, analyzing the impact of variables and identifying key predictors.
  - **XGBoost**: Employing hyperparameter tuning for enhanced prediction accuracy.
  - **Random Forest Classifier**: Applied specifically to assess dropout risk per course, with feature importance analysis.

### Section 4: Academic Performance Analysis
- **Semester Grades Prediction**:
  - Predict student performance in subsequent semesters using historical grade data and previous qualifications.
  - Assess potential difficulties for students in future semesters to provide targeted support.

### Section 5: Final Grade Prediction
- Use previous qualifications and semester grades to predict final course grades.
- Fine-tune models to assess if additional variables enhance prediction accuracy and overall model performance.

## Machine Learning Techniques
The project employs multiple machine learning models to address various questions around student success:
- **Logistic Regression**
- **XGBoost**
- **Random Forest Classifier**

Each model is refined through hyperparameter tuning, with feature selection applied to focus on the most significant variables.

## Conclusion
This project aims to demonstrate that student success is influenced by a wide array of factors beyond grades, and that incorporating these factors can enhance the predictive power of models in educational settings. The insights generated may encourage more holistic approaches in evaluating student success in higher education.
