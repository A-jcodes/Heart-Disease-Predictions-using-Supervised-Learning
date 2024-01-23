# Heart-Disease-Predictions-using-Supervised-Learning
![graph](https://github.com/A-jcodes/Heart-Disease-Predictions-using-Supervised-Learning/assets/96001998/3574efc8-0401-40c7-9ca9-0b46bbc62daf)



Peterside Hospital, a leading healthcare facility, faced challenges in efficiently managing patient data and predicting potential health issues. Peterside Hospital is known for its state-of-the-art facilities, modern equipment, and highly skilled medical professionals. The  hospital  has  a  team  of  over  300  medical  personnel, including doctors, nurses, and other healthcare professionals, who are trained locally and internationally.

The  hospital  has  several  specialized  clinics,  including  a diabetes clinic, a fertility clinic, a heart clinic, and a cancer clinic.  It  also  offers  services  such  as  health  check-ups, laboratory tests, and imaging services. The hospital sought to leverage data science to analyze its patient database, identify trends, and make predictions to enhance patient care and resource allocation.

**Dataset**
The  heart  CSV  dataset  contains  303  records  and  14 columns, including the target variable. The features include: 

age-age in years

sex-(1 = male, 0. female)

cp-chest pain type (1: typical angina 2: atypical angina, 3: non-anginal pain, 4: asymptomatic),

trestbps - resting blood pressure (in mm Hg on admission to the hospital),

chol - serum choestoral in mg/dl,

fbs- (fasting blood sugar > 120 mg/dl) (1 =true; 0 =false),

restecg - resting electrocardiographic results,

thalach-maximum heart rate achieved,

exang - exercise induced angina (1 = yes; 0= no),

oldpeak - ST depression Induced by exercise realve to rest,

slope-the sope of the peak exercise ST segment,

ca-number of major vessels (0-3) colored by flourosopy,

thal -3 = normal; 6 = fixed defect; 7 = reversable defect,

target-have disease of not (1=yes, 0=no).

**Task:**
To build a machine-learning model that can predict the likelihood of a person having a heart disease based on the given features.

**Action:**

1. **Data Collection and Exploration:**
   - Acquired and preprocessed the patient database, addressing missing values, outliers, and ensuring data quality.
   - Explored the dataset to understand the distribution of variables and potential correlations.

2. **Feature Engineering:**
   - Identified relevant features for analysis, including demographic information, medical history, and diagnostic data.
   - Engineered new features to enhance the predictive power of the models.

3. **Model Selection:**
   - Explored a variety of supervised machine learning models suitable for healthcare predictions, such as logistic regression, decision trees, and random forests.
   - Selected models based on their performance in preliminary testing and their interpretability.

4. **Training and Evaluation:**
   - Split the dataset into training and testing sets to train the models and assess their performance.
   - Utilized appropriate evaluation metrics, considering the hospital's specific needs, such as precision, recall, and F1 score.
   - Fine-tuned hyperparameters to optimize model performance.

5. **Interpretability and Insights:**
   - Ensured models were interpretable, providing explanations for predictions to enhance trust in the results.
   - Extracted meaningful insights from the models, identifying key factors influencing predictions and potential areas for intervention.

**Result:**
The project successfully provided Peterside Hospital with:
- Predictive models for identifying potential health risks in patients.
- Insights into key factors affecting patient outcomes.
- Recommendations for targeted interventions to improve patient care.

**Key Achievements:**
- Achieved a predictive model with [92.59%] accuracy, demonstrating the feasibility of using machine learning for healthcare predictions.
- Identified specific patient cohorts at higher risk, enabling proactive healthcare interventions.
- Enhanced data-driven decision-making processes within the hospital.

**Recommendations for Future Work:**
- Continuously update and retrain the models as new data becomes available.
- Explore additional features and data sources to improve prediction accuracy.
- Collaborate with healthcare professionals to integrate the models into the hospital's daily operations.

**Conclusion:**
The data science project at Peterside Hospital showcased the potential of leveraging Python, supervised machine learning models, and advanced evaluation techniques to gain valuable insights from patient data. The developed models contribute to informed decision-making, ultimately enhancing patient care and resource allocation at Peterside Hospital.
