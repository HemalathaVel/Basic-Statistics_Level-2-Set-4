# Basic-Statistics_Level-2-Set-4
**1.	Examine the following normal Quantile plots carefully. Which of these plots indicates that the data …
I.	Are nearly normal?
II.	Have a bimodal distribution? (One way to recognize a bimodal shape is a “gap” in the spacing of adjacent data values.)
III.	Are skewed (i.e. not symmetric)?
IV.	Have outliers on both sides of the center?**


![image](https://github.com/HemalathaVel/Basic-Statistics_Level-2-Set-4/assets/154992818/ba3220c8-ac42-45cd-a6d1-c6aabe098030)


Ans: 
I)	Are nearly normal?
Ans –> C  
II)	Have a bimodal distribution? (One way to recognize a binomial shape is a “gap” in the spacing of adjacent data values.)
Ans –> B and D
III)	Are skewed (i.e. not symmetric)?
Ans –> A, B and D 
IV)	Have outliers on both sides of the center? 
Ans –> A and B

**2.	For each of the following statements, indicate whether it is True/False. If false, explain why.**

**The manager of a warehouse monitors the volume of shipments made by the delivery team. The automated tracking system tracks every package as it moves through the facility. A sample of 25 packages is selected and weighed every day. Based on current contracts with customers, the weights should have μ = 22 lbs. and σ = 5 lbs.**
	**i)  Before using a normal model for the sampling distribution of the average package weights, the manager must confirm that weights of individual packages are normally distributed.**
**ii)  The standard error of the daily average SE (x ̅) = 1.**


  
  
  Ans:
i)	False:
The Central Limit Theorem (CLT) states that, regardless of the population distribution shape, the distribution of the sample mean will approach a normal distribution as the sample size increases.
For a sample size of 25 or more, the sampling distribution of the sample mean (average package weights) is approximately normally distributed due to the CLT, even if the individual package weights are not normally distributed.

ii)	True:
Standard Error (SE) = sample standard deviation / Square root of SE
                    = 5 / √25
                    = 1

**3.	Auditors at a small community bank randomly sample 100 withdrawal transactions made during the week at an ATM machine located near the bank’s main branch. Over the past 2 years, the average withdrawal amount has been $50 with a standard deviation of $40. Since audit investigations are typically expensive, the auditors decide to not initiate further investigations if the mean transaction amount of the sample is between $45 and $55. What is the probability that in any given week, there will be an investigation?
A.	1.25%
B.	2.5%
C.	10.55%
D.	21.1%
E.	50%**

Ans:  D
Standard Error (SE) = σ /√n
σ = Population standard deviation = $40
n = Sample size = 100
SE = 40/√100
SE = 4
Z-scores for the values $45 and $55 using the formula:
 Z = x - µ/SE
    For $45
 Z1 = 45 – 50 /4
    = –1.25
Z1 = 55 – 50 /4
   = 1.25
The probabilities corresponding to these z-scores.
From the z-table:
P (Z < – 1 .25) = 0.1056
P (Z < 1.25) = 0.8944
The probability that the sample mean is either less than $45 or greater than $55, we add these two probabilities:
P (Z < – 1.25 or Z > 1.25) = 0.1056 +(1 – 0.8944)
                           = 0.1056 +0.1056
                           = 0.2112
Converting this to a percentage:
0.2112 × 100 = 21.12%


**4.	The auditors from the above example would like to maintain the probability of investigation to 5%. Which of the following represents the minimum number transactions that they should sample if they do not want to change the thresholds of 45 and 55? Assume that the sample statistics remain unchanged.**
**A.	144
B.	150
C.	196
D.	250
E.	Not enough information**


Ans: P (Z < – 1.25 or Z > 1.25) = 0.2112 (sample size of 100)
Z-score corresponding to the desired probability of 5% is approximately 1.645.
Formula of Z-score:
Z = x - µ / SE
Solve for the sample size n using:
n = (z × σ/E)2
 Calculate the margin of error€ for the sample size of 100:
   E = z × SE
     = 1.645 × 4
     = 6.58
Formula for the sample size:
n = (1.645 × 40 / 6.58)2
  = 146.98

 

                      

**5.	An educational startup that helps MBA aspirants write their essays is targeting individuals who have taken GMAT in 2012 and have expressed interest in applying to FT top 20 b-schools. There are 40000 such individuals with an average GMAT score of 720 and a standard deviation of 120. The scores are distributed between 650 and 790 with a very long and thin tail towards the higher end resulting in substantial skewness. Which of the following is likely to be true for randomly chosen samples of aspirants?**

**A.	The standard deviation of the scores within any sample will be 120.
B.	The standard deviation of the mean of across several samples will be 120.
C.	The mean score in any sample will be 720.
D.	The average of the mean across several samples will be 720.
E.	The standard deviation of the mean across several samples will be 0.60**
 
  
  ANS:  E
Standard error = sigma / (n)^0.5
               = standard deviation / (sample size) ^ 0.5
               = 120 / (40000) ^0.5
               = 0.60























 
