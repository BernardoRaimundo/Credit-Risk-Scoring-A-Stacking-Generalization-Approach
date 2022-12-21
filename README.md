# Credit-Risk-Stacking-Ensemble
<p align="justify"> 
Credit risk regulation has been receiving tremendous attention, as a result of the effects of the latest global financial crisis. According to the developments made in the Internal Rating Based approach, under the Basel guidelines, banks are allowed to use internal risk measures as key drivers to assess the possibility to grant a loan to an applicant. Credit scoring is a statistical approach used for evaluating potential loan applications in both financial and banking institutions. When applying for a loan, an applicant must fill out an application form detailing its characteristics (e.g., income, marital status, and loan purpose) that will serve as contributions to a credit scoring model which produces a score that is used to determine whether a loan should be granted or not. This enables faster and consistent credit approvals and the reduction of bad debt. Currently, many machine learning and statistical approaches such as logistic regression and tree-based algorithms have been used individually for credit scoring models. Newer contemporary machine learning techniques can outperform classic methods by simply combining models.
<p align="justify"> 
This project intends to be an empirical study on a publicly available bank loan dataset to study banking loan default, using ensemble-based techniques to increase model robustness and predictive power. The proposed ensemble method is based on stacking generalization an extension of various preceding studies that used different techniques to further enhance the model predictive capabilities. The results show that combining different models provide a great deal of flexibility to credit scoring models.

This project is composed of the following notebooks:

1) Exploratory Data Analysis
2) Feature Engeneering + model implementations
3) Final Ensemble Model Combination

Dataset available at: https://www.kaggle.com/datasets/wordsforthewise/lending-club?select=rejected_2007_to_2018Q4.csv.gz

References:

[1] Yao, Y., Vehtari, A.,  Simpson, D., & Gelman, A. (2017). Using Stacking to Average Bayesian Predictive Distributions. Bayesian Analysis. 13. 
https://doi.org/10.1214/17-BA1091.
[2] Dietterich, T.G. (2000). Ensemble methods in machine learning. Multiple Classifier Systems: First International Workshop, MCS 2000, Lecture Notes in Computer Science. 1-15. https://doi.org/10.1007/3-540-45014-9_1
[3] James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An Introduction to Statistical Learningwith Applications in R (8th ed.). Springer New York Heidelberg Dordrecht London. https://doi.org/10.1007/978-1-4614-7138-7
