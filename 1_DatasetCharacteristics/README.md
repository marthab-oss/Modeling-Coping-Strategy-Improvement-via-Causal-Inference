# Dataset Characteristics

**[Notebook](exploratory_data_analysis.ipynb)**

## Dataset Information

### Dataset Source
- **Dataset Link:** [https://www.kaggle.com/datasets/cloverchen/causalpitfalls-benchmark-causal-data-neurips-2025]
- **Dataset Owner/Contact:** Dataset from Kaggle, no author named

### Dataset Characteristics
- **Number of Observations:** 500
- **Number of Features:** 8

### Target Variable/Label
- **Label Name:** coping_strategy_improvement
- **Label Type:** Regression
- **Label Description:** ability to adapt to problems or new environment, and is dependent on the socio- economic environment
- **Label Values:** range: 0.18 - 10.80
- **Label Distribution:** mostly concentrated between values of 4 and eight, histogramm close to a gausian curve. Same applies to other features, except the first one, which only gives 0 or 1 for educational intervention yes or no.

### Feature Description
all features have the same data type: int64

- **Feature 1 (educational_intervention):** extra support for students, range: 0-1
- **Feature 2 (coping_strategy_improvement):** ability to adapt to new environment, range: 0.18-10.80
- **Feature 3 (social_support_enhancement):** governmental support for family, range: 0.49 - 16.45
- **Feature 4 (mental_health_score):** how stable and resilient the psychological state is, range: 66.98 - 238.63
- **Feature 5 (socioeconomic_status):** the purchase power linked to social status in society, range: 3.24 - 3.85 
- **Feature 6 (school_quality_score):** status of attended school compared to (in amount of cancelled lessons, relationship between pupil and teacher, motivation, budget of school,..) other schools, range: 53.22 - 112.61
- **Feature 7 (baseline_cognitive_score):** overall brain function (logical thinking, memory, attention, processing speed, ..), range: 59.98 - 156.02
- **Feature 8 (random_noise):** values not significant for dataset, range: -2.93 - 3.24

## Exploratory Data Analysis

The exploratory data analysis is conducted in the [exploratory_data_analysis.ipynb](exploratory_data_analysis.ipynb) notebook, which includes:

- Data loading and initial inspection
- Statistical summaries and distributions:
  <img width="1200" height="1200" alt="Histogramm" src="https://github.com/user-attachments/assets/51552bf5-8c94-4639-9cfe-05cdc1cd69e8" />
- Missing value analysis: no missing values
- Feature correlation analysis:
 <img width="640" height="480" alt="Correlation_Matrix (1)" src="https://github.com/user-attachments/assets/b0b56ce2-547f-46e2-bb5f-f4588d7f334e" />
- Data visualization and insights:
- Data quality assessment: 
