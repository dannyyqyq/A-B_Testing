# Assessing Campaign Performance Using Chi-Square Test For Independence

This project applies the Chi-Square Test For Independence to analyze the performance of two mailer types (low-cost and high-cost) used to promote a new service.

## Project Overview

* **Context:** A grocery retailer ran a campaign to promote their "Delivery Club" using two types of mailers. They want to know if there's a significant difference in signup rates between the low-cost and high-cost mailers.
* **Actions:** Chi-Square Test For Independence was applied to compare the signup rates. Data was prepared, hypotheses were stated (Null: no relationship, Alternate: relationship), and the test was executed using Python's `scipy` library.
* **Results & Discussion:** While the high-cost mailer had a higher signup rate, the Chi-Square test indicated no statistically significant difference (p-value = 0.16, Chi-Square Statistic = 1.94, Critical Value = 3.84). Thus, the null hypothesis was retained. The project recommends further testing with more data.

## Concept Overview

* **A/B Testing:** Randomized experiments to compare two groups and drive business decisions.
* **Hypothesis Testing:** Statistical method to assess the plausibility of a viewpoint based on sample data.
* **Chi-Square Test For Independence:** A hypothesis test to determine if there's a relationship between two categorical variables.

## Data Overview & Preparation

* The project used campaign data, excluding the control group, focusing on customers who received either the low-cost or high-cost mailers.
* Data was prepared using pandas library in python.

## Applying Chi-Square Test For Independence

* Hypotheses and acceptance criteria (0.05) were defined.
* Observed and expected frequencies were calculated, and the Chi-Square test was performed.

## Analysing The Results

* The p-value and Chi-Square statistic were used to determine if the null hypothesis should be rejected.
* The project provides python code to automate the result analysis.

## Discussion

* The analysis suggests that the higher cost mailer did not significantly increase signup rates compared to the lower cost mailer.
* Further A/B testing with more data is recommended for a more robust conclusion.
