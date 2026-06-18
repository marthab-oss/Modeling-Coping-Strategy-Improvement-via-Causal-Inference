# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: [Predictive modeling of academic outcomes based on
socioeconomic variables]

  - **[Link](https://ceur-ws.org/Vol-4146/short04.pdf)**
  - **Objective**: classify students in passing and failing
  - **Methods**: used Tree based ensemble models XGBoost, LightGBM, . CatBoost, Explainable Boosting Machine (EBM): 
  - **Outcomes**: Accuracy ≈ 0.7
  - **Relation to the Project**: same topic (features include: Academic performance, Family and parental background, , Support and study habits, Demographics and daily life) but different approach as they were classfiying. interesting is the handling of the topic

- **Source 2**: [Using the Bayesian Network Method to Evaluate the Effectiveness of College Students’ Mental Health Intervention Strategies and Their Impact on Academic Performance
]

  - **[Link](https://journals.sagepub.com/doi/10.1177/07342829251393575)**
  - **Objective**: predict academic performance and psychological risk across students 
  - **Methods**: Dynamic Bayesian Networks (DBN) and Bayesian Networks (BN)
  - **Outcomes**: BN: 91.0% accuracy, DBN: 94.2% accuracy; uncertainty-resilient prediction of both psychological risk and academic outcomes among university students.
  - **Relation to the Project**: BN works similar to DAG, that I used in the project and the paper focused on the same sequential mediation topic

- **Source 3**: [Machine learning-based academic performance prediction with explainability for enhanced decision-making in educational institutions]

  - **[Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC12290028/)**
  - **Objective**: predictin of academic performance based on study behaviors, prior performance, and extracurricular activitie, academic habits, demographic attributes, and institutional factors such as attendance, teacher quality, and parental involvement
  - **Methods**: 10 regression models including K-Nearest Neighbors Regressor, Linear Regression, CatBoost, XGBoost, AdaBoost, and ensemble voting regression (VR) algorithm; 2 datasets (10000 and 6000 samples)
  - **Outcomes**: first dataset: RMSE of 0.1050, MAE of 0.0837, and R² of 0.9890; and R² of 0.7 in second set.
  - **Relation to the Project**: similar features used, including socio-economic environment and universitary skills
