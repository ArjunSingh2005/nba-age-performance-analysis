# NBA Performance & Fantasy Points Analysis 📊🏀

This repository contains statistical analyses of NBA player performance using data from the 2023–2024 season. The main focus is on how **age** influences performance, particularly scoring ability and fantasy points.

## 📁 Project Contents

- `Stat11_FinalPaper.pdf`: Full write-up of a statistical study on age and NBA performance using t-tests, linear regression, and logistic regression.
- `NbaAnalysis.pdf`: R-based analysis exploring fantasy point prediction using multiple linear regression.
- `nba2024.csv`: The dataset used, originally sourced from [Basketball Reference](https://www.basketball-reference.com/).

## 📌 Key Analyses

### 1. Two-Sample T-Test
- Compares points per game for players under 25 and over 30.
- Result: No significant scoring difference (p = 0.96).

### 2. Multiple Linear Regression
- Predicts Fantasy Points (FP) using:
  - Age
  - Minutes Played (MP)
  - Field Goal % (FG%)
  - Free Throw % (FT%)
- **FG% and MP** were significant predictors.
- **Age was not a significant factor** in FP prediction.

### 3. Logistic Regression
- Predicts likelihood of being a high-scoring player.
- **FG% and MP** had strong positive influence.
- **Age** showed a weak negative correlation.

## 📊 Tools & Libraries Used

- R (ggplot2, caret, pROC)
- Statistical methods: t-test, linear regression, logistic regression
- Diagnostic plots and ROC curve analysis

## 📈 Insights

- Younger and older players have similar scoring averages.
- Fantasy Points are best predicted by efficiency and minutes played—not age.
- Shooting efficiency (FG%) is the strongest predictor of being high-scoring.

---

## 📎 References

- [Basketball Reference](https://www.basketball-reference.com/)
- [Harvard Sports Analysis Collective](https://harvardsportsanalysis.org/)
- Bryant University Digital Repository
