## Sleep-Wake Cycle Hormone Analysis

I worked on this project as part of the Digital Health and Human Behavior course at Aalto University.
In this project, I use the [MMASH dataset](https://physionet.org/content/mmash/1.0.0/) (Multilevel Monitoring of Activity and Sleep in Healthy people) to study how sleep patterns, physical activities, and stress levels influence melatonin and cortisol level in the sleep-wake cycle. 
The more report and key visualization of the project can be found in [the report folder](https://github.com/lucienguyen/sleep-analysis-dhhb25/tree/main/report).


**Grade: ~95/100**

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

# Key Findings

Statistical Insights

- Strong correlation between cortisol and melatonin levels after sleep
- Significant increase in cortisol levels post-sleep
- Potential relationships between screen time, daily activities, and hormone regulation

Machine Learning Results

- Random Forest outperformed Linear Regression in predicting post-sleep cortisol levels
- Average RMSE: 0.046 (Random Forest) vs 0.087 (Linear Regression)
