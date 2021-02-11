# COVID-19 Intubation Classification Project
Classification model to predict whether someone needs a ventilator using patient-level clinical and epidemiological data from Mexico

**Description**\
Given all of the patient-level data, I decided to focus on classifying Intubation because understanding the underlying conditions of patients who were intubated and survived COVID-19 can help healthcare workers identify who is most likely to need and benefit from a ventilator.

**Features and Target**\
The target variable is intubation status, a binary variable for whether someone will need a ventilator or not. Categorical features include:
* Gender
* Age
* Pneumonia
* Pregnant
* Indigenous
* Diabetic
* Symptoms of lung disease
* Asthma
* Immunosuppressed
* Hypertension
* Comorbidity
* Cardiovascular Disease
* Obese
* Chronic Renal Insufficiency

Continuous features include:
* Age

Future work may include more continuous features such as:
* *Median income of city of residence*
* *Average temperature for two weeks prior to symptom start date*
* *Number of days between symptom start date and test date*


**Data Used**\
A dataset containing the results of real-time PCR testing for COVID-19 in Mexico as reported by the General Directorate of Epidemiology. The raw data was converted from PDF to tabular prior to analysis.

**Tools used**
* Pandas
* NumPy
* scikit-learn
* Seaborn
* Matplotlib
* statsmodels

**Possible Impacts**\
Understanding a patient’s risk for needing a ventilator will improve the level of patient care across the country and allow for a more efficient allocation of limited resources. It’s especially important for healthcare workers in countries like Mexico to understand a patient’s risk given the lack of ventilators nationwide and the constant battle over limited resources between hospitals in less prosperous regions. 
