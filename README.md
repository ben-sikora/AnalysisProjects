# Heart Disease Indicators: Analyzing CDC Survey Data to Identify High Risk Individuals

While I have built many different projects as an analyst, the one that I am most proud of was my final project for my Statistical Data Science class (To see my Java ML and AI projects, please reach out to me separately, as those repositories need to remain private.). My partner and I set out to predict heart disease among individuals based on underlying health parameters. My pride in the project is because of its scale and technical complexity. The dataset we used had 253,680 entries and 21 variables. On top of general analyses, we used unsupervised and supervised algorithms to generate and compare dozens of different predictor models. Choosing our final model required rigorous testing and analysis and a careful understanding of its impact. While I have been developing statistical tools throughout my career, this project was the summation of much of my work as a data scientist.

I understand it is slightly complicated to present a collaborative project. To set expectations, my partner worked on the introduction and unsupervised model while I worked on the two supervised models and the conclusion. After the initial draft, however, we thoroughly reviewed each other's work to help with debugging and analysis. The work was not split for any gap in each other's understanding but simply to complete the project at hand. 

As part of the project, my partner and I wrote a substantial report in the repository as a [PDF](https://github.com/ben-sikora/HeartDiseasePredictor/blob/main/Final-Project-Beta.pdf). It explains every aspect of the assignment, including background on the data set, models used, training, analysis, and model selection. I was tempted to paste the report here, but I will instead do my best to summarize it and highlight our points of struggle. I highly recommend reading the report to gain the best understanding of the project. 

# Overview of Work
The main question my partner and I were pursuing was to see how well we could predict heart disease given health data from survey responses. We used a dataset from Kaggle, but it was initially part of released survey data from the CDC. We conducted all our analysis in R, using appropriate libraries as necessary.

For our models, we used Principal Component Analysis, Logistic Regression, and K-Nearest Neighbor. To analyze performance, we used ROC curves with K-Fold Cross-validation to test how different cutoffs would affect accuracy, sensitivity, and specificity. And for the logistic regression, we selected our covariates using Lasso Penalized regression and tested for collinearity, model fit, outliers, and high-leverage observations.



