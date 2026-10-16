# Global Superstore: Statistical Analysis & Regression Modelling

> **Team project** (SSDI course project, Team 12).

An end-to-end statistical analysis of the Global Superstore sales dataset in Python, from probability distributions to regularised regression and classification.

## What's covered
- **Probability distributions**: Normal (PDF, CDF, PPF), Binomial (profitable vs loss-making orders), Poisson (orders per day)
- **Maximum likelihood estimation**: closed-form, manual log-likelihood and numerical optimisation (Normal and Binomial)
- **Hypothesis testing**: z-test, one- and two-sample t-tests, chi-square (independence and goodness of fit)
- **Group comparisons**: ANOVA, two-way ANOVA with interaction, Tukey HSD post-hoc, MANOVA
- **Non-parametric tests**: sign test, Mann-Whitney U, Wilcoxon signed-rank, Kruskal-Wallis, Friedman
- **Bayesian inference**: conjugate Normal prior to posterior update with a 95% credible interval
- **Regression**: simple, polynomial, multiple and dummy-variable OLS; interaction terms; VIF; residual diagnostics
- **Regularisation**: Ridge, Lasso, RidgeCV / LassoCV, Lasso feature selection, k-fold cross-validation
- **Classification**: Gaussian Naive Bayes and logistic regression (odds ratios, confusion matrix, precision / recall / F1)

## Tech stack
Python · pandas · NumPy · SciPy · statsmodels · scikit-learn · Matplotlib · seaborn

## Run it
1. Download the Global Superstore dataset (`Global_Superstore2.csv`) and place it next to the notebook.
2. Open `global_superstore_statistical_analysis.ipynb` in Jupyter or Google Colab and run all cells.
