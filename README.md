# Stats-concepts
general stats concepts

AIC: Akaike’s Information Criterion
https://www.statisticshowto.datasciencecentral.com/akaikes-information-criterion/

Log-likelihood: the natural logarithm of the likelihood
https://www.statlect.com/glossary/log-likelihood#targetText=In%20turn%2C%20given%20a%20sample,Definition

Marginal Models: a type of linear model that accounts for repeated response measures on the same subject
Five Extensions of the General Linear Model: https://www.theanalysisfactor.com/extensions-general-linear-model/#targetText=Marginal%20models%20are%20a%20type,observations%20of%20a%20single%20subject.

Robust Standard Errors: a technique to obtain unbiased standard errors of OLS coefficients under heteroscedasticity
https://economictheoryblog.com/2016/08/07/robust-standard-errors/#targetText=%E2%80%9CRobust%E2%80%9D%20standard%20errors%20is%20a,of%20OLS%20coefficients%20under%20heteroscedasticity.&targetText=%E2%80%9CRobust%E2%80%9D%20standard%20errors%20have%20many,the%20sandwich%20estimator%20of%20variance.

Bonferonni correction: divide the alpha value by the number of tests

Holm-Bonferroni Method: It is a modification of the Bonferroni correction. The Bonferroni correction reduces the possibility of 
getting a statistically significant result (i.e. a Type I error) when performing multiple tests. Although the Bonferroni is 
simple to calculate, it suffers from a lack of statistical power. The Holm-Bonferroni method is also fairly simple to 
calculate, but it is more powerful than the single-step Bonferroni. https://www.statisticshowto.datasciencecentral.com/holm-bonferroni-method/

Block randomization: designed to randomize subjects into groups that result in equal sample sizes. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3136079/

Cox proportional hazards regression: survival analysis http://www.sthda.com/english/wiki/cox-proportional-hazards-model

Standard deviation of the residuals: https://www.khanacademy.org/math/ap-statistics/bivariate-data-ap/assessing-fit-least-squares-regression/v/standard-dev-residuals

Standard deviation vs. standard error of the mean: standard error of the mean is the measure of how far your sample mean is likely to be from the true mean of the population. So the lower your SEM is, the more likely it is that your calculated mean is close to the actual mean. Estimate SEM: SEM = SD / sqrt(n).
SD is a measure of the variability of the data, and SEM is a measure of precision of the data.
https://www.youtube.com/watch?v=3UPYpOLeRJg

{
Sample statistic: a metric calculated for a sample of data drawn from a larger population.

Data distribution: The frequency distribution of individual values in a data set.

Sampling distribution: The frequency distribution of a sample statistic over may samples or resamples.

Central limit theorem: The tendency of the sampling distribution to take on normal shape as sample size rises. (Why so important: https://tutorials.methodsconsultants.com/posts/the-central-limit-theorem-and-its-implications-for-statistical-inference/)

STANDARD ERROR: The variability (standard deviation) of a sample statistic over many samples (not to be confused with standard deviation, which, by itself, refers to variability of individual data values).
}

Why Overlapping Confidence Intervals mean Nothing about Statistical Significance:
https://towardsdatascience.com/why-overlapping-confidence-intervals-mean-nothing-about-statistical-significance-48360559900a

Maximum likelihood estimation: 

Likelihood function: 

Combinations vs Permutations: https://medium.com/i-math/combinations-permutations-fa7ac680f0ac

intracluster correlation coefficient (ICC): a measure of the relatedness of clustered data. Values range from 0 to 1 in human studies. If 1, all responses within a cluster are identical. A very small value for ρ implies that the within-cluster variance is much greater than the between-cluster variance, and a ρ of 0 shows that there is no correlation of responses within a cluster. 
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1466680/

Coefficient of variation: also known as relative standard deviation (RSD), is a standardized measure of dispersion of a probability distribution. It is often expressed as a percentage, and is defined as the ratio of the standard deviation {sigma} to the mean {mu}b(or its absolute value, {|mu|}.
https://en.wikipedia.org/wiki/Coefficient_of_variation

Marginal distribution and conditional distribution: https://www.khanacademy.org/math/ap-statistics/analyzing-categorical-ap/distributions-two-way-tables/v/marginal-distribution-and-conditional-distribution

Degrees of freedom: the number of degrees of freedom is the number of values in the final calculation of a statistic that are free to vary.
https://www.statisticshowto.datasciencecentral.com/degrees-of-freedom/
http://www.rondotsch.nl/degrees-of-freedom/

Sampling distribution: Suppose we draw all possible samples of size n from a given population. Suppose further that we compute a statistic (eg. a mean, proportion, standard deviation) for each sample. The probability distribution of this statistic is called a sampling distribution. And the standard deviation of this statistic is called the standard error.
https://stattrek.com/sampling/sampling-distribution.aspx

BCa: Bias- corrected and accelerated confidence interval.
Bias correction: https://garstats.wordpress.com/2018/01/23/bias-correction/

Which statistical test should you use:
https://help.xlstat.com/s/article/which-statistical-test-should-you-use?language=en_US
https://stats.idre.ucla.edu/other/mult-pkg/whatstat/

Something to read: https://www.johndcook.com/blog/2009/06/25/probability-approximation/
