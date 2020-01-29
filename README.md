# Stats
Statistics Basics and Advanced

## A/B Testing

* A/B testing, also known as split testing, is a marketing experiment wherein you "split" your audience to test a 
  number of variations of a campaign and determine which performs better. 
* In other words, you can show version A of a piece of marketing content to one half of your audience, 
  and version B to another.


**There are several types of A/B tests. You should choose the one that best fits your particular situation.**

* Classic A/B test. The classic A/B test presents users with two variations of your pages at the same URL. 
  That way, you can compare two or several variations of the same element.

* Split tests or redirect tests. The split test redirects your traffic towards one or several distinct URLs. 
  If you are hosting new pages on your server, this could be an effective approach.

* Multivariate or MVT test. Lastly, multivariate testing measures the impact of multiple changes on the same web page. 
  For example, you can modify your banner, the color of your text, your presentation, and more.


Your A/B tests must be complemented by additional information in order to identify conversion problems and offer an 
understanding of user behavior. This analysis phase is critical, and must help you to create “strong” hypotheses. 
The disciplines mentioned above will help. 

**A correctly formulated hypothesis is the first step towards a successful A/B testing program and must respect the following rules.**

*Hypotheses must:*

* be linked to a clearly discerned problem that has identifiable causes
* mention a possible solution to the problem
* indicate the expected result, which is directly linked to the KPI to be measured


**Before A/B Test**

1. Pick one variable to test.
2. Identify your goal.
3. Create a 'control' and a 'challenger.'
4. Split your sample groups equally and randomly.
5. Determine your sample size (if applicable).
6. Decide how significant your results need to be.
7. Make sure you're only running one test at a time on any campaign.

**During the A/B Test**

8. Use an A/B testing tool.
9. Test both variations simultaneously.
10. Give the A/B test enough time to produce useful data.
11. Ask for feedback from real users.

**After the A/B Test**

12. Focus on your goal metric.
13. Measure the significance of your results using our A/B testing calculator.
14. Take action based on your results.
15. Plan your next A/B test.


### Tips and best practices for A/B testing

Below are several best practices that can help you avoid running into trouble. 

* **Ensure data reliability for the A/B testing solution**

Conduct at least one A/A test to ensure a random assignment of traffic to different versions. This is also an opportunity to compare the A/B testing solution indicators and those of your web analytics platform. This is done in order to verify that figures are in the ballpark, not to make them correspond exactly.

* **Conduct an acceptance test before starting**

Do some results seem counter-intuitive? Was the test set up correctly and were the objectives correctly defined? In many cases, time dedicated to acceptance testing saves precious time which would be spent interpreting false results.

* **Test one variable at a time**

This makes it possible to precisely isolate the impact of the variable. If the location of an action button and its label are modified simultaneously, it is impossible to identify which change produced the observed impact.

* **Conduct one test at a time**

For the same reasons cited above, it is advisable to conduct only one test at a time. The results will be difficult to interpret if two tests are conducted in parallel, especially if they’re on the same page.

* **Adapt number of variations to volume**

If there is a high number of variations for little traffic, the test will last a very long time before giving any interesting results. The lower the traffic allocated to the test, the less there should be different versions.

* **Wait to have a statistical reliability before acting**

So long as the test has not attained a statistical reliability of at least 95%, it is not advisable to make any decisions. The probability that differences in results observed are due to chance and not to the modifications made is very high otherwise.

* **Let tests run long enough**

Even if a test rapidly displays statistical reliability, it is necessary to take into account the size of the sample and differences in behavior linked to the day of the week. It is advisable to let a test run for at least a week—two ideally—and to have recorded at least 5,000 visitors and 75 conversions per version.

* **Know when to end a test**

If a test takes too long to reach a reliability rate of 95%, it is likely that the element tested does not have any impact on the measured indicator. In this case, it is pointless to continue the test, since this would unnecessarily monopolize a part of the traffic that could be used for another test.

* **Measure multiple indicators**

It is recommended to measure multiple objectives during the test. One primary objective to help you decide on versions and secondary objectives to enrich the analysis of results. These indicators can include click rate, cart addition rate, conversion rate, average cart, and others.

* **Take note of marketing actions during a test**

External variables can falsify the results of a test. Oftentimes, traffic acquisition campaigns attract a population of users with unusual behavior. It is preferable to limit collateral effects by detecting these kinds of tests or campaigns.

* **Segment tests**

In some cases, conducting a test on all of a site’s users is nonsensical. If a test aims to measure the impact of different formulations of customer advantages on a site’s registration rate, submitting the current database of registered users is ineffective. The test should instead target new visitors.


## Hypothesis Testing

Hypothesis testing is an objective method of making decisions or inferences from sample data (evidence). 
Sample data is used to choose between two choices i.e. hypotheses or statements about a population. 
Typically this is carried out by comparing what we have observed to what we expected if 
one of the statements (Null Hypothesis) was true.

*Key terms:*  

**NULL HYPOTHESIS (H0)** is a statement about the population & sample data used to decide whether to reject that statement or not. 
                 Typically the statement is that there is no difference between groups or association between variables. 

**ALTERNATIVE HYPOTHESIS (H1)** is often the research question and varies depending on whether the test is one or two tailed. 

**SIGNIFICANCE LEVEL:** The probability of rejecting the null hypothesis when it is true, (also known as a type 1 error). 
                    This is decided by the individual but is normally set at 5% (0.05) which means that there is a 1 in 20 chance of 
                    rejecting the null hypothesis when it is true. 

**TEST STATISTIC** is a value calculated from a sample to decide whether to accept or reject the null (H0) and varies between tests. 
                    The test statistic compares differences between the samples or between observed and expected values when the 
                    null hypothesis is true. 

**P-VALUE:** the probability of obtaining a test statistic at least as extreme as ours if the null is true and there 
         really is no difference or association in the population of interest. 
         P-values are calculated using different probability distributions depending on the test. 
         A significant result is when the p-value is less than the chosen level of significance (usually 0.05). 
         
         

*The court case :* 

Hypothesis testing can be thought of as a court caseMembers of a jury have to decide whether a person is guilty or 
innocent based on evidence presented to them.

*Null: The person is innocent*

*Alternative: The person is not innocent.*

The null can only be rejected if there is enough evidence to disprove it and the jury do not know whether the person 
is really guilty or innocent so they may make a mistake.


## Confidence Interval

* The Confidence interval is the range of values that we believe will have a specified chance of containing 
the unknown population parameter.

* It gives us the information about the precision of a point estimate such as the sample mean.

* Confidence Intervals describe the variability surrounding the sample point estimate (the wider the interval, 
the less confident we can be about the estimate of the population mean). 

* In general, all things being equal, the larger the sample size the better (more precise) the estimate is, 
  as less variation between sample means is expected.

* In simple terms, CI will tell you the most likely range of the un-known population mean or proportion.

*The confidence is in the method, not in any interval.*


**Three things affect the width of a confidence interval:**

**1. Confidence Level:** usually 95%.

**2. Variability:** if there is more variation in a population, each sample taken will fluctuate more and wider 
the confidence interval. The variability of the population is estimated using the standard deviation from the sample.

**3. Sample size:** without lowering the confidence level, the sample size can control the width of a confidence interval, 
having an inverse square root relationship to it.


## P-value  

Expresses the probability that extreme results obtained in an analysis of sample data are due to chance. 

We choose the probability level or p-value that defines when sample results will be considered strong enough to 
support rejection of the null hypothesis. A low p-value (for example, less than 0.05) means that the null hypothesis 
is unlikely to be true. 

With null hypothesis testing, all it takes is sufficient evidence (instead of definitive proof) 
that we can see as at least some difference. The size of the difference is given by the confidence interval around the 
difference. 

**A small p-value might occur:**

1. by chance
2. because of problems related to data collection 
3. because of violations of the conditions necessary for testing procedure 
4. because H0 is true If multiple tests are carried out, some are likely to be significant by chance alone!

For sigma = 0:05,we expect that significant results will be 5% of the time. Be suspicious when you see a few 
significant results when many tests have been carried out or significant results on a few subgroups of the data.



## Type I vs Type II error 


If we wrongly say that there is a difference, we have a Type I error. 

If we wrongly say there is no difference, it is called Type II error.


#### Design an experiment to see whether a new feature is better

**Questions:**

* How often Y occurs? Do X and Y co-vary? (requires measuring X and Y) 

* Does X cause Y? (requires measuring X and Y and measuring X, and accounting for other independent variables) 

We have: 
* goals for visitor (sign up, buy). 
* metrics to improve (visit time, revenue, return). 

We are manipulating independent variables (independent of what the user does) to measure dependent variables 
(what the user does). 

We can test 2 versions with a A/B test, or many full versions of a single page. 

How different web pages perform using a random sample of visitor: define what percentage ofthe visitor are 
included in the experiment, chose which object to test.


#### How do you test a data sample to see whether it is normally distributed? 

* I would first plot the frequencies, comparing thehistogram of the sample to a normal probability curve. 
This might be hard to see if the sample is small,in this case we can regress the data against the quantities 
of a normal distribution with the same mean and variance as the sample, the lack of fit to the regression line 
suggests a departure from normality. 

* Another thing you can do, a back-of-the-envelope calculation, is taking the sample's maximum and minimum and 
compute the z-score (ormore properly the t-statistics), which is the num-ber of sample standard deviations that a 
sample is above or below the mean: z = (x - mean(x)) / (s/sqrt(N)) and then compares it to the 68-95-99.7 rule. 

* If you have a 3 sigma event and fewer than 300samples, or a 4 sigma event and fewer than 15k 
samples, then a normal distribution understatesthe maximum magnitude of deviations in the data.


#### Given a dataset, how do you determine its sample distribution? 

* Please provide at leasttwo methods. Plot them using histogram: it should give you and idea as to what parametric 
fam-ily(exponential, normal, log-normal...) might provide you with a reasonable fit. 
* If there is one,you can proceed with estimating the parameters. 
* If you use a large enough statistical sample size, you can apply the Central Limit Theorem to a sample proportion 
for categorical data to find its sampling distribution. 

* Distributions based on responses
    1. You may have 0/1 responses, so the distribution is binomial, 
    2. maybe conditional on some other covariates, that's a logistic regression. 
    3. You may have counts, so the distribution is Poisson. 
    4. Regression to fit, test chi-square to the goodness of the fit. 

* Also a small sample (say under 100) will be compatible with many possible distributions,
 there is simply no way distinguishing between them on the basis of the data only. 
 
* On the other hand, large samples (say more than 10000) won't becompatible with anything.



#### What's the difference between the t-stat and R2 in a regression? What does each measure?  When you get a very large value in one but avery small value in the other, what does that tell you about the regression? 

* Correlation is a measure of association between two variables, the variables are not designated as dependent or 
independent. 

* The significance(probability) of the correlation coefficient is determined from the t-statistic.
 
* The test indicates whether the observed correlation coefficient occurred by chance if the true correlation is zero. 

* Regression is used to examine the relationship between one dependent variable and one independent variable. 

* The regression statistics can be used to predict the dependent variable when the independent variables is known. 

* Regression goes beyond correlation by adding prediction capabilities. 

* The significance of the slope of the regression line is determined from the t-statistic. It is the probability 
  that the observed correlation coefficient occurred by chance if the true correlation is zero. 

* Some researchers prefer to report the F-ratio instead of the t-statistic. The F-ratio is equal to the t-statistic squared. 

* The t-statistic for the significance of the slope is essentially a test to determine if the 
  regression coefficients are significant or not.