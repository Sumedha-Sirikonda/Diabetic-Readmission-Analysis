# Diabetic-Readmission-Analysis
Diabetic Readmission Analysis using Machine Learning

Data Description:
Our dataset sources from The UCI Machine Learning Repository (Dua & Graff, 2019). The dataset provides 10 years (1999-2008) of clinical care details of over 100000 patients at 130 US hospitals and integrated delivery networks. The dataset has over 50 features and around 17000 rows representing patient and their health related data such as admission source, number of medications, readmitted etc., details available in  hospital records. Information was extracted from the hospital database for encounters that satisfied the following criteria.
(1) It is an inpatient encounter (a hospital admission).
(2) It is a diabetic encounter, that is, one during which any kind of diabetes was entered to the system as a diagnosis.
(3) The length of stay was at least 1 day and at most 14 days.
(4) Laboratory tests were performed during the encounter.
(5) Medications were administered during the encounter.
The features available in the dataset are patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c test result, diagnosis, number of medication, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc.
The dataset has multi variant characteristics, a combination of numerical and categorical features. There are many missing values in the dataset that made using some of the categorical and numerical data columns quite difficult. For our analysis we are classifying the dataset to check if the patient is getting readmitted in 30 days or not.

