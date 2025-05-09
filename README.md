The dataset contains of 768 people to study diabetes-related health stats and no null values. First, I picked a random sample of 25 people.
=>In this sample, the average glucose level was 116.64, and the highest was 183.
=>For the whole population, the average glucose was 120.89, and the highest was 199. So, the sample missed out some values.

Next, I looked at BMI.
=>The 98th percentile ( the top 2% of values) was 40.25 in the sample and 47.53 in the whole dataset. Same happened here sample missed out some values.

Next task bootstrapping, where I created 500 random samples (with 150 people each) to study blood pressure.
Found that:

=>The average blood pressure from bootstrapping was 69.18, very close to the population average of 69.11.
=>The standard deviation (how spread out the numbers are) was 19.07 in the bootstrap samples and 19.36 in the population.
=>The 98th percentile for blood pressure was 97.90 from bootstrapping and 99.32 in the full data.

Conclusion:So, even though the sample was small, bootstrapping helped get results that are very close to the real population values.
