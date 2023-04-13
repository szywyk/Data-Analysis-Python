## Medical data visualizer
Link to the code at Google Colab: <https://colab.research.google.com/drive/1FjgT3G4Ia_Kk8SVjEB96P7hnjDXWtu1j>

This dataset contains medical data, which was collected during medical examinations. The rows in the dataset represent patients and the columns represent information like body measurements, results from various blood tests, and lifestyle choices.

The dataset was used to explore the relationship between cardiac disease, body measurements, blood markers, and lifestyle choices.

Table below explains the dataset (binary means - 0: NO, 1: YES):
|                  **Feature**                  |  **Variable Type**  |  **Variable** |                  **Value Type**                  |
|:---------------------------------------------:|:-------------------:|:-------------:|:------------------------------------------------:|
|                      Age                      |  Objective Feature  |     _age_     |                    int (days)                    |
|                     Height                    |  Objective Feature  |    _height_   |                     int (cm)                     |
|                     Weight                    |  Objective Feature  |    _weight_   |                    float (kg)                    |
|                     Gender                    |  Objective Feature  |    _gender_   |                 categorical code                 |
|            Systolic blood pressure            | Examination Feature |    _ap_hi_    |                        int                       |
|            Diastolic blood pressure           | Examination Feature |    _ap_lo_    |                        int                       |
|                  Cholesterol                  | Examination Feature | _cholesterol_ | 1: normal, 2: above normal, 3: well above normal |
|                    Glucose                    | Examination Feature |     _gluc_    | 1: normal, 2: above normal, 3: well above normal |
|                    Smoking                    |  Subjective Feature |    _smoke_    |                      binary                      |
|                 Alcohol intake                |  Subjective Feature |     _alco_    |                      binary                      |
|               Physical activity               |  Subjective Feature |    _active_   |                      binary                      |
| Presence or absence of cardiovascular disease |   Target Variable   |    _cardio_   |                      binary                      |
