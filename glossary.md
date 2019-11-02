# Glossary

**Null Hypothesis**

A null hypothesis is a hypothesis that says there is no statistical significance between two variables. This is commonly abberviate to H_0. 

**Alternative Hypothesis**

An alternative hypothesis is a hypothesis that states there is a statistically significant relationship between two variables. This is commonly abberviated to H_A.

**Signifiance Level**

The significance level (alpha) is a mesure of the strength of evidence that must be present in your sample before you will reject the null hypothesis. This is set before the experiment begins.

It is the probability of rejecting the null hypothesis when it is true. Lower significance levels indicate that you require stronger evidence before you reject the null hypothesis.

Example - A significance level of 0.05 indicates a 5% risk of concluding that a difference exists when there isn't one.

**P-Value**

The p-value is the probability of obtaining the result from a statistical test or more extreme given the null hypothesis is true.

A p-value of say 0.03 for example, means that there is a 3% chance of finding a difference as large or larger, given the null hypothesis is true.

**Type 1 Error**

A type 1 error also known as a false positive, is the error of rejecting a null hypothesis when it is actually true. This is tie to the significance level which can be thought of as the probability of rejecting the null hypothesis when it is true.

**Type 2 Error**

A type 2 error also known as a false negative, is the error of not rejecting a false null hypothesis.

The type 2 error rate is denoted by the greek letter (beta) and is related to the power of a test (which is 1- beta). The higher the power of the test the lower the probability of a type 2 error.

**Power Analysis**

Power analysis is conducted to determine the smallest sample size that is suitable to detect the effect of a given test at the desired level of significance.

**One Sample T-Test**
A One Sample T-Test (or univariate T-test) compares a sample mean to a hypothetical population mean.
The One Sample T-Test is concerned with the question:

"*What is the probability that the sample of interest came from a distribution with the desired mean?*"

**Two Sample T-Test**

A 2 sample t-test investigates whether the means of two independent samples of data differ from each other.

Example
Suppose that the average sales per day last week for an online store was 210 items per day. 

This week the average sales figure per day is 285 items. Did the average sales figure per day change or is this just part of natural fluctuations?

The 2 Sample T-Test could be used to try and determine this.

**ANOVA**

ANOVA (Analysis of Variance) tests the null hypothesis that all of the datasets have the same mean. 
If we reject the null hypothesis when performing an ANOVA test, this tells us that at least one of the datasets has a different mean.  
However it does not inform us which of the datasets are different.

**Tukeys Range Test**

Tukey's range test is used to determine if there are significant differences between datasets.  

Where an ANOVA test will only tell you if there is a significant difference between say 3 datasets being tested, Tukey's range test will specifically tell you which datasets there is a significant difference between.  

Tukey's range test compares the means of different groups and will tell you which ones have a significant difference.

**Binomial Test**

A binomial test compares a categorical dataset to some expectation.
Examples of where a Binomial Test would be used could:

*   Comparing the number of market emails opened by users to some target value
*   Comparing the number of tails from 100 coin flips to the expected number of tails from 100 flips 

**Chi Square Test**

One of the use cases of a Chi Square test is when we want to compare two or more categorical sets of data. 
It is useful and often used in A/B testing.

Example uses:

* An A/B test where half of the users were shown a blue submit button and the other half a purple submit button on web funnel landing page. Which group was more likely to click on the button?
