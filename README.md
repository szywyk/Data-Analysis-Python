# Data Analysis in Python with Pandas
This repository contains projects done for FreeCodeCamp.org's Data Analysis With Python Certification.

Below are descriptions of all projects.

---
## Demographic data analysis
Link to the code at Google Colab: <https://colab.research.google.com/drive/1LJs288qbzvseZi_bTDakvDOUjDLkL9Co>

This dataset contains demographic data which was extracted from the 1994 Census database.

This analysis answers following questions:
* How many people of each race are represented in this dataset?
* What is the average age of men?
* What is the percentage of people who have a Bachelor's degree?
* What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?
* What percentage of people without advanced education make more than 50K?
* What is the minimum number of hours a person works per week?
* What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?
* What country has the highest percentage of people that earn >50K and what is that percentage?
* What is the most popular occupation for those who earn >50K in India?

---
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

---
## Page Views Time Series Visualizer

Link to the code at Google Colab: <https://colab.research.google.com/drive/1ZbY_aHa4oumMbHFTY816ZCM49RSgGFdA>

This dataset contains time series data. Specifically, it contains the number of page views each day on the freeCodeCamp.org forum from 2016-05-09 to 2019-12-03.

Data visualizations help in understanding the patterns in visits and identify yearly and monthly growth of the freeCodeCamp.org forum.
