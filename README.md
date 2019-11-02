# Hypothesis Testing

This repository is a collection of notes describing and explaining a number of common hypothesis tests that can be carried in data science.

Each notebook contains a description and explanation of a hypothesis test and how to perform the hypothesis test in python using a library called SciPy.

[SciPy Library](https://www.scipy.org/)

This repo contains a number of hypothesis tests that can be carried out for both numerical and categorical situations.

# Glossary

Null Hypothesis

A null hypothesis is a hypothesis that says there is no statistical significance between two variables. This is commonly abberviate to H_0. 

Alternative Hypothesis

An alternative hypothesis is a hypothesis that states there is a statistically significant relationship between two variables. This is commonly abberviated to H_A.

Signifiance Level

The significance level (alpha) is a mesure of the strength of evidence that must be present in your sample before you will reject the null hypothesis. This is set before the experiment begins.

It is the probability of rejecting the null hypothesis when it is true. Lower significance levels indicate that you require stronger evidence before you reject the null hypothesis.

Example - A significance level of 0.05 indicates a 5% risk of concluding that a difference exists when there isn't one.

p-value

The p-value is the probability of obtaining the result from a statistical test or more extreme given the null hypothesis is true.

A p-value of say 0.03 for example, means that there is a 3% chance of finding a difference as large or larger, given the null hypothesis is true.

Type 1 Error

A type 1 error also known as a false positive, is the error of rejecting a null hypothesis when it is actually true. This is tie to the significance level which can be thought of as the probability of rejecting the null hypothesis when it is true.

Type 2 Error

A type 2 error also known as a false negative, is the error of not rejecting a false null hypothesis.

The type 2 error rate is denoted by the greek letter (beta) and is related to the power of a test (which is 1- beta). The higher the power of the test the lower the probability of a type 2 error.

Power Analysis

Power analysis is conducted to determine the smallest sample size that is suitable to detect the effect of a given test at the desired level of significance.

One Sample T-Test

Two Sample T-Test

ANOVA

Tukeys Range Test

Binomial Test

Chi Square Test

# Numerical
[One Sample T-Test](https://github.com/rosslogan702/hypothesis_testing_notes/blob/master/one_sample_t_tests.ipynb)  
[Two Sample T-Test](https://github.com/rosslogan702/hypothesis_testing_notes/blob/master/two_sample_t_test.ipynb)  
[ANOVA](https://github.com/rosslogan702/hypothesis_testing_notes/blob/master/anova.ipynb)  
[Tukeys Range Test](https://github.com/rosslogan702/hypothesis_testing_notes/blob/master/tukeys_range_test.ipynb)

# Categorical
[Binomial Tests](https://github.com/rosslogan702/hypothesis_testing_notes/blob/master/binomial_test.ipynb)  
[Chi Square](https://github.com/rosslogan702/hypothesis_testing_notes/blob/master/chi_square_test.ipynb)

# Power Analysis
[Sample Size Determination](https://github.com/rosslogan702/hypothesis_testing_notes/blob/master/sample_size_determination.ipynb)
