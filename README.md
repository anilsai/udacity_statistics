# udacity_statistics




Time taken to read words
40
35
30
25
20
15
10
5
0
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24
Samples
Congruent Incongruent
P1: Testing the perpetual phenomenon
1) The dependent variable is the performance of participant. The independent variable is
the congruent and incongruent conditions.
2) Hypotheses:
One hypothesis we can use is: there is a difference between the time used to recognize
colors under congruent words condition and incongruent words condition, namely, the
Stroop Effect is in existence.
Specifically, here we referring to the population means of congruence words group and
incongruence words group - average times for the respective groups to recognize the colors.
By comparing these means directly, we’ll be able to tell whether there is a difference between
the the two groups’ color recognition times. However, it wouldn’t be possible to do the
experiment with all potential subjects in the world, so we need to work with the sample we
have on hand to make inference about the population means, i.e., to use the observation
means, sd and other statistics to infer about the population means. In this case, the
observation is the difference between the two groups’ times. With this new data, we can
construct new statistics such as means and standard errors.
To achieve this, We can use a two-sided paired student T-test to verify. This is because:
one, we need to address the uncertainty in sample standard error resulted from the unknown
population standard deviation; two, we are comparing the means of two groups that are
dependent; three, the same subject is involved under both conditions.
Below is the hypothesis to test:
H0: mu_diff = 0 (The real difference between group population means is zero)
HA: mu_diff != 0 (The real difference between group population means is not zero)
3) Measures of Central Tendency:
􀀀 Mean time taken to read congruent list = 14.051s
􀀀 Mean time taken to read incongruent list = 22.016s
Measures of Variability:
􀀀 Standard deviation of congruent list = 3.56
􀀀 Standard deviation of incongruent list = 4.80
4) Data Visualization:
Time Taken
This graph shows the time taken by each individual in reading words in congruent and
incongruent conditions. In each sample, we can observe that the time taken by the
participant in incongruent condition is greater than the time taken in congruent
condition.
The above graph indicates that the highest number of samples lie in the range 6-10.
This means the mode is in that range.
5) Results:
􀀀 a = 0.05
􀀀 Number of samples = 24
􀀀 Test = Paired-Sample t-test
􀀀 Direction = 2-tailed
􀀀 Degree of freedom(df) = 23
􀀀 T-statistic(t) = 8.024
􀀀 T-critical value(tcr) =±2.07
􀀀 P<.05
From the above results, we can observe that t > tcr. Hence, we can reject the null
hypotheses. These results helped me proving the hypotheses that the mean time taken
in congruent condition is less compared to the mean time taken in incongruent
condition. Also the t-statistic is greater compared to t-critical value.
6) References:
􀀀 https://en.wikipedia.org/wiki/Stroop_effect
􀀀 http://cognitivefun.net/test/2/
Sample difference Graph
12
10
8
6
4
2
0
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25
Sample Difference
Frequency
