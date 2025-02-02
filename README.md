# CCJS 621: General Linear Models in Criminal Justice Research

* Instructor: Robert Brame
* Course Meets in LeFrak 1222 on Monday evenings from 4:00-6:45pm.
* My office hours: Wednesdays 10-12 and by appointment; my office is 2139 LeFrak Hall. You are welcome to email me (from your University email account) at rbrame at umd.edu.
* Catalog Description: An in-depth exploration of applied linear regression analysis. Covers characteristics of estimates, such as unbiasedness and efficiency. Encourages fluency with the theoretical issues involved in the basic linear regression using simple algebra, familiarity with the general model using matrix algebra, and fluency with the computer application of multivariate regressions and the probit/logit models. Prerequisite: CCJS 620 or equivalent; please see me if you have any questions about your preparation for the class.
* Course-related policies: In all matters, the class will follow University guidance as outlined [here](https://gradschool.umd.edu/faculty-and-staff/course-related-policies).
* Course content: In addition to the textbooks (listed below), I will also assign some supplementary readings. Some of the work you will be doing will involve hand calculations on simple datasets and some will involve problems where you will need to rely on the computer. I will be posting relevant content for the course on this webpage throughout the semester so please bookmark the site and check it regularly.
* Accessibility accommodations: If you think you might need one or more academic accommodations, please contact the Accessibility and Disability Service Office ([link](https://ads.umd.edu)) for guidance and assistance.
* Statistical software: I will be using R in this course. You can obtain R for your computer at this [website](https://www.r-project.org) or you can use the R software that is installed on lab computers across campus. 
* Grades: there will be 4 take-home assignments throughout the semester. Each assignment will be worth 1/4 of your final grade and will be graded on a 100-point scale; each individual grade will be rounded to the nearest integer (so, for example, a 94.8 rounds up to 95 and a 94.3 rounds down to 94). At the end of the semester, I will add up your (rounded) grades on the 4 assignments and then I will divide the sum by 4 to get your final numeric grade which will also be rounded to the nearest integer. Letter grades will be assigned as follows: 98-100=A+, 93-97=A, 90-92=A-, 88-89=B+, 83-87=B, 80-82=B-, 78-79=C+, 73-77=C, 70-72=C-, 68-69=D+, 63-67=D, 60-62=D-, and all grades lower than 60=F.
* Assignment submission rules: assignments are due on ELMS at 11:59pm on the due date and must be submitted as a pdf file. If you submit your assignment in any other form than a pdf file, you will receive an automatic 10-point deduction.  It is your responsibility to make sure the pdf file you submit can be opened and read. File submissions that cannot be opened or read will receive a grade of 0. In the unlikely event that there is an ELMS or Canvas problem at the deadline time, you can submit your assignment to me by email (rbrame@umd.edu) but the time stamp of the email will be marked as the submission time. Such emails must originate from your UMD email account or they will not be accepted.
* Late submission of assignments: If you submit your assignment after the 11:59pm deadline, there will be a 5-point grade penalty for each hour the submission is late (so, for a submission arriving at midnight up through 12:59am, the penalty is 5 points; if the submission arrives at 1:00am up through 1:59am, the penalty is 10 points, etc.). If an emergency arises and you are unable to submit your assignment, you are expected to notify me no later than the time the assignment is due and to supply appropriate documentation to support your excuse. The documentation must demonstrate incapacity to work on the assignment for a substantial fraction of the time between when the assignment is posted and the time it is due. If the emergency is such that you are unable to notify me by the time the assignment is due, your excuse must also include documentation to justify the delay in notification. Once I have reviewed the documentation, I will make a judgment about whether an extension is warranted.
* Attendance expectations for classes: My expectation is that you will attend all of the class sessions. If you have to miss a class, I encourage you to work with other people in the class to get caught up on your notes and contact me if you need clarification.
* Academic integrity: the guiding principle in this class is that the work you submit should be your own work. This means you are not permitted to discuss assignment problems with other students, share R code to solve assignment problems with other students, or use artificial intelligence to obtain R code or to solve assignment problems. If credible evidence of a rule violation materializes, it will be reported to the Office of Student Conduct in accordance with the University's Academic Integrity Policy ([website](https://policies.umd.edu/academic-affairs/university-of-maryland-code-of-academic-integrity)). Please note that an Academic Integrity referral does *not* mean that you have been found responsible for a violation or that I have concluded you are responsible for a violation. It means that an issue of concern has been noted and that the Office of Student Conduct will examine it carefully. A determination of responsibility will only be reached after the Office of Student Conduct has completed its investigation with appropriate due process; as an instructor, my role in the process is a limited one. 

### Required Textbooks

* David Freedman (2009). *Statistical Models: Theory and Practice* (revised edition). New York: Cambridge University Press. This book can be freely read on the library's [website](https://usmai-umcp.primo.exlibrisgroup.com/discovery/fulldisplay?docid=alma9963824059708238&context=L&vid=01USMAI_UMCP:UMCP&lang=en&search_scope=DN_and_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,David%20freedman%20statistical%20models).
* Simon Sheather (2009). *A Modern Approach to Regression with R*. New York: Springer-Verlag. This book can be freely downloaded from the library's [website](https://usmai-umcp.primo.exlibrisgroup.com/discovery/fulldisplay?docid=alma9963930950608238&context=L&vid=01USMAI_UMCP:UMCP&lang=en&search_scope=DN_and_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,Simon%20sheather%20regression).
* David Weisburd and Chester Britt (2007). *Statistics in Criminal Justice* (3rd edition). New York: Springer-Verlag. This book is also available for free on the library's [website](https://usmai-umcp.primo.exlibrisgroup.com/discovery/fulldisplay?docid=alma9963921939908238&context=L&vid=01USMAI_UMCP:UMCP&lang=en&search_scope=DN_and_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,David%20weisburd%20Chester%20Britt%20statistics%20in%20criminal%20justice&offset=0). The most relevant chapters would be 14-18 and 20.

### Outline

The various topics I plan to discuss in this course are listed below in coverage order. The assignment due dates are:

* #1: distributed on 2/17; due on 2/24 at 11:59pm (ET)
* #2: distributed on 3/10; due on 3/24 at 11:59pm (ET)
* #3: distributed on 4/7; due on 4/14 at 11:59pm (ET)
* #4: distributed on 5/12; due on 5/19 at 11:59pm (ET)

#### Simple Linear Regression

*Note*: reading for this section is chapters 14, 15, and 20 of Weisburd/Britt, chapter 2 and section 5.2 of Freedman, and chapters 2-3 of Sheather; For topic 14, chapter 1 of Freedman is useful and I've provided links to supplementary readings for topics 12 and 13.

1. confidence interval for a mean
2. confidence interval for a median
3. linear correlation
4. scatterplots
5. confidence interval for a correlation
6. least squares
7. maximum likelihood
8. Gauss-Markov theorem (section 5.2 of Freedman)
9. linear regression with standardized variables
10. linear regression with unstandardized variables
11. linear regresssion with a categorical independent variable
12. measurement error; (Blalock et al., 1970; [link](https://www.jstor.org/stable/270784))
13. extrapolation (Manski, 1993; [link](https://www.jstor.org/stable/271005))
14. causal inference and omitted variables
15. residuals/prediction errors
16. heteroscedasticity
17. influential observations
18. functional form
19. nonlinear single independent variable regression
20. finite difference derivatives (difference quotients)
21. prediction interval
22. confidence interval for an expected value

#### Multiple regression

*Note*: reading for this section is chapters 16 and 17 of Weisburd/Britt, chapters 4 and 5 of Freedman, and chapters 5, 6, and 10 of Sheather; for topic 23, there will be parts of Freedman chapter 3 that are relevant and a supplementary reading is linked for topic 27. 

23. matrix operations
24. 2 continuous independent variables 
25. 1 continuous and 1 binary independent variable
26. interaction effects (moderation)
27. statistical mediation (MacKinnon et al., 2007; [link](https://pmc.ncbi.nlm.nih.gov/articles/PMC2819368/pdf/nihms173361.pdf))
28. F-tests and likelihood ratio tests
29. introduction to regression with hierarchical data (Sheather chapter 10 is important for this topic).

#### Binary outcomes

*Note*: relevant readings for this section are chapter 18 of Weisburd/Britt, chapter 7 of Freedman, and chapter 8 of Sheather; supplementary readings for topics 32 and 33 are linked.

30. linear probability model
31. logistic regression
32. confidence intervals for proportions (Brown et al., 2001; [link](https://projecteuclid.org/journals/statistical-science/volume-16/issue-2/Interval-Estimation-for-a-Binomial-Proportion/10.1214/ss/1009213286.full)).
33. introduction to Bayesian analysis of proportions (Agresti and Hitchcock, 2005; [link](https://link.springer.com/content/pdf/10.1007/s10260-005-0121-y.pdf)).

### Lesson 1 - Monday 1/27/25

* An estimator is a formula or way of calculating some scientifically interesting quantity.
* Estimators are used to calculate estimates (sometimes people say "estimand").
* Scientists must attend to the properties of the estimators they use for describing phenomena and developing inferences.
* When we conduct a statistical analysis we are usually doing one of the following things: (1) point estimation; (2) interval estimation; and/or (3) hypothesis testing.
* It is natural to be concerned with how accurately we are performing these tasks.
* To motivate this discussion, let's consider the case of a normally distributed random variable, *y*, for a large population.
* This generates the population distribution of y (mean of about 100 and a standard deviation of about 10):

```R
y <- rnorm(n=1000000,mean=100,sd=10)
mean(y)
sd(y)
hist(y)
```

* Here is our output:

```Rout
> y <- rnorm(n=1000000,mean=100,sd=10)
> mean(y)
[1] 100.0005
> sd(y)
[1] 10.00185
> hist(y)
> 
```

* Here is the population histogram:

<p align="center">
<img src="/gfiles/fig1.png" width="600px">
</p>

* So far, all we've done is consider the population.
* Now, let's draw a single sample, yss, of size 100 from the population -- with replacement.

```R
yss <- sample(y,size=100,replace=T)
```

* The y values for the single sample are included in the vector, *yss*.
* Now, let's suppose our objective is to estimate the *population mean* using the *sample* information.
* We need to choose an estimator to produce the estimate.
* An obvious choice for an estimator would be the *sample mean*: $\overline{y} = \frac{1}{n} \sum_{i=1}^n y_i$
* But another choice for an estimator could be the *sample median* or the middle score of the distribution.
* Let's calculate both quantities for our single sample:

```
mean(yss)
median(yss)
```

* Here is our output:

```Rout
> mean(yss)
[1] 99.91584
> median(yss)
[1] 99.46716
>
```

* Let's draw another sample and see what happens:

```R
yss <- sample(y,size=100,replace=T)
mean(yss)
median(yss)
```

* Here is our next output:

```Rout
> yss <- sample(y,size=100,replace=T)
> mean(yss)
[1] 101.0809
> median(yss)
[1] 100.2906
```

* In both samples the mean and median are close to the population mean
* In the first sample, the mean is closer; in the second sample the median is closer.
* How should we choose which estimator to use?
* To investigate this, let's draw repeated samples of size n = 100 from this population.

```R
ymean <- vector()
ymedian <- vector()

for(i in 1:1e5){
  ys <- sample(y,size=100,replace=T)
  ymean[i] <- mean(ys)
  ymedian[i] <- median(ys)
  }

mean(ymean)
mean(ymedian)
boxplot(ymean,ymedian,names=c("sample mean","sample median"))
```

* Here is our output:

```Rout
> ymean <- vector()
> ymedian <- vector()
> 
> for(i in 1:1e5){
+   ys <- sample(y,size=100,replace=T)
+   ymean[i] <- mean(ys)
+   ymedian[i] <- median(ys)
+   }
> 
> mean(ymean)
[1] 99.99852
> mean(ymedian)
[1] 99.9985
> boxplot(ymean,ymedian,names=c("sample mean","sample median"))
>
```

<p align="center">
<img src="/gfiles/fig2.png" width="600px">
</p>

* This repeated sampling exercise yields an approximation to the *sampling distribution* of the two sets of estimates.
* Both the sample mean and median seem to be *unbiased* (right on average) estimators of the population mean.
* But the sample median has greater dispersion than the sample mean -- it is less *efficient*.
* So, we would prefer the sample mean over the sample median on efficiency grounds
* We can confirm this by looking at the standard deviation of each distribution of sample means and sample medians.

```R
sd(ymean)
sd(ymedian)
```

* which gives the following output:

```Rout
> sd(ymean)
[1] 1.000298
> sd(ymedian)
[1] 1.243241
>
```

* Not by coincidence, the *mean squared error* for the two estimators gives us the same result (this is just the square of the standard deviations or the variance of the sampling distribution).

```R
dmean <- ymean-100
sum(dmean^2)/1e5
dmedian <- ymedian-100
sum(dmedian^2)/1e5
```

* Here is the output:

```Rout
> dmean <- ymean-100
> sum(dmean^2)/1e5
[1] 1.000589
> dmedian <- ymedian-100
> sum(dmedian^2)/1e5
[1] 1.545636
> 
```

* Now, let's think about a 90% confidence interval for the sample mean.
* We can calculate this interval for a single sample using the following approach:

```R
yss <- sample(y,size=100,replace=T)
mean(yss)
sd(yss)
se.meanyss <- sd(yss)/sqrt(100)
se.meanyss
p5 <- qnorm(p=0.05,mean=0,sd=1)
p5
p95 <- qnorm(p=0.95,mean=0,sd=1)
p95
lcl <- mean(yss)+p5*se.meanyss
lcl
ucl <- mean(yss)+p95*se.meanyss
ucl
```

* Here is our output:

```Rout
> yss <- sample(y,size=100,replace=T)
> mean(yss)
[1] 99.35032
> sd(yss)
[1] 10.99164
> se.meanyss <- sd(yss)/sqrt(100)
> se.meanyss
[1] 1.099164
> p5 <- qnorm(p=0.05,mean=0,sd=1)
> p5
[1] -1.644854
> p95 <- qnorm(p=0.95,mean=0,sd=1)
> p95
[1] 1.644854
> lcl <- mean(yss)+p5*se.meanyss
> lcl
[1] 97.54235
> ucl <- mean(yss)+p95*se.meanyss
> ucl
[1] 101.1583
>
```

* So, the calculated 90% confidence interval for this particular sample is [97.542,101.1583] -- which traps the true population value of 100.
* The creation of a valid 90% confidence interval means that our interval has *at least* a 90% chance of trapping the true population value of 100. What does this mean?
* Here is some code to check on whether it really works:

```R
ymean <- vector()
se.ymean <- vector()
lcl90 <- vector()
ucl90 <- vector()

for(i in 1:1e5){
  ys <- sample(y,size=100,replace=T)
  ymean[i] <- mean(ys)
  se.ymean[i] <- sd(ys)/sqrt(100)
  lcl90[i] <- ymean[i]+qnorm(p=0.05,mean=0,sd=1)*se.ymean[i]
  ucl90[i] <- ymean[i]+qnorm(p=0.95,mean=0,sd=1)*se.ymean[i]
  }

mean(ymean)
sd(ymean)
mean(se.ymean)
mean(ucl90-lcl90)
trap <- ifelse(lcl90<100 & ucl90>100,"hit","miss")
table(trap)
```

* Here is the output:
  
```Rout
> mean(ymean)
[1] 99.99113
> sd(ymean)
[1] 1.004598
> mean(se.ymean)
[1] 0.9969187
> mean(ucl90-lcl90)
[1] 3.279571
> trap <- ifelse(lcl90<100 & ucl90>100,"hit","miss")
> table(trap)
trap
  hit  miss 
89468 10532 
> 
```

* As you can see, it's pretty close but not quite right. It turns out this is *not* a valid 90% confidence interval.
* We should be using the t-distribution instead of the normal distribution with a sample size of 100.
* Let's try the t-distribution and see what we get:

```R
ymean <- vector()
se.ymean <- vector()
lcl90 <- vector()
ucl90 <- vector()

for(i in 1:1e5){
  ys <- sample(y,size=100,replace=T)
  ymean[i] <- mean(ys)
  se.ymean[i] <- sd(ys)/sqrt(100)
  lcl90[i] <- ymean[i]+qt(p=0.05,df=100-1)*se.ymean[i]
  ucl90[i] <- ymean[i]+qt(p=0.95,df=100-1)*se.ymean[i]
  }

mean(ymean)
mean(se.ymean)
mean(ucl90-lcl90)
trap <- ifelse(lcl90<100 & ucl90>100,"hit","miss")
table(trap)
```

* That's better!

```Rout
> ymean <- vector()
> se.ymean <- vector()
> lcl90 <- vector()
> ucl90 <- vector()
> 
> for(i in 1:1e5){
+   ys <- sample(y,size=100,replace=T)
+   ymean[i] <- mean(ys)
+   se.ymean[i] <- sd(ys)/sqrt(100)
+   lcl90[i] <- ymean[i]+qt(p=0.05,df=100-1)*se.ymean[i]
+   ucl90[i] <- ymean[i]+qt(p=0.95,df=100-1)*se.ymean[i]
+   }
> 
> mean(ymean)
[1] 99.99331
> mean(se.ymean)
[1] 0.9976558
> mean(ucl90-lcl90)
[1] 3.312998
> trap <- ifelse(lcl90<100 & ucl90>100,"hit","miss")
> table(trap)
trap
  hit  miss 
90076  9924 
> 
```

* Larry Wasserman's (2004:92) interpretation of a confidence interval: "Warning! There is much confusion about how to interpret a confidence interval. A confidence interval is not a probability statement about $\theta$ since $\theta$ is a fixed quantity, not a random variable. Some texts interpret confidence intervals as follows: if I repeat the experiment over and over, the interval will contain the parameter 95 percent of the time. This is correct but useless since we rarely repeat the same experiment over and over. A better interpretation is this: "On day 1, you collect data and construct a 95 percent confidence interval for a parameter $\theta_1$. On day 2, you collect new data and construct a 95% percent confidence interval for an unrelated parameter $\theta_2$. On day 3, you collect new data and construct a 95% confidence interval for an unrelated parameter $\theta_3$. You continue this way constructing confidence intervals  for a sequence of unrelated parameters, $\theta_1,\theta_2,\cdots$ Then 95 percent of your intervals will trap the true parameter value. There is no need to introduce the idea of repeating the same experiment over and over."

### Lesson 2 - Monday 2/3/25

* Before we turn to confidence intervals for medians, we will spend some time looking at how R works.
* You can use R interactively or in batch mode.
* Need to have a text editor such as Notepad (windows) or TextEdit (mac) that allows you to work with plain text.
* R Studio also has a text editor and many students enjoy using it.
* If you use R Studio, you still have to install R on your computer.
* Whenever you start a new R session, I recommend that you submit the following command:

```R
rm(list=ls())
```

* Note that this clears the memory so you don't carry over materials from prior R sessions.
* You can put comments in your R code/scripts by using the # symbol.
* R ignores everything after the # symbol -- everything that is on the same line, that is.
* Assignment operators

```R
# illustrates assignment
x <- 2
x
x=3
x
```

```Rout
> # illustrates assignment
> x <- 2
> x
[1] 2
> x=3
> x
[1] 3
> 
```

* Basic arithmetic

```R
x <- 2
y <- 3
x+y
x-y
x*y
y/x
ysq = y*y
ysq
sqrt(ysq)
xcu <- x^3
xcu
```

```Rout
> x <- 2
> y <- 3
> x+y
[1] 5
> x-y
[1] -1
> x*y
[1] 6
> y/x
[1] 1.5
> ysq = y*y
> ysq
[1] 9
> sqrt(ysq)
[1] 3
> xcu <- x^3
> xcu
[1] 8
>
```

* Logical operations

```R
x <- 7
y <- 5
x==y
x!=y
x>y
x<y
x>(y+2)
x>=(y+2)
```

```Rout
> x <- 7
> y <- 5
> x==y
[1] FALSE
> x!=y
[1] TRUE
> x>y
[1] TRUE
> x<y
[1] FALSE
> x>(y+2)
[1] FALSE
> x>=(y+2)
[1] TRUE
>
```

* Vectors

```R
x <- c(3,4,7,2,9,5)
x
y <- c(2,3,5,1,2,4)
y
x+y
```

```Rout
> x <- c(3,4,7,2,9,5)
> x
[1] 3 4 7 2 9 5
> y <- c(2,3,5,1,2,4)
> y
[1] 2 3 5 1 2 4
> x+y
[1]  5  7 12  3 11  9
> 
```

* Functions

```R
x <- c(3,4,7,2,9,5)
x
length(x)
sum(x)
y <- sum(x)
y
xbar <- mean(x)
xbar
var(x)
sd(x)
sd(x)/sqrt(length(x))
sum(x)/length(x)
sort(x,decreasing=T)
sort(x,decreasing=F)
median(x)
max(x)
min(x)
ifelse(mean(x)>median(x),"mean is bigger than median","mean is not bigger than median")
purplecow <- ifelse(median(x)>mean(x),"mediaan is bigger than mean","median is not bigger than mean")
purplecow
```

```Rout
> x <- c(3,4,7,2,9,5)
> x
[1] 3 4 7 2 9 5
> length(x)
[1] 6
> sum(x)
[1] 30
> y <- sum(x)
> y
[1] 30
> xbar <- mean(x)
> xbar
[1] 5
> var(x)
[1] 6.8
> sd(x)
[1] 2.607681
> sd(x)/sqrt(length(x))
[1] 1.064581
> sum(x)/length(x)
[1] 5
> sort(x,decreasing=T)
[1] 9 7 5 4 3 2
> sort(x,decreasing=F)
[1] 2 3 4 5 7 9
> median(x)
[1] 4.5
> max(x)
[1] 9
> min(x)
[1] 2
> ifelse(mean(x)>median(x),"mean is bigger than median","mean is not bigger than median")
[1] "mean is bigger than median"
> purplecow <- ifelse(median(x)>mean(x),"mediaan is bigger than mean","median is not bigger than mean")
> purplecow
[1] "median is not bigger than mean"
>
```

* We can also use familiar formulas from elementary statistics to make our own calculations:

```R
x <- c(13,17,12,16,19,11,9,14,18,22,7,17,14,19,16)
x
n <- length(x)
n
median(x)
sort(x)
sort(x)[8]
mean(x)
1/n*sum(x)
var(x)
1/(n-1)*sum((x-mean(x))^2)
sd(x)
sqrt(1/(n-1)*sum((x-mean(x))^2))
```

```Rout
> x <- c(13,17,12,16,19,11,9,14,18,22,7,17,14,19,16)
> x
 [1] 13 17 12 16 19 11  9 14 18 22  7 17 14 19 16
> n <- length(x)
> n
[1] 15
> median(x)
[1] 16
> sort(x)
 [1]  7  9 11 12 13 14 14 16 16 17 17 18 19 19 22
> sort(x)[8]
[1] 16
> mean(x)
[1] 14.93333
> 1/n*sum(x)
[1] 14.93333
> var(x)
[1] 16.49524
> 1/(n-1)*sum((x-mean(x))^2)
[1] 16.49524
> sd(x)
[1] 4.061433
> sqrt(1/(n-1)*sum((x-mean(x))^2))
[1] 4.061433
> 
```

* Here are 3 ways to generate a sequence of numbers:

```R
x <- seq(from=1,to=7,by=1)
x
y <- 1:7
y

z <- vector()
for(i in 1:7){
  z[i] <- i
  }
z
```

```Rout
> x <- seq(from=1,to=7,by=1)
> x
[1] 1 2 3 4 5 6 7
> y <- 1:7
> y
[1] 1 2 3 4 5 6 7
> 
> z <- vector()
> for(i in 1:7){
+   z[i] <- i
+   }
> z
[1] 1 2 3 4 5 6 7
>
```

* Here are the rounding, ceiling, and floor functions:

```R
x <- c(1.5,1.49)
rx <- round(x,0)
rx

y <- c(1.5,1.49)
ry <- floor(y)
ry

z <- c(1.5,1.49)
rz <- ceiling(z)
rz
```

```Rout
> x <- c(1.5,1.49)
> rx <- round(x,0)
> rx
[1] 2 1
> 
> y <- c(1.5,1.49)
> ry <- floor(y)
> ry
[1] 1 1
> 
> z <- c(1.5,1.49)
> rz <- ceiling(z)
> rz
[1] 2 2
>
```

* Now, we look at how to generate random numbers. Here are a few examples with uniform random numbers:

```R
### uniform distribution
u <- runif(n=7,min=0,max=1)
u

### uniform distribution of integers
i <- round(runif(n=7,min=0.5,max=7.5),0)
i

### uniform distribution of integers - version 2
i2 <- round(runif(n=1e7,min=0.5,max=7.5),0)
table(i2)
```

```Rout
> ### uniform distribution
> u <- runif(n=7,min=0,max=1)
> u
[1] 0.17758123 0.06742606 0.90219515 0.45684591 0.77407265
[6] 0.41772782 0.16073524
> 
> ### uniform distribution of integers
> i <- round(runif(n=7,min=0.5,max=7.5),0)
> i
[1] 7 2 3 6 4 1 7
>
> ### uniform distribution of integers - version 2
> i2 <- round(runif(n=1e7,min=0.5,max=7.5),0)
> table(i2)
i2
      1       2       3       4       5       6       7 
1428949 1427749 1429130 1428387 1428961 1429747 1427077 
> 
```

* We can also draw random numbers from a normal distribution. We can use the random numbers to draw a histogram.

```R
z <- rnorm(n=7,mean=0,sd=1)
z

z2 <- rnorm(n=1e7,mean=70,sd=10)
hist(z2)
```

```Rout
> z <- rnorm(n=7,mean=0,sd=1)
> z
[1] -0.8937032  0.6196616 -0.8823563  0.4166921 -0.7184740
[6]  0.3612151 -0.1511227
>
> z2 <- rnorm(n=1e7,mean=70,sd=10)
> hist(z2)
> 
```

<p align="center">
<img src="/gfiles/fig3.png" width="600px">
</p>
