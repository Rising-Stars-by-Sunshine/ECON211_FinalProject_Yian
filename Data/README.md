## Description 
- The heart dataset provides comprehensive information on patients' cardiovascular health, encompassing diverse attributes such as age, gender, chest pain type, blood pressure, cholesterol levels, and various electrocardiographic parameters. With a focus on exercise-induced conditions, the dataset includes variables like maximum heart rate, presence of angina, and ST segment characteristics during exercise. The dataset is designed to facilitate the exploration of factors contributing to heart disease, offering a valuable resource for researchers and healthcare professionals. The inclusion of categorical and numerical variables allows for a nuanced analysis, aiding in the identification of patterns and risk factors associated with cardiovascular health. This dataset is instrumental for developing predictive models and gaining insights into the intricate relationships between patient characteristics and the presence or absence of heart disease.

## Data Dictionary

| Variable          | Definition                                            | Description                                          | Frequency    | Range              | Unit       | Type      |
|-------------------|-------------------------------------------------------|------------------------------------------------------|--------------|--------------------|------------|-----------|
| Age               | Age of the patient [years]                            | Patient's age                                       | Continuous   | 29-77              | years      | Numerical |
| Sex               | Sex of the patient                                    | Gender of the patient                               | Categorical  | M, F               | -          | String   |
| ChestPainType     | Chest pain type                                      | Type of chest pain                                  | Categorical  | TA, ATA, NAP, ASY | -          | String   |
| RestingBP         | Resting blood pressure [mm Hg]                        | Resting blood pressure                               | Continuous   | 94-200             | mm Hg      | Numerical |
| Cholesterol       | Serum cholesterol [mm/dl]                             | Cholesterol levels in the blood                      | Continuous   | 126-564            | mm/dl      | Numerical |
| FastingBS         | Fasting blood sugar                                  | Fasting blood sugar level                           | Categorical  | 0, 1               | -          | String   |
| RestingECG        | Resting electrocardiogram results                    | Results of resting ECG                              | Categorical  | Normal, ST, LVH   | -          | String   |
| MaxHR             | Maximum heart rate achieved [Numeric value]           | Maximum heart rate during exercise                  | Continuous   | 71-202             | -          | Numerical |
| ExerciseAngina    | Exercise-induced angina                              | Presence of exercise-induced angina                 | Categorical  | Y, N               | -          | String   |
| Oldpeak           | Oldpeak = ST [Numeric value measured in depression]   | ST depression induced by exercise relative to rest | Continuous   | 0-6.2              | -          | Numerical |
| ST_Slope          | The slope of the peak exercise ST segment             | Slope of ST segment during peak exercise            | Categorical  | Up, Flat, Down     | -          | String   |
| HeartDisease      | Output class                                         | Presence or absence of heart disease                | Categorical  | 0, 1               | -          | String   |

## Sample Observations

| Age | Sex | ChestPainType | RestingBP | Cholesterol | FastingBS | RestingECG | MaxHR | ExerciseAngina | Oldpeak | ST_Slope | HeartDisease |
|-----|-----|---------------|-----------|-------------|-----------|------------|-------|-----------------|---------|----------|--------------|
| 40  | M   | ATA           | 140       | 289         | 0         | Normal     | 172   | N               | 0       | Up       | 0            |

