# Stats-and-probability-theory-and-codes

This file will help one to get through the concept of the statistics and probability for better analysis
Statistics is a branch that deals with the data collection and analysis on same based upon which we can further decide a result.

We have two different types of statistics :

Descriptive and Inferential 

Descriptive Statistics - It describe the characteristics of the data. It is a part of statistics that will help us summarize and describe the most important aspect of the data. It can Be mean, mode, median, max, min etc. 

Inferential Statistics - This will help us in generating inferences from the characteristics of the data.

These are the steps we need to perform for **Statistic Analysis ———> Important**

1. Data collection
2. Preparing samples
3. Creating two hypothesis (null hypothesis, alternate hypothesis)
4. Apply appropriate test (based on requirement or case)
5. p_value>0.05 -> accept null hypothesis
6. p_value<0.05 -> reject null hypothesis

# Descriptive Stats / Sample/ Population

- Population - This is the data on which we are going to work.
- Sample - It is always a subset or the part of a population. There is very high probability that sample will have same characteristics of the population.

# SAMPLING TECHNIQUES -

Random Sampling - 
If we are having a population it will create a subset by picking up the data randomly from the population. Each member has equal chance of getting picked.

**Definition**: Simple random sampling is a probability sampling method where each member of the population has an equal chance of being selected. This method ensures that the sample is unbiased and representative of the population.

**Example**: A researcher wants to survey 100 students out of a school of 1000 students about their food preferences. Each student is assigned a number from 1 to 1000, and a random number generator is used to pick 100 numbers. The students corresponding to these numbers are surveyed.

**When to Use**: Use simple random sampling when you have a complete list of the population and want to ensure that every member has an equal chance of being selected. It is suitable for small to moderately sized populations where the list of members is accessible.

Stratified Sampling - 
This works on the division of the data into sub groups/categories and then deals upon the same. 
- Define the characteristics of the data based upon the USP’s
- Determine the sample size.

**Definition**: Stratified sampling involves dividing the population into subgroups (strata) based on shared characteristics and then randomly sampling from each stratum. This method ensures that each subgroup is adequately represented in the sample.

**Example**: A researcher studying the GPA of college students might divide the population into strata based on majors (e.g., English, Science, Engineering) and then randomly select students from each major in proportion to their representation in the population.

**When to Use**: Use stratified sampling when the population has distinct subgroups, and you want to ensure that each subgroup is represented. It is particularly useful when there are significant differences between strata that could affect the study's outcome.

Systematic Sampling - 
It is a probability technique in which researcher selects the data based upon the order of any particular random interval. 

**Definition**: Systematic sampling is a probability sampling method where the researcher selects every nth member from the population list after a random starting point.

**Example**: A researcher wants to survey 200 customers out of a population of 2000. They decide to select every 10th customer after randomly choosing a starting point between 1 and 10.

**When to Use**: Use systematic sampling when you have a large, ordered population and want to ensure an even spread of the sample across the population. It is suitable for large populations where a complete list is available, and random selection is impractical.

**Cluster Sampling -** 

**Definition**: Cluster sampling involves dividing the population into clusters, usually based on geographical or organizational boundaries, and then randomly selecting entire clusters for the sample.

**Example**: A researcher studying the health outcomes of school children might divide the population into clusters based on schools. They then randomly select a few schools and include all students from those schools in the sample.

**When to Use**: Use cluster sampling when the population is large and geographically dispersed, making it impractical to conduct simple random sampling. It is suitable for studies where the population is naturally divided into clusters.

# **CENTRAL TENDENCY -**

If we want to get the idea about where the middle of the data is - 

It is a summary major that will represent the entire dataset through a single value. May be mean(average), median(middle value) or mode (Most occurring value).

Q1 - 0 % - 25%

Q2 - 25% - 50%

Q3 - 50% - 75%

Q4 - 75% - 100%

Distribution of data - Its determine how the data is distributed.

- Norma Distribution (**Gaussian distribution)**-  
The **Normal distribution**, also known as the **Gaussian distribution**, is one of the most important and widely used probability distributions in statistics. It describes how data points are distributed around a mean
It assumes that all the central tendency will be there together,  not equal but similar.
The **Normal distribution** is **symmetrical** about the mean, meaning the left and right sides are mirror images of each other.
The curve is often described as "bell-shaped" because of its peak at the mean, and it gradually tapers off toward the extremes.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/612f6771-8bf8-45f8-8937-3b4fbe35aea6/b42875b6-3e7f-4668-9868-13327edb22d0/image.png)

- Right Skewed Distribution (Positively Skewed Distribution)- 
A **right-skewed distribution** (also known as a **positively skewed** distribution) is a type of probability distribution where the **right tail** (larger values) is **longer** or **more stretched out** than the left tail. In simpler terms, in a right-skewed distribution, the majority of the data values are clustered toward the **left** (lower end), with a few extreme values on the **right** (higher end)
The tail on the right-hand side of the distribution is **longer** than the tail on the left-hand side.
There are **fewer** extreme high values, but they pull the mean to the right.

In a right-skewed distribution, the **mean** is typically greater than the **median**, and the **median** is greater than the **mode**. This happens because the extreme high values (outliers) on the right pull the mean upward.
**Mean > Median > Mode**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/612f6771-8bf8-45f8-8937-3b4fbe35aea6/b471be06-1ad8-4ac8-8459-81cc4e7979fa/image.png)

- **Left-Skewed Distribution (Negatively Skewed Distribution)-** 
A **left-skewed distribution** (also known as a **negatively skewed distribution**) is a type of probability distribution where the **left tail** (smaller values) is **longer** or **more stretched out** than the right tail.
The **tail** on the **left-hand side** of the distribution is **longer** than the tail on the right-hand side.
There are **fewer** extreme low values (outliers), but they pull the mean to the left.

In a left-skewed distribution, the **mean** is typically less than the **median**, and the **median** is less than the **mode**. This happens because the extreme low values (outliers) on the left pull the mean downward.
Mean < Median < Mode

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/612f6771-8bf8-45f8-8937-3b4fbe35aea6/25b79d56-51ae-411b-869a-38db80955fac/image.png)

# Variation / Z-Score / Technique in Stats

- Variation - The varying nature of the data. Its the degree of the spread of the data points from the central tendency.
The metrices that help to find the changes how much data is varying-
- Range
   The most simplest variation i.e.
   Top - Bottom 
   High - Low
   Range : Max - Min

- Variance -  Average Square of all the value that we have got from mean.

- Standard Deviation

Standard Variance and Standard Deviation - 

It is the standard distance between any of the given data and mean.

- **Population Standard Deviation Formula**:

*σ*=*N*∑(*X*−*μ*)2
Where *σ* is the population standard deviation, *X* represents each value in the dataset, *μ* is the                 mean of the dataset, and *N* is the total number of values.

- **Sample Standard Deviation Formula**:

*s*=*n*−1∑(*X*−*X*ˉ)2
Where *s* is the sample standard deviation, *X* represents each value in the dataset, *X* is the sample mean, and *n* is the number of values in the sample.

IMP- Standard deviation is dealing with the deviation that how much deviated we are from the mean.
          Variance is dealing with how different we are from the mean.

Example - Suppose you are given 500 rupee for the shopping and told you that your budget can go up to 100 rupee i.e. budget can fluctuate from 400 to 600.  So this is the variance about how much you can vary from the given datapoint (money). 
And if you purchase something of 570 rupee so you deviated 70 rupee from the actual money so this 70 rupee deviation is the standard deviation.

Z- Score - 
The distance of the data point from the mean in terms of standard deviation is Z- score.

Quartile IQR - 

Q1 = data frame [’Column Name’].quartile(0.25) —> Formula to find the Q1
—> Get the value of Q1
Q3 = data frame [’Same Column Name’].quartile(0.75) —> Formula to find the Q3

—> Get the value of Q3

Calculate the IQR-
*IQR = Q3 - Q1* 

Formula to find the Outliers  - 

*UL = Q3 + ( 1.5 * IQR )*

*LL = Q1 + ( 1.5 * IQR )*

 Note -  Any data points which is below the LL and above the UL are the outliers.
We can check the same using describe function :
describe()

# Format Sampling / Central Tendency

# 1- Random Sampling-

# We are taking 'Urban population (% of total population)' column to get the random sample.

# Format: ( We have taken country profile dataset)

country[['Urban population (% of total population)']].sample(10)

# 2 - Systematic Sampling :

# Format - df.iloc[: : n_components]

country.iloc[::5]

# Stats formula and steps :

Mean : 

np.mean(df['column_name’])  —> for numeric data only, continuous data

Median: 

np.median(df['column_name’]) —> for numeric data only, continuous data

Mode: 

df['column_name'].mode() —> It is advisable that we should find the mode for categorical data only. discrete data

- Now to find the range we need to find the min and max value as formula for range is :
range = max value - min value
- To find the max value of any column :
df[’column_name’].max()
- To find the min value of any column:
df[’column_name’].max()
- Range = df[’column_name’].max()  -  df[’column_name’].max()
- Standard Deviation :
std = df[’column_name’].std()
- Variance:
var = std(standard deviation )* * 2
- Now to find the first quantile from the given sample pf the column :
Q1 = df[’column name’].quantile(0.25)
- Now to find the last quantile from the given sample pf the column :
Q3 = df[’column name’].quantile(0.75)

# Now to find the outliers we have :

IQR = Q3 - Q1
LL = Q1 - 1.5 * IQR
UL = Q3 + 1.5 * IQR

# Important note = If our calculation for LL and UL exceed the minimum and maximum values of the data , the new UL and LL will be those max and min

# Z - Score :

To find the Z-Score of any particular column we need to first know the mean and std of the same column as:

Z_score = (data - mean) / std

** In case you have a datapoint at 20, and the given mean is 10, and std = 5.
Then If you want to find the distance between this data and given mean in terms of std deviation.
We can simply find the distance and divide it by the standard deviation to find the Z_score **
**z_score = (20-10)/5

# Inferential Statistics :

Consider that Walmart's Quality Control department wants to know how much of the company's product in its warehouse are defective. For this, the team can simply select a small sample of 1000 products instead of inspecting all the product int the warehouse ( which would be impossible to inspect). It can then find the defect rate (i.e. the proportion of defective products) for the sample, based on which it can further infer the defect rate for all the products in the warehouses.

This process of deriving insights or drawing inferences from sample data is called 'Inferential Statistics'. Situation like the one above arise all the time in the big companies like Amazon and Flipkart, among others.

Inferential Statistics is used in the industry in multiple ways like :

- Financial: Risk Management
- Marketing : Consumers Surveys
- Manufacturing : Quality Control
- Retail : Demand Forecasting

The main aim of Inferential Statistics is to calculate population mean using the sample mean. Many times we don't have enough time and resources to collect entire population data, so we take a large enough sample and infer the population mean from the sample mean.

- First, we need to make sure that we take a sample which is representative of the population otherwise our inference will be inaccurate. We have various sampling techniques to collect appropriate samples.
- Next we calculate the sample mean and infer the population mean from the sample mean.
- But the population mean will be not same as sample mean. So we represent:
    - `Population Mean = Sample Means +/- Margin of Error`.
- We can easily calculate the sample mean from the collected sample data but we need to understand how to find the margin of error.

# Random Variable -

Random variable are of two types :

1 - Discrete RV - They take a fixed set of possible outcomes. Each outcomes has an associated probability. EX : Number of heads in two tosses, The creditworthiness of a loan applicant, Marital Status, Gender etc. 

2 - Continuous RV - They can take any value within a range. Ex: Age of a person, Income of a person, Subscription of any platform like Netflix, Disney , Hot star etc.

# Probability -

Probability can be defined as the measure of certainty(or uncertainty) that a certain event or outcome will occur given a certain random process. It is represented numerically as a number between zero and one. The probabilities of zero and one both represent certainty.

**Probability measures the likelihood that an event will occur. Probability values have two properties:**

`They always lie in the range of 0 to 1.` The value is 0 when an event is impossible (for example, the probability of you being in India and America at the same time) and 1 when an event is sure to occur (for example, the probability of the sun rising in the East tomorrow).

`The sum of the probabilities of all outcomes of an experiment is always 1.` For instance, in a coin toss, there can be two outcomes: heads or tails. Each outcome has a probability of 0.5. Hence, the sum of the probabilities is 0.5 + 0.5 = 1.

# **Probability Terminologies -**

**Experiment** is a process or action that results in one of several possible outcomes. Examples include tossing a coin, rolling a die, or drawing a card from a deck.

**Random Experiment** is an experiment or process for which the outcome cannot be predicted with certainty. Each performance of the experiment is called a trial.

**Outcome** is a possible result of an experiment. For example, when rolling a six-sided dice, the possible outcomes are 1, 2, 3, 4, 5, and 6.

**Sample Space** is a set of all possible outcomes of an experiment. Tossing two coins : {HH, HT, TT, TH}.

**Event** An event is a subset of the sample space. It consists of one or more outcomes. For example, getting an even number when rolling a die is an event that includes the outcomes {2,4,6}.

**Favorable Outcome** is an outcome that satisfies the event of interest. For example, if the event is rolling a number greater than 4 on a die, the favorable outcomes are 5 and 6.

# Probability Distribution -

 A mathematical function that gives the probabilities of occurrence of different possible outcomes of an experiment. In the simple words, it lists out all possible outcomes in the sample space with their probabilities.

Probability Distribution is of two types :

- Discrete Probability Distribution
- Continuous Probability Distribution

# Discrete Probability Distribution -

A discrete probability distribution is a type of probability distribution that shows all possible values of a discrete random variable along with the associated probabilities. A discrete random variable is one that has a finite or countable number of possible outcomes.

Consider the roll of a fair six-sided die. The possible outcomes are `{1, 2, 3, 4, 5, 6}`, and each outcome has a probability of `1/6`.

**1. Bernoulli Distribution -**

The Bernoulli distribution is a discrete probability distribution for a random variable that can take on only two possible outcomes: success (1) and failure (0). The probability of success is denoted by 𝑝 and the probability of failure is 1−𝑝.
**Example:** A coin flip can be modeled by a Bernoulli distribution where the probability of getting heads(success) is p=0.5.

**2. Binomial Distribution -**

The binomial distribution is a discrete probability distribution that models the number of successes in a fixed number of independent Bernoulli trials. Each trial has the same probability of success 𝑝.
**Example:** If a fair coin is flipped 10 times, the probability of getting exactly 5 heads can be calculated using the binomial distribution with n=10 and 𝑝=0.5.

# Probability Mass Function -

The probability function for a discrete random variable is the ‘ Probability Mass Function’. It shows the exact probabilities for a particular value of the random variable.

 A probability mass function (PMF) is the probability function that defines the probability of  observing a particular value of a discrete random variable. For example, a PMF can be used to calculate the probability of rolling a three on a fair six-sided die.
For example, suppose that we flip a fair coin some number of times and count the number of heads. The probability mass function that describes the likelihood of each possible outcome (eg., 0 heads, 1 head, 2 heads, etc.) is called the binomial distribution. The parameters for the binomial distribution are:
• `n` for the number of trials (eg., n=10 if we flip a coin 10 times)
• `p` for the probability of success in each trial (probability of observing a particular outcome in each trial. In this example, p= 0.5 because the probability of observing heads on a fair coin flip is 0.5)

- • `n` for the number of trials (eg., n=10 if we flip a coin 10 times)
- • `p` for the probability of success in each trial (probability of observing a particular outcome in each trial. In this example, p= 0.5 because the probability of observing heads on a fair coin flip is 0.5)

---

If we flip a fair coin 10 times, we say that the number of observed heads follows a Binomial(n=10, p=0.5) distribution. The graph below shows the probability mass function for this experiment. The heights of the bars represent the probability of observing each possible outcome as calculated by the PMF.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/612f6771-8bf8-45f8-8937-3b4fbe35aea6/bf74b4f1-6b81-4785-933e-8ccb366916cf/image.png)

The binom.pmf() method from the scipy.stats library can be used to calculate the PMF of the binomial distribution at any value. This method takes 3 values:

- `x:` the value of interest
- `n:` the number of trials
- `p:` the probability of success

For example, suppose we flip a fair coin 10 times and count the number of heads. We can use the binom.pmf() function to calculate the probability of observing 6 heads as follows:

```
import scipy.stats as stats

#stats.binom.pmf(x, n, p)
stats.binom.pmf(6, 10, 0.5)
```

# **Central Limit Theorem -**

The Central Limit Theorem (CLT) is a fundamental concept in statistics and plays a crucial role in data science. It states that, regardless of the shape of the original population distribution, the sampling distribution of the sample mean will be approximately normally distributed for sufficiently `large sample sizes(n > 30)`.

**It says**:

1. Take any Data.
2. Make multiple samples with replacement from the dataset. Each sample size must be more than 30 (the bigger the sample size, the better).
3. Suppose we took 500 or 1000 samples from the data, now take means of all the various samples we have taken.
4. We get 500 or 1000 sample means. We plot the sample means and check the distribution of the sample means. This is also known as 'Sampling Distribution of Sample Mean'.
5. They will always follow Normal Distribution.

# **`Frequently used hypothesis tests`**:

**Z-Test**

- `Use When`: Comparing the mean of a sample to a known population mean when the population variance is known and the sample size is large (n > 30).
- `Example`: Testing if the average height of a sample of students is different from the known average height of the population.

**T-Test**

---

- `One-Sample T-Test`: Compare the sample mean to a known value.
- `Two-Sample T-Test`: Compare the means of two independent samples.
- `Paired T-Test`: Compare means from the same group at different times.
- `Use When`: The population variance is unknown and the sample size is small (n < 30).
- `Example`: Testing if the average test scores of two different classes are significantly different.

**ANOVA (Analysis of Variance)**

- `One-Way ANOVA`: Compare means of three or more independent groups.
- `Two-Way ANOVA`: Compare means with two independent variables.
- `Use When`: Comparing the means of three or more groups to see if at least one group mean is different.
- `Example`: Testing if different teaching methods result in different student performance.

**Chi-Square Test**

- `Chi-Square Goodness of Fit Test`: Determine if a sample matches a population.
- `Chi-Square Test of Independence`: Determine if two categorical variables are independent.
- `Use When`: Dealing with categorical data to test relationships between variables.
- `Example`: Testing if there is an association between gender and voting preference.

**`Other Tests`**:
**Mann-Whitney U Test**:

- `Use When`: Comparing differences between two independent groups when the data is not normally distributed.
- `Example`: Testing if the distribution of scores differs between two different teaching methods.

**Wilcoxon Signed-Rank Test**:

- `When to use`: Compare the distributions of two related groups (e.g., before and after a treatment).
- `Description`: Tests if the distributions of two related groups are significantly different.
- `Example`: Testing if there is a difference in performance before and after a training program.

**Kruskal-Wallis H Test**:

- `When to use`: To test if the distributions of multiple groups are significantly different or Comparing more than two independent groups when the data is not normally distributed.
- `Example`: Testing if there are differences in customer satisfaction scores across multiple stores.

**Shapiro-Wilk Test or D'Agostino's K^2 Test or Anderson-Darling Test**:

- `When to use`: Check if the data follows a normal distribution.
- `Description`: Tests if the data is normally distributed.

**Augmented Dickey-Fuller Test or Kwiatkowski-Phillips-Schmidt-Shin (KPSS) Test**:

- `When to use`: Check if a time series is stationary.
- `Description`: Tests if a time series is stationary.

# **Z-Test -**

A z-test is a statistical method used in hypothesis testing to determine if there is a significant difference between sample and population means, or between the means of two samples. It is particularly useful when the population standard deviation is known and the sample size is large (typically greater than 30).

`We have mainly two types of z-test:`

1. **One-Sample Z-Test:** Used to determine whether the mean of a single sample is different from a known population mean.
2. **Two-Sample Z-Test:** Used to compare the means of two independent samples to see if they are significantly different from each other.

**Assumptions of Z-Tests**

For a z-test to yield valid/correct results, these assumptions must be met:

1. **Normal Distribution:** The data should be approximately normally distributed. This assumption is satisfied with large sample sizes due to the central limit theorem.
2. **Known Population Standard Deviation:** The standard deviation of the population must be known. If it is unknown, using a `t-test` is more appropriate.
3. **Random Sampling:** The sample data should be randomly drawn from the population, ensuring that it is representative of the actual population data.
4. **Independence:** The samples must be independent of each other, particularly in two-sample z-tests.
5. **Continuous Data:** The z-test is applicable for continuous data, w

**One Sample Z-Test Examples-**

**Example statement 1 :** Jeep, a well-known car maker, claims that its car 'Compass' gives a mileage of at least 17 km/litre.

- `Null Hypothesis` : μ ≥ 17
- `Alternate Hypothesis` : μ < 17

```
from statsmodels.stats.weightstats import ztest
import numpy as np

mileages = list(np.random.randint(14, 19, size = 50))

# Perform one-sample Z-test
z_statistic, p_value = ztest(mileages, value=17)

# Interpret the results
if p_value < 0.05:
    print(f"Z-statistic: {z_statistic:.4f}, p-value: {p_value:.4f}")
    print("We have sufficient evidence to reject the null hypothesis.")
else:
    print(f"Z-statistic: {z_statistic:.4f}, p-value: {p_value:.4f}")
    print("We do not have sufficient evidence to reject the null hypothesis.")
```

**Example 2:** Google claims that its internet browser ‘Chrome’ is the best in the industry, as it has an optimum boot time of only 250 ms, with a standard deviation of 9 ms. Sam, a tech geek, wanted to test the claim of Google. So, he randomly collected boot time data of 165 devices of Chrome and got a sample mean of 247 ms.

- Ho: μ = 250, i.e., the mean boot time is 250 ms.
- Ha: μ ≠ 250, i.e., the mean boot time is not 250 ms.

```
from statsmodels.stats.weightstats import ztest
import numpy as np

boot_times = list(np.random.randint(180, 300, size = 165))  #generating a list of 165 random integers between 180 and 300

population_mean = 250
pop_std_dev = 9

standardized_boot_times = [(x - population_mean) / pop_std_dev for x in boot_times]

# Perform one-sample Z-test
z_statistic, p_value = ztest(standardized_boot_times, value=0)  #here value = 250 but after standardization we always write value = 0

# Interpret the results
if p_value < 0.05:
    print(f"Z-statistic: {z_statistic:.4f}, p-value: {p_value:.4f}")
    print("We have sufficient evidence to reject the null hypothesis.")
else:
    print(f"Z-statistic: {z_statistic:.4f}, p-value: {p_value:.4f}")
    print("We do not have sufficient evidence to reject the null hypothesis.")
```

**Two Sample Z-test Example -**

**Problem Statement**

A company wants to compare the average time spent on their website by users from two different countries, Country A and Country B. They have collected data from a sample of users from each country. The population standard deviations for the time spent on the website are known to be 5 minutes for Country A and 6 minutes for Country B. The company wants to determine if there is a significant difference in the average time spent on the website between the two countries.

**Hypothesis Statements:**

- Null Hypothesis (): There is no significant difference in the average time spent on the website between users from Country A and Country B. ()
    
    H0
    
    μA=μB
    
- Alternative Hypothesis (): There is a significant difference in the average time spent on the website between users from Country A and Country B. ()
    
    H1
    
    μA≠μB
    

```
import numpy as np
from statsmodels.stats.weightstats import ztest

# Sample data
country_A_times = np.random.normal(loc=30, scale=5, size=100)  # Mean 30 minutes, std dev 5
country_B_times = np.random.normal(loc=32, scale=6, size=100)  # Mean 32 minutes, std dev 6

# Perform two-sample Z-test
z_statistic, p_value = ztest(country_A_times, country_B_times, value=0)

# Interpret the results
alpha = 0.05   #represents significance level : 5%
if p_value < alpha:
    print(f"Z-statistic: {z_statistic:.4f}, p-value: {p_value:.4f}")
    print("We have sufficient evidence to reject the null hypothesis.")
    print("There is a significant difference in the average time spent on the website between the two countries.")
else:
    print(f"Z-statistic: {z_statistic:.4f}, p-value: {p_value:.4f}")
    print("We do not have sufficient evidence to reject the null hypothesis.")
    print("There is no significant difference in the average time spent on the website between the two countries.")
```

---

---

---

---

# **T-test -**

The t-distribution is kind of a normal distribution; it is also symmetric and single peaked but less concentrated around its peak. In layman’s terms, a t-distribution is shorter and flatter around the centre than a normal distribution. It is used to study the mean of a population that has a distribution fairly close to a normal distribution (but not an exact normal distribution).

**Two simple conditions to determine when to use the t-statistic are as follows:**

- The population standard deviation is unknown.
- The sample size is less than 30.

Even if one of them is applicable in a situation, you can comfortably go for a t-test. The formula to determine the t-statistic is:
`t = x–μ / s/√n`

**One Sample T-Test Examples-**

The company claims that their new algorithm can process a specific dataset in an average of 20 minutes, which is faster than the current average processing time of 22 minutes using the standard algorithm. To validate this claim, a data scientist decides to conduct a t-test. The data scientist collects a sample of processing times using the new algorithm. The sample consists of 10 processing times (in minutes):

Sample Data : 19,18,21,20,19,22,18,17,21,20

The data scientist wants to test if the new algorithm significantly reduces the processing time compared to the standard average of 22 minutes. The hypothesis for the t-test would be set up as follows:

- `Null Hypothesis (H₀)`: The mean processing time using the new algorithm is equal to or greater than 22 minutes. (μ≥22)
- `Alternative Hypothesis (H₁)`: The mean processing time using the new algorithm is less than 22 minutes. (μ<22)

```
from scipy.stats import ttest_1samp

global_average_score = 22
sample_scores = [19,18,21,20,19,22,18,17,21,20]

t_stat, p_value = ttest_1samp(sample_scores, global_average_score)
p_value
```

The result of the t-test indicates that there is significant evidence to conclude that the new algorithm reduces the processing time for processing the datasets compared to the standard processing time of 22 minutes. Therefore, we can confidently claim that the new algorithm is more efficient.

**Two Sample T-test Example -**

A two-sample t-test is often used to determine if there is a significant difference between the means of two groups. Let's consider a scenario where a company wants to test if a new training program improves employee productivity. The productivity scores (measured in units of work completed per day) of employees who underwent the training are compared to those who did not.

**Hypothesis**

- Null Hypothesis (): There is no difference in productivity between trained and untrained employees.
- Alternative Hypothesis (): There is a difference in productivity between trained and untrained employees.

```
import numpy as np
from scipy.stats import ttest_ind

# Generating synthetic productivity data for trained employees
np.random.seed(0)  # for reproducibility of the random values being generate by the following random.normal functions
trained_productivity = np.random.normal(loc=80, scale=10, size=40)  # Mean 80, std dev 10

# Generating synthetic productivity data for untrained employees
untrained_productivity = np.random.normal(loc=75, scale=10, size=40)  # Mean 75, std dev 10

# Performing a two-sample t-test on the productivity data
t_statistic, p_value = ttest_ind(trained_productivity, untrained_productivity, equal_var = False)

# Interpret the results
alpha = 0.05
if p_value < alpha:
    print(f"T-statistic: {t_statistic:.4f}, p-value: {p_value:.4f}")
    print("We have sufficient evidence to reject the null hypothesis.")
    print("There is a significant difference in productivity between trained and untrained employees.")
else:
    print(f"T-statistic: {t_statistic:.4f}, p-value: {p_value:.4f}")
    print("We do not have sufficient evidence to reject the null hypothesis.")
    print("There is no significant difference in productivity between trained and untrained employees.")
```

Example 2 - A dataset from a recent health survey that includes information on participants' gender (male or female) and their cholesterol levels (a quantitative variable). The data scientist wants to investigate whether there is a significant difference in the mean cholesterol levels between male and female participants.

```
import numpy as np
from scipy import stats

gender = np.array(["Male", "Female", "Female", "Male", "Female", "Male", "Male", 
                   "Female", "Male", "Female"])

cholesterol = np.array([200, 220, 210, 190, 205, 195, 180, 230, 175, 225])

# Since the gender array contains categorical data, we need to separate the cholesterol data by gender
male_cholesterol = cholesterol[gender == "Male"]
female_cholesterol = cholesterol[gender == "Female"]

# Perform the two-sample t-test
t_stat, p_value = stats.ttest_ind(male_cholesterol, female_cholesterol)

print(f"T-statistic: {t_stat}")
print(f"P-value: {p_value}")
```

T-statistic: -4.57495710997814
P-value: 0.0018139585097282133

The `ttest_ind` function is used to compare the means of two independent samples, which in this case are the cholesterol levels of males and females. The gender array is used to filter the cholesterol array into two groups: male cholesterol and female cholesterol.

Example 3-  A retail company wants to evaluate the effectiveness of two different marketing strategies on sales performance. They implement Strategy A in one region and Strategy B in another region. After a month, they collect sales data from both regions. The company wants to determine if there is a statistically significant difference in the average sales between the two regions.

**Hypothesis Statements:**

- Null Hypothesis (): There is no difference in the average sales between the two marketing strategies. ()
    
    H0
    
    μA=μB
    
- Alternative Hypothesis (): There is a difference in the average sales between the two marketing strategies. ()
    
    H1
    
    μA≠μB
    

```
import numpy as np
from scipy.stats import ttest_ind

# Sample data: sales in thousands of dollars
sales_strategy_A = np.random.normal(loc=100, scale=15, size=50)  # Mean 100, std dev 15
sales_strategy_B = np.random.normal(loc=110, scale=15, size=50)  # Mean 110, std dev 15

# Perform two-sample t-test
t_statistic, p_value = ttest_ind(sales_strategy_A, sales_strategy_B)

# Interpret the results
alpha = 0.05
if p_value < alpha:
    print(f"T-statistic: {t_statistic:.4f}, p-value: {p_value:.4f}")
    print("We have sufficient evidence to reject the null hypothesis.")
    print("There is a significant difference in average sales between the two marketing strategies.")
else:
    print(f"T-statistic: {t_statistic:.4f}, p-value: {p_value:.4f}")
    print("We do not have sufficient evidence to reject the null hypothesis.")
    print("There is no significant difference in average sales between the two marketing strategies.")
```

# **Chi-Squared Test -**

A Chi-Squared test is a statistical method used in hypothesis testing to determine if there is a significant difference between observed and expected frequencies in one or more categories. It is particularly useful for analyzing categorical data and is often employed to test relationships between categorical variables.

**Chi-squared test of independence**: This is used to determine whether or not there is a significant relationship between two nominal (categorical) variables.

---

**Problem Statement:**

A marketing team at a software company wants to determine if there is a relationship between the type of advertising medium (online, print, television) and software purchases. They collect data from a sample of customers, noting the advertising medium each customer was exposed to and whether they purchased the software.

**Hypotheses:**

- Null Hypothesis (): There is no association between the type of advertising medium and software purchases. The variables are independent.
    
    H0
    
- Alternative Hypothesis (): There is an association between the type of advertising medium and software purchases. The variables are not independent.
    
    H1
    

```
import numpy as np
from scipy.stats import chi2_contingency

# Observed frequency data in a contingency table
# Rows in the data array represent: Advertising Medium (Online, Print, Television)
# Columns in the data array represent: Purchase (Yes, No)
data = np.array([[30, 10],  # Online
                 [20, 20],  # Print
                 [50, 30]]) # Television

# Perform Chi-Square Test of Independence
chi2_stat, p_value, dof, expected = chi2_contingency(data)

# Interpret the results
alpha = 0.05
if p_value < alpha:
    print(f"Chi-Square Statistic: {chi2_stat:.4f}, p-value: {p_value:.4f}")
    print("We have sufficient evidence to reject the null hypothesis.")
    print("There is a significant association between the advertising medium and software purchases.")
else:
    print(f"Chi-Square Statistic: {chi2_stat:.4f}, p-value: {p_value:.4f}")
    print("We do not have sufficient evidence to reject the null hypothesis.")
    print("There is no significant association between the advertising medium and software purchases.")
```

**Problem Statement 2:** A restaurant chain wants to determine if there is an association between the type of cuisine offered (Italian, Chinese, Mexican) and customer satisfaction levels (satisfied, neutral, dissatisfied). They conduct a survey among customers across several locations to collect this data.

**Hypotheses:**

- Null Hypothesis (): There is no association between the type of cuisine and customer satisfaction levels. The variables are independent.
    
    H0
    
- Alternative Hypothesis (): There is an association between the type of cuisine and customer satisfaction levels. The variables are not independent.
    
    H1
    

```
import numpy as np
from scipy.stats import chi2_contingency

# Observed frequency data in a contingency table
# Rows: Type of Cuisine (Italian, Chinese, Mexican)
# Columns: Customer Satisfaction (Satisfied, Neutral, Dissatisfied)
data = np.array([[40, 30, 10],  # Italian
                 [35, 25, 20],  # Chinese
                 [25, 30, 15]]) # Mexican

# Perform Chi-Square Test of Independence
chi2_stat, p_value, dof, expected = chi2_contingency(data)

# Interpret the results
alpha = 0.05
if p_value < alpha:
    print(f"Chi-Square Statistic: {chi2_stat:.4f}, p-value: {p_value:.4f}")
    print("We have sufficient evidence to reject the null hypothesis.")
    print("There is a significant association between the type of cuisine and customer satisfaction levels.")
else:
    print(f"Chi-Square Statistic: {chi2_stat:.4f}, p-value: {p_value:.4f}")
    print("We do not have sufficient evidence to reject the null hypothesis.")
    print("There is no significant association between the type of cuisine and customer satisfaction levels.")
```

Finally, a Chi-Square test evaluates whether the observed contingency table is significantly different from the table that would be expected if there were no association between the variables.

# Stats library -

to create sample we use :

sample = filtered_df.sample(30% of the filtered df, random_state = 5)

- Label Encoder() -

- from sklearn.preprocessing import LabelEncoder
- le = LaabelEncoder
- df[’column_name’] = le.fit_transform(df[’column_name])

- If we have to check only one condition we will go with the ttest:

- from scipy import stats
- from scipy.stats import ttest_1samp
- asumed_mean = value
- (t_stat, p_value) = ttest_1samp(filtered_df[’column_name from which mean is taken’],  assumed_mean)

- If the condition is in proportion we will go with the z_test

from statsmodels.stats.proportion import proportions_ztest

we than need to find the :
- Total number of condition in the filtered_df under count variable
- Total number of observation in the filtered df nobs variable
- proportion value under p0 variable
Now perform the test:
- count = ?
- nobs = ?
- p0 = ?
(z_stat, p_value) = proportions_ztest(count = count , nobs = nobs, value = p0)

create the hypothesis and verify if it meet the condition now.

# To find the encoded value in LabelEncoder:

for i in data.columns:
    if data[i].dtype=='object':
       data[i]=le.fit_transform(data[i])

```
print(f'Column:{i}')
print('Original -> Encoded:')
for original_class,encoded_value in zip(le.classes_,le.transform(le.classes_)):
  print(f'{original_class}->{encoded_value}')
print()

```

Copy the code as it is to find the encoded values:
