# Data

## Description 
- The dataset contains information on individuals' health parameters, with columns representing different attributes. These include Age, Sex, Chest Pain Type (ATA, NAP, ASY, TA), Resting Blood Pressure (RestingBP), Cholesterol levels, Fasting Blood Sugar (FastingBS), Resting Electrocardiographic Results (RestingECG), Maximum Heart Rate (MaxHR), Exercise-Induced Angina (ExerciseAngina), ST depression induced by exercise relative to rest (Oldpeak), ST segment slope (ST_Slope), and the presence or absence of Heart Disease (HeartDisease).
- Each row corresponds to a unique individual, providing a snapshot of their health profile. The data appears to capture diverse information such as age, gender, cardiovascular symptoms, and various physiological measurements. The dataset is likely intended for analysis to identify patterns or factors associated with the presence of heart disease.

## Data dictionary
| Variable        | Definition                                          | Description                                         | Frequency     | Range                | Unit        | Type      |
|-----------------|-----------------------------------------------------|-----------------------------------------------------|---------------|----------------------|-------------|-----------|
| Age             | The age of the individual                           | The age of the person in years                      | Continuous    | 32 to 66 years        | Years       | Numerical |
| Sex             | The gender of the individual                        | Male (M) or Female (F)                             | Categorical   | M, F                 | Category    | Categorical |
| ChestPainType   | Type of chest pain experienced                      | ATA (Typical Angina), NAP (Atypical Angina), ASY (Non-Anginal Pain), TA (Typical Angina) | Categorical   | ATA, NAP, ASY, TA    | Category    | Categorical |
| RestingBP       | Resting blood pressure                               | Blood pressure measured at rest                     | Continuous    | 100 to 170 mm Hg     | mm Hg       | Numerical |
| Cholesterol     | Cholesterol levels                                   | Serum cholesterol in mg/dl                          | Continuous    | 100 to 529 mg/dl     | mg/dl       | Numerical |
| FastingBS       | Fasting blood sugar level                            | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) | Binary        | 0, 1                 | Category    | Binary    |
| RestingECG      | Resting electrocardiographic results                | Normal, ST-T wave abnormality (ST), Left ventricular hypertrophy (LVH) | Categorical   | Normal, ST, LVH      | Category    | Categorical |
| MaxHR           | Maximum heart rate achieved                         | Maximum heart rate during exercise                 | Continuous    | 82 to 184 BPM        | BPM         | Numerical |
| ExerciseAngina  | Exercise-induced angina                             | Presence (Y) or absence (N) of exercise-induced angina | Binary        | Y, N                | Category    | Binary    |
| Oldpeak         | ST depression induced by exercise relative to rest  | The degree of ST depression                         | Continuous    | 0 to 4               | Dimensionless | Numerical |
| ST_Slope        | ST segment slope during exercise                    | Up, Flat                                            | Categorical   | Up, Flat             | Category    | Categorical |
| HeartDisease    | Presence or absence of heart disease                 | Presence (1) or absence (0) of heart disease        | Binary        | 0, 1                 | Category    | Binary    |
## Sample Observation

| Age | Sex | ChestPainType | RestingBP | Cholesterol | FastingBS | RestingECG | MaxHR | ExerciseAngina | Oldpeak | ST_Slope | HeartDisease |
|-----|-----|---------------|-----------|-------------|-----------|------------|-------|-----------------|---------|----------|--------------|
| 40  | M   | ATA           | 140       | 289         | 0         | Normal     | 172   | N               | 0       | Up       | 0            |

## Flowchart
<img src="Flowchart.png" alt="Flowchart">

## Citation
- FEDESORIANO. 2021. “Heart Failure Prediction Dataset.” www.kaggle.com. 2021. https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction.


