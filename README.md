## Sleep-Wake Cycle Hormone Analysis

I worked on this project as part of the Digital Health and Human Behavior course at Aalto University.
In this project, I aimed to study how sleep patterns, physical activities, and stress levels influence melatonin and cortisol level in the sleep-wake cycle. The project was graded ~95 in the scale 100. The project uses the MMASH (Multilevel Monitoring of Activity and Sleep in Healthy people) provided by Rossi et al. (2020).
Data source: Rossi, A., Eleonora, D. P., Menicagli, D., Tremolanti, C., Priami, C., Sirbu, A., Clifton, D., Martini, C., & Morelli, D. (2020, June). Multilevel Monitoring of Activity and Sleep in Healthy people. https://doi.org/10.13026/cerq-fc86
Grade: ~95/100

# Methods

For statistical analysis

- Correlation analysis (Pearson/Spearman) to identify relationships
- Hypothesis testing (t-tests) with Bonferroni correction
- Linear regression for relationship visualization

For machine Learning

- Models: Linear Regression vs Random Forest
- Validation: 5-fold cross-validation
- Evaluation: Root Mean Squared Error (RMSE)
- Features: Cortisol before sleep, MEQ score, sleep efficiency, daily stress, state anxiety
