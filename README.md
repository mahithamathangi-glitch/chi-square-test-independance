# Chi-Square Test of Independence

## Project Overview

This project demonstrates the use of the Chi-Square Test of Independence
to determine whether two categorical variables are statistically associated.

The Titanic dataset is used for the analysis.

## Objective

To determine whether there is a statistically significant association
between passenger sex and survival status.

## Dataset

The Titanic dataset contains information about passengers including
their sex, survival status, passenger class, age, fare, and other attributes.

## Variables Used

### Independent Variable
Sex

Categories:
- Male
- Female

### Dependent Variable
Survival Status

Categories:
- Did Not Survive
- Survived

## Hypotheses

### Null Hypothesis (H0)

There is no statistically significant association between sex and survival status.

### Alternative Hypothesis (H1)

There is a statistically significant association between sex and survival status.

## Significance Level

The significance level used for the test is:

α = 0.05

## Methodology

1. Load the Titanic dataset.
2. Select the categorical variables.
3. Remove missing values.
4. Create a contingency table using Pandas crosstab().
5. Calculate expected frequencies.
6. Perform the Chi-Square Test of Independence using SciPy.
7. Compare the p-value with the significance level.
8. Interpret the result using statistical reasoning.
9. Visualize the relationship using bar charts and a heatmap.

## Contingency Table

The contingency table compares the number of passengers who survived
and did not survive across male and female passengers.

## Statistical Results

The Chi-Square Test produces:

- Chi-Square Statistic: approximately 260.717
- Degrees of Freedom: 1
- P-value: approximately 1.197 × 10^-58

## Decision

Since:

p-value < 0.05

the null hypothesis is rejected.

## Conclusion

There is a statistically significant association between passenger sex
and survival status in the Titanic dataset.

The analysis shows that survival outcomes differed substantially
between male and female passengers.

However, statistical association should not be interpreted as proof
of causation.

## Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Project Files

- `Chi_Square_Test_of_Independence.ipynb` - Complete analysis
- `README.md` - Project documentation
- `requirements.txt` - Python dependencies

## Key Learning Outcomes

- Understanding categorical variables
- Creating contingency tables
- Understanding expected frequencies
- Performing Chi-Square Tests
- Interpreting p-values
- Understanding statistical independence
- Communicating statistical conclusions
