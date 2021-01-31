# COVID-19 Intubation Project
Classification model to predict whether someone needs a ventilator using patient-level clinical and epidemiological data from Mexico

**Description**\


**Features and Target Variables**\
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
* *City/state of residence?

Continuous features include:
* Age
* *Median income of city of residence?
* *Average temperature for two weeks prior to sympton start date?
* *Number of days between symptom start date and test date?


**Data Used**\
A dataset containing the results of real-time PCR testing for COVID-19 in Mexico as reported by the General Directorate of Epidemiology. The raw data was converted from PDF to tabular prior to analysis. *Income data (census)? Temperature or weather data?

**Tools used**
* Pandas
* NumPy
* scikit-learn
* Seaborn
* Matplotlib
* statsmodels

**Possible Impacts**\
