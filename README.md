# Credit-Risk-Stacking-Ensemble
<p align="justify">
Credit risk regulation has received tremendous attention, especially in the aftermath of the latest global financial crisis. Under the Basel guidelines and the Internal Rating Based approach, banks are permitted to use internal risk measures as key drivers to assess the viability of granting a loan to an applicant. Credit scoring, a statistical approach used for evaluating potential loan applications in financial and banking institutions, plays a crucial role in this process. When applying for a loan, an applicant must provide details such as income, marital status, and loan purpose, which contribute to a credit scoring model. This model produces a score used to determine the appropriateness of granting a loan, thereby enabling faster and more consistent credit approvals and reducing bad debt. Traditionally, machine learning and statistical approaches like logistic regression and tree-based algorithms have been employed individually for credit scoring models. However, newer contemporary machine learning techniques, which combine multiple models, can outperform these classic methods.
<p align="justify">
This project is an empirical study on a publicly available bank loan dataset, focusing on banking loan default and using ensemble-based techniques to enhance model robustness and predictive power. The proposed ensemble method, based on stacking generalization, extends various preceding studies that used different techniques to improve model predictive capabilities. The results demonstrate that combining different models offers significant flexibility to credit scoring models.

The project comprises the following notebooks:

1) Exploratory Data Analysis
2) Feature Engineering + Model Implementations
3) Final Ensemble Model Combination

Dataset available at: [Kaggle - Lending Club Dataset](https://www.kaggle.com/datasets/wordsforthewise/lending-club?select=rejected_2007_to_2018Q4.csv.gz)

References:

1. Yao, Y., Vehtari, A., Simpson, D., & Gelman, A. (2017). Using Stacking to Average Bayesian Predictive Distributions. Bayesian Analysis, 13. [Link](https://doi.org/10.1214/17-BA1091)
2. Dietterich, T.G. (2000). Ensemble methods in machine learning. In Multiple Classifier Systems: First International Workshop, MCS 2000, Lecture Notes in Computer Science, 1-15. [Link](https://doi.org/10.1007/3-540-45014-9_1)
3. James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An Introduction to Statistical Learning with Applications in R (8th ed.). Springer New York Heidelberg Dordrecht London. [Link](https://doi.org/10.1007/978-1-4614-7138-7)

