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
4. confidence interval for a correlation
5. scatterplots
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
* First assignment will be distributed on Monday 2/17/25 and will be due on Monday 2/24/25.
* By now you should have downloaded R and begun reading Chapter 20 of Weisburd and Britt.

#### R Primer

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

* Vectors: we use the c() to create a vector; c stands for concatenation or combining elements into a vector.

```R
x <- c(-3,4,7,2,9,5)
x
y <- c(2,3,5,1,2,4)
y
x+y
sum(x)
sum(y)
```

```Rout
> x <- c(-3,4,7,2,9,5)
> x
[1] -3  4  7  2  9  5
> y <- c(2,3,5,1,2,4)
> y
[1] 2 3 5 1 2 4
> x+y
[1] -1  7 12  3 11  9
>
> sum(x)
[1] 24
> sum(y)
[1] 17
> 
```

* Built-in R Functions: we already used one above, the sum() function. Here it is again along with some others.

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
x
lx <- log(x)
lx
elx <- exp(lx)
elx
sum(x)
sum(lx)
sum(elx)
rank(x)
rank(lx)
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
> x
[1] 3 4 7 2 9 5
> lx <- log(x)
> lx
[1] 1.0986123 1.3862944 1.9459101 0.6931472 2.1972246
[6] 1.6094379
> elx <- exp(lx)
> elx
[1] 3 4 7 2 9 5
> sum(x)
[1] 30
> sum(lx)
[1] 8.930626
> sum(elx)
[1] 30
> rank(x)
[1] 2 3 5 1 6 4
> rank(lx)
[1] 2 3 5 1 6 4
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
# first way

x <- seq(from=1,to=7,by=1)
x

# second way

y <- 1:7
y

# third way

z <- vector()
for(i in 1:7){
  z[i] <- i
  }
z
```

```Rout
> # first way
> 
> x <- seq(from=1,to=7,by=1)
> x
[1] 1 2 3 4 5 6 7
> 
> # second way
> 
> y <- 1:7
> y
[1] 1 2 3 4 5 6 7
> 
> # third way
> 
> z <- vector()
> for(i in 1:7){
+   z[i] <- i
+   }
> z
[1] 1 2 3 4 5 6 7
> 
```

* We can use the rep() function to replicate or repeat numbers:

```R
rep(3,times=7)
rep(2,5)
```
```Rout
> rep(3,times=7)
[1] 3 3 3 3 3 3 3
> rep(2,5)
[1] 2 2 2 2 2
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
z1 <- rnorm(n=7,mean=0,sd=1)
z1

z2 <- rnorm(n=1e7,mean=70,sd=10)
hist(z2)
```

```Rout
> z1 <- rnorm(n=7,mean=0,sd=1)
> z1
[1]  0.3487839  2.4169589  0.5568956 -1.9129909  0.6130422
[6] -0.1482766  0.9415427
> 
> z2 <- rnorm(n=1e7,mean=70,sd=10)
> hist(z2)
> 
```

<p align="center">
<img src="/gfiles/fig3.png" width="600px">
</p>

* Last, we will consider the sample() function. We use this function to sample a list of integers from a larger list of integers.

```R
sample(1:5,size=3,replace=T)
```
```Rout
> sample(1:5,size=3,replace=T)
[1] 3 2 5
>
```

#### Topic 1: Confidence Interval for a Sample Mean

* Now, let's review the procedure for calculating a XX% confidence interval for a sample mean. In this case, we have a measure of the age at release from prison for a population of inmates returning to the community. Here is the population distribution:
  
```R
age <- c(rep(16,19000),rep(17,161000),rep(18,492000),rep(19,480000),
         rep(20,624000),rep(21,599000),rep(22,580000),rep(23,468000),
         rep(24,537000),rep(25,443000),rep(26,432000),rep(27,338000),
         rep(28,415000),rep(29,292000),rep(30,324000),rep(31,254000),
         rep(32,234000),rep(33,179000),rep(34,187000),rep(35,167000),
         rep(36,177000),rep(37,132000),rep(38,152000),rep(39,117000),
         rep(40,119000),rep(41,93000),rep(42,113000),rep(43,102000),
         rep(44,85000),rep(45,75000),rep(46,90000),rep(47,72000),
         rep(48,86000),rep(49,62000),rep(50,78000),rep(51,61000),
         rep(52,57000),rep(53,50000),rep(54,44000),rep(55,49000),
         rep(56,55000),rep(57,34000),rep(58,34000),rep(59,25000),
         rep(60,21000),rep(61,18000),rep(62,19000),rep(63,11000),
         rep(64,16000),rep(65,7000),rep(66,5000),rep(67,13000),
         rep(68,5000),rep(69,3000),rep(70,1000),rep(71,3000),
         rep(72,5000),rep(73,3000),rep(74,4000),rep(75,2000),
         rep(76,1000),rep(77,2000),rep(78,2000))
table(age)
mean(age)
median(age)
hist(age)
```

```Rout
> table(age)
age
    16     17     18     19     20     21     22     23 
 19000 161000 492000 480000 624000 599000 580000 468000 
    24     25     26     27     28     29     30     31 
537000 443000 432000 338000 415000 292000 324000 254000 
    32     33     34     35     36     37     38     39 
234000 179000 187000 167000 177000 132000 152000 117000 
    40     41     42     43     44     45     46     47 
119000  93000 113000 102000  85000  75000  90000  72000 
    48     49     50     51     52     53     54     55 
 86000  62000  78000  61000  57000  50000  44000  49000 
    56     57     58     59     60     61     62     63 
 55000  34000  34000  25000  21000  18000  19000  11000 
    64     65     66     67     68     69     70     71 
 16000   7000   5000  13000   5000   3000   1000   3000 
    72     73     74     75     76     77     78 
  5000   3000   4000   2000   1000   2000   2000 
> mean(age)
[1] 29.33287
> median(age)
[1] 26
> hist(age)
>
```
<p align="center">
<img src="/gfiles/fig4.png" width="600px">
</p>

* Based on these results, we see that the population distribution of age at release from prison is skewed so that cases at the lower end of the age scale are more prevalent than cases at the higher end of the age scale.
* When this happens, we expect the population mean to exceed the population median -- which is what we have.
* Now, let's draw a single simple random sample of 500 cases from this population.

```R
set.seed(14)
k <- sample(1:length(age),size=500,replace=T)
ss.age <- age[k]
hist(ss.age)
mean(ss.age)
median(ss.age)
```
```Rout
> set.seed(14)
> k <- sample(1:length(age),size=500,replace=T)
> ss.age <- age[k]
> hist(ss.age)
> mean(ss.age)
[1] 29.28
> median(ss.age)
[1] 26
> 
```
<p align="center">
<img src="/gfiles/fig5a.png" width="600px">
</p>

* Now, let's calculate a 88% confidence interval for the sample mean:

```R
# calculate estimate of the mean
xbar <- mean(ss.age)
xbar

# calculate the standard error
std.err <- sd(ss.age)/sqrt(500)
std.err

# identify the multipliers for the hypothesized sampling
# distribution of sample means

lcl.mult <- qt(p=0.06,df=500-1)
lcl.mult
ucl.mult <- qt(p=0.94,df=500-1)
ucl.mult

# calculate the lower confidence limit

xbar+lcl.mult*std.err

# calculate the upper confidence limit

xbar+ucl.mult*std.err
```
```Rout
> # calculate estimate of the mean
> xbar <- mean(ss.age)
> xbar
[1] 29.28
> 
> # calculate the standard error
> std.err <- sd(ss.age)/sqrt(500)
> std.err
[1] 0.4748285
> 
> # identify the multipliers for the hypothesized sampling
> # distribution of sample means
> 
> lcl.mult <- qt(p=0.06,df=500-1)
> lcl.mult
[1] -1.55744
> ucl.mult <- qt(p=0.94,df=500-1)
> ucl.mult
[1] 1.55744
> 
> # calculate the lower confidence limit
> 
> xbar+lcl.mult*std.err
[1] 28.54048
> 
> # calculate the upper confidence limit
> 
> xbar+ucl.mult*std.err
[1] 30.01952
> 
```

* Notice that in this particular sample, our *procedure* has *trapped* (covered) the true population parameter value -- 29.33287.
* What assurance do we have that this particular procedure traps the true population parameter value at the advertised coverage rate?

```R
lcl.mult <- qt(p=0.06,df=500-1)
lcl.mult
ucl.mult <- qt(p=0.94,df=500-1)
ucl.mult

xbarvec   <- vector()
stderrvec <- vector()
lclvec    <- vector()
uclvec    <- vector()

for(i in 1:1e6){
  s <- sample(1:length(age),size=500,replace=T)
  age.s <- age[s]
  xbarvec[i] <- mean(age.s)
  stderrvec[i] <- sd(age.s)/sqrt(500)
  lclvec[i] <- xbarvec[i]+lcl.mult*stderrvec[i]
  uclvec[i] <- xbarvec[i]+ucl.mult*stderrvec[i]
  }

mean(xbarvec)
sd(xbarvec)
mean(stderrvec)
trap <- ifelse(lclvec<mean(age) & uclvec>mean(age),"hit","miss")
table(trap)
hist(xbarvec)
```
```Rout
> lcl.mult <- qt(p=0.06,df=500-1)
> lcl.mult
[1] -1.55744
> ucl.mult <- qt(p=0.94,df=500-1)
> ucl.mult
[1] 1.55744
> 
> xbarvec   <- vector()
> stderrvec <- vector()
> lclvec    <- vector()
> uclvec    <- vector()
> 
> for(i in 1:1e6){
+   s <- sample(1:length(age),size=500,replace=T)
+   age.s <- age[s]
+   xbarvec[i] <- mean(age.s)
+   stderrvec[i] <- sd(age.s)/sqrt(500)
+   lclvec[i] <- xbarvec[i]+lcl.mult*stderrvec[i]
+   uclvec[i] <- xbarvec[i]+ucl.mult*stderrvec[i]
+   }
> 
> mean(xbarvec)
[1] 29.33304
> sd(xbarvec)
[1] 0.4740103
> mean(stderrvec)
[1] 0.4735767
> trap <- ifelse(lclvec<mean(age) & uclvec>mean(age),"hit","miss")
> table(trap)
trap
   hit   miss 
879535 120465 
> 
```
<p align="center">
<img src="/gfiles/fig6.png" width="600px">
</p>

* The average of the sample means is quite close to the true population mean (unbiased).
* The average standard error is quite close to the actual standard deviation of the sampling distribution (valid standard error).
* Note that the fraction of hits is approximately 88% which is equal to the coverage rate we were seeking (accurate coverage).
* Also note that the sampling distribution of sample means is approximately normal even though the original population distribution of ages at the time of release from prison was definitely not normal. This is a manifestation of the *central limit theorem*.
* Thus far, we have used analytic formulas for calculating the standard error and confidence interval.
* We now consider an alternative approach called the *bootstrap*.

```R
bootmean <- vector()

for(i in 1:1e6){
  b <- sample(1:500,size=500,replace=T)
  boot.age <- ss.age[b]
  bootmean[i] <- mean(boot.age)
  }

mean(bootmean)
sd(bootmean)
xbar+lcl.mult*sd(bootmean)
xbar+ucl.mult*sd(bootmean)
quantile(bootmean,0.06)
quantile(bootmean,0.94)
```
```Rout
> bootmean <- vector()
> 
> for(i in 1:1e6){
+   b <- sample(1:500,size=500,replace=T)
+   boot.age <- ss.age[b]
+   bootmean[i] <- mean(boot.age)
+   }
> 
> mean(bootmean)
[1] 29.28077
> sd(bootmean)
[1] 0.4742992
> xbar+lcl.mult*sd(bootmean)
[1] 28.54131
> xbar+ucl.mult*sd(bootmean)
[1] 30.01869
> quantile(bootmean,0.06)
   6% 
28.55 
> quantile(bootmean,0.94)
   94% 
30.024 
> 
```

#### Practice Problems (week 2)

* Suppose we obtain data from the local prison recording the length of time incarcerated (in years) for 300 people released from prison over a 3-month period. The data look like this:

```Rout
  0   1   2   3   4   5   7 
 67 110  68  39  10   5   1 
>
```

which can be converted into a dataset by:

```R
t <- c(rep(0,67),rep(1,110),rep(2,68),rep(3,39),rep(4,10),rep(5,5),7)
table(t)
```

Now, with this dataset in hand, calculate the mean number of years served for the 300 people and a 92% confidence interval using both the t-distribution and the bootstrap. Compare the results using the two methods. What conclusions can you draw based on the results you've observed?

* The distribution of time served in the first problem is skewed. Why can we use the t-distribution (which is symmetric) to develop a valid confidence interval for the mean of time served?
* Suppose I tell you that the population mean of time served is 1.61. Comment on whether your 92% confidence interval has successfully trapped the true population parameter value.
* *Note*: recommended reading for this week: Chapter 8.1 of Freedman (introduction to the bootstrap) and Chapter 10 of Weisburd and Britt (particularly the sections on pp. 224-226 and pp. 234-239).

### Lesson 3 - Monday 2/10/25

* Reminder: first assignment will be distributed next Monday (2/17/25).
* You will have 1 week to work on it.

#### Topic 1 Practice Problem

* Here is our dataset comprised of 300 people released from prison; the data measure time served in prison at the time of release:

```R
t <- c(rep(0,67),rep(1,110),rep(2,68),rep(3,39),rep(4,10),rep(5,5),7)
table(t)
```
```Rout
> t <- c(rep(0,67),rep(1,110),rep(2,68),rep(3,39),rep(4,10),rep(5,5),7)
> table(t)
t
  0   1   2   3   4   5   7 
 67 110  68  39  10   5   1 
> 
```

* We begin by setting a random number seed (for reproducibility).

```R
# set random number seed
set.seed(308)
```

* Next, we use analytical formulas to calculate the sample mean and the standard error of the sample mean:

```R
# calculate estimate of the mean
xbar <- mean(t)
xbar

# calculate the standard error
std.err <- sd(t)/sqrt(300)
std.err
```
```Rout
> # calculate estimate of the mean
> xbar <- mean(t)
> xbar
[1] 1.45
> 
> # calculate the standard error
> std.err <- sd(t)/sqrt(300)
> std.err
[1] 0.06973832
>
```

* Now, we need to obtain our *t*-values based on the 4th and 96th percentiles of the *t*-distribution with 300-1=299 degrees of freedom:

```R
# calculate 4th and 96th %iles of t-distribution
# with 300-1 df

lcl.mult <- qt(p=0.04,df=300-1)
lcl.mult
ucl.mult <- qt(p=0.96,df=300-1)
ucl.mult
```
```Rout
> # calculate 4th and 96th %iles of t-distribution
> # with 300-1 df
> 
> lcl.mult <- qt(p=0.04,df=300-1)
> lcl.mult
[1] -1.756656
> ucl.mult <- qt(p=0.96,df=300-1)
> ucl.mult
[1] 1.756656
>
```

* To calculate the confidence limits, we use the following code:

```R
# calculate confidence interval
xbar+lcl.mult*std.err
xbar+ucl.mult*std.err
```
```Rout
> # calculate confidence interval
> xbar+lcl.mult*std.err
[1] 1.327494
> xbar+ucl.mult*std.err
[1] 1.572506
>
```

* We can also use the bootstrap:

```R
# bootstrap

bootmean <- vector()

for(i in 1:1e6){
  b <- sample(1:300,size=300,replace=T)
  boot.years <- t[b]
  bootmean[i] <- mean(boot.years)
  }

mean(bootmean)
sd(bootmean)
xbar+lcl.mult*sd(bootmean)
xbar+ucl.mult*sd(bootmean)

# percentile bootstrap (first-order accurate)

quantile(bootmean,0.04)
quantile(bootmean,0.96)
```

* And, we can see that the bootstrap gives us a similar answer:

```Rout
> # bootstrap
> 
> bootmean <- vector()
> 
> for(i in 1:1e6){
+   b <- sample(1:300,size=300,replace=T)
+   boot.years <- t[b]
+   bootmean[i] <- mean(boot.years)
+   }
> 
> mean(bootmean)
[1] 1.450008
> sd(bootmean)
[1] 0.06961999
> xbar+lcl.mult*sd(bootmean)
[1] 1.327702
> xbar+ucl.mult*sd(bootmean)
[1] 1.572298
> 
> # percentile bootstrap (first-order accurate)
> 
> quantile(bootmean,0.04)
  4% 
1.33 
> quantile(bootmean,0.96)
     96% 
1.573333 
>
```

#### Topic 2: Confidence Intervals for Medians

* Now, I want to return to the issue of the sampling distribution of the sample median.
* I will also include the sample mean to reinforce what we covered for Topic 1.
* Suppose we have the following large population of risk assessment scores:

```R
# set random number seed

set.seed(314)

# specify the population

yp  <- abs(rnorm(n=1e6,mean=0,sd=2))
mny <- mean(yp)
mny
mdy <- median(yp)
mdy
hist(yp)
```
```Rout
> # set random number seed
> 
> set.seed(314)
> 
> # specify the population
> 
> yp  <- abs(rnorm(n=1e6,mean=0,sd=2))
> mny <- mean(yp)
> mny
[1] 1.596291
> mdy <- median(yp)
> mdy
[1] 1.349637
```

* Here is the population histogram:

<p align="center">
<img src="/gfiles/fig7.png" width="600px">
</p>

* Suppose we repeatedly sample from this population with a sample size of N=483.
* Also suppose we have been asked to study the 89% confidence interval coverage for both the sample mean and median.
* For the sample mean, we will need to get the multipliers associated with the 5.5th and 94.5th percentiles of the *t*-distribution:

```R
# t-multipliers for 89% confidence interval
# with df=483-1 

lcl.mult <- qt(p=0.055,df=483-1)
lcl.mult
ucl.mult <- qt(p=0.945,df=483-1)
ucl.mult
```
```Rout
> # t-multipliers for 89% confidence interval
> # with df=483-1 
> 
> lcl.mult <- qt(p=0.055,df=483-1)
> lcl.mult
[1] -1.601145
> ucl.mult <- qt(p=0.945,df=483-1)
> ucl.mult
[1] 1.601145
>
```

* For the sample median, we cannot invoke the *t*-distribution because the central limit theorem does not apply to the sampling distribution of the sample median.
* Instead we will have to use the bootstrap.
* But we can verify that the bootstrap works as intended for this problem.
* Note that this code will take a long time to run.

```R
# draw repeated samples from the population

xbar      <- vector()
medn      <- vector()
lclmean   <- vector()
uclmean   <- vector()
lclmedian <- vector()
uclmedian <- vector()

for(i in 1:1e4){
  s <- sample(1:1e6,size=483,replace=T)
  ys <- yp[s]

  # calculate mean and median for each sample

  xbar[i] <- mean(ys)
  medn[i] <- median(ys)

  # calculate the standard error of the mean

  std.err <- sd(ys)/sqrt(483)

  # calculate confidence interval for the mean

  lclmean[i] <- mean(ys)+lcl.mult*std.err
  uclmean[i] <- mean(ys)+ucl.mult*std.err

  # bootstrap

  bootmedian <- vector()

  for(j in 1:3e3){
    b <- sample(1:483,size=483,replace=T)
    boot.ys <- ys[b]
    bootmedian[j] <- median(boot.ys)
    }

  lclmedian[i] <- quantile(bootmedian,0.055)
  uclmedian[i] <- quantile(bootmedian,0.945)
  }

mean(ifelse(lclmean<mny & uclmean>mny,1,0))
mean(ifelse(lclmedian<mdy & uclmedian>mdy,1,0))
```

* Here are the results:

```Rout
> # set random number seed
> 
> set.seed(314)
> 
> # specify the population
> 
> yp  <- abs(rnorm(n=1e6,mean=0,sd=2))
> mny <- mean(yp)
> mny
[1] 1.596291
> mdy <- median(yp)
> mdy
[1] 1.349637
> hist(yp)
> 
> 
> # t-multipliers for 89% confidence interval
> # with df=483-1 
> 
> lcl.mult <- qt(p=0.055,df=483-1)
> lcl.mult
[1] -1.601145
> ucl.mult <- qt(p=0.945,df=483-1)
> ucl.mult
[1] 1.601145
> 
>  
> 
> # draw repeated samples from the population
> 
> xbar      <- vector()
> medn      <- vector()
> lclmean   <- vector()
> uclmean   <- vector()
> lclmedian <- vector()
> uclmedian <- vector()
> 
> for(i in 1:1e4){
+   s <- sample(1:1e6,size=483,replace=T)
+   ys <- yp[s]
+ 
+   # calculate mean and median for each sample
+ 
+   xbar[i] <- mean(ys)
+   medn[i] <- median(ys)
+ 
+   # calculate the standard error of the mean
+ 
+   std.err <- sd(ys)/sqrt(483)
+ 
+   # calculate confidence interval for the mean
+ 
+   lclmean[i] <- mean(ys)+lcl.mult*std.err
+   uclmean[i] <- mean(ys)+ucl.mult*std.err
+ 
+   # bootstrap
+ 
+   bootmedian <- vector()
+ 
+   for(j in 1:3e3){
+     b <- sample(1:483,size=483,replace=T)
+     boot.ys <- ys[b]
+     bootmedian[j] <- median(boot.ys)
+     }
+ 
+   lclmedian[i] <- quantile(bootmedian,0.055)
+   uclmedian[i] <- quantile(bootmedian,0.945)
+   }
> 
> mean(ifelse(lclmean<mny & uclmean>mny,1,0))
[1] 0.8849
> mean(ifelse(lclmedian<mdy & uclmedian>mdy,1,0))
[1] 0.8893
>
```

* As we can see, our approach to creating the confidence interval for the sample mean (using the *t*-distribution) and the sample median (using the bootstrap) yielded very close to the expected 89% coverage rates.
* So, this is what is called a Monte Carlo simulation study to examine the repeated sampling performance of the two estimators.
* Let's now consider what we get for the 2 confidence intervals for the last (10,000th) sample we drew from the population.
* This would be the process we would follow in the more conventional case where we would only draw a single sample.
* Here is our R code:

```R
# calculate 89% confidence interval for median
# in the 10,000th sample that we drew

hist(ys)
mean(ys)
median(ys)

# calculate the standard error of the mean

std.err <- sd(ys)/sqrt(483)

# calculate confidence interval for the mean

mean(ys)+lcl.mult*std.err
mean(ys)+ucl.mult*std.err

bootmedian.ss <- vector()

for(j in 1:3e3){
  b <- sample(1:483,size=483,replace=T)
  boot.ys <- ys[b]
  bootmedian.ss[j] <- median(boot.ys)
  }

quantile(bootmedian.ss,0.055)
quantile(bootmedian.ss,0.945)
```

* And here is our output:
  
```Rout
> # calculate 89% confidence interval for median
> # in the 10,000th sample that we drew
> 
> hist(ys)
> mean(ys)
[1] 1.612869
> median(ys)
[1] 1.297095
> 
> # calculate the standard error of the mean
> 
> std.err <- sd(ys)/sqrt(483)
> 
> # calculate confidence interval for the mean
> 
> mean(ys)+lcl.mult*std.err
[1] 1.523321
> mean(ys)+ucl.mult*std.err
[1] 1.702417
> 
> bootmedian.ss <- vector()
> 
> for(j in 1:3e3){
+   b <- sample(1:483,size=483,replace=T)
+   boot.ys <- ys[b]
+   bootmedian.ss[j] <- median(boot.ys)
+   }
> 
> quantile(bootmedian.ss,0.055)
    5.5% 
1.187871 
> quantile(bootmedian.ss,0.945)
   94.5% 
1.435155 
>
```

<p align="center">
<img src="/gfiles/fig8.png" width="500px">
</p>

* Notice that both of the estimated 89% confidence intervals (one for the mean, one for the median) include or *trap* the true population parameter values.
* Our simulation study relied on drawing 10,000 samples and we now know that we have about an 89% chance of drawing a sample whose confidence interval includes the true population parameter value.
* This underscores the fact that the population parameter is fixed while the confidence interval bounds vary from sample to sample (based on sampling error).
* This concludes our discussion of topics 1 and 2.

#### Topic 3: Linear Correlation

* Relevant reading: chapters 6 (review) and 14 of Weisburd and Britt.
* The relationship between 2 interval level scales is often referred to as a linear correlation.
* A linear correlation is a measure of association (strength of relationship).
* Commonly used measure: Pearson's Correlation Coefficient
* Normalized to lie on scale from -1 (perfect negative relationship) to 0 (no relationship) to +1 (perfect positive relationship).
* Just like a sample mean or sample median varies from sample to sample, so too does a correlation vary from sample to sample.
* A problem that arises is that a correlation is constrained to vary within a range (-1,1).
* This means that a correlation coefficient *cannot* have a normal sampling distribution.
* And this means that the central limit theorem is not applicable to the correlation coefficient.
* Let's begin by creating a sample dataset (N=1250) and calculate the correlation (using both a formula and the R cor() function).

```R
library(MASS)

# set random number seed for reproducibility

set.seed(231)

# create a sample data set

N <- 1250
V <- mvrnorm(n=N,mu=c(0,0),Sigma=matrix(c(1,0.07,0.07,1),2,2))
x <- V[,1]
y <- V[,2]

# numerator of correlation coefficient formula

num <- sum((x-mean(x))*(y-mean(y)))

# denominator of correlation coefficient formula

den <- sqrt(sum((x-mean(x))^2))*sqrt(sum((y-mean(y))^2))

# correlation coefficient estimate

num/den

# R function

cor(x,y)
```

* Here is our output:

```Rout
> library(MASS)
> 
> # set random number seed for reproducibility
> 
> set.seed(231)
> 
> # create a sample data set
> 
> N <- 1250
> V <- mvrnorm(n=N,mu=c(0,0),Sigma=matrix(c(1,0.07,0.07,1),2,2))
> x <- V[,1]
> y <- V[,2]
> 
> # numerator of correlation coefficient formula
> 
> num <- sum((x-mean(x))*(y-mean(y)))
> 
> # denominator of correlation coefficient formula
> 
> den <- sqrt(sum((x-mean(x))^2))*sqrt(sum((y-mean(y))^2))
> 
> # correlation coefficient estimate
> 
> num/den
[1] 0.08560983
> 
> # R function
> 
> cor(x,y)
[1] 0.08560983
>
```

#### Topic 4: Confidence Interval for a Correlation

* Note that the population correlation coefficient is +0.07 while the correlation coefficient in our sample of N=1250 is about 0.086.
* Weisburd and Britt's chapter 14 gives a scale for interpreting the magnitude of a correlation coefficient on page 390.
* The difference between the population and sample correlations is due to sampling error.
* Up to this point, we have engaged with 2 of the major functions of statistical science: (1) point estimation; and (2) interval estimation.
* We now add a third function to this list: hypothesis testing.
* Suppose we wish to test the hypothesis that the population correlation coefficient is equal to zero (a hypothesis we already know is false because I already told you that the population correlation is equal to 0.07).
* In the real world, however, we don't know what the population parameter value is so a hypothesis test would be useful.
* To test a hypothesis, we have to consider that there are 2 types of errors: Type I (alpha) and Type 2 (beta) errors.
* A Type 1 error occurs when we reject a hypothesis that is true.
* A Type 2 error occurs when we fail to reject a hypothesis that is false.
* We can control the chance of making a Type 2 error by adjusting our sample size (holding everything else constant).
* When we test a hypothesis, we have to establish a decision rule.
* Normally, the decision rule is based on a *p*-value so we can control the chance of making a Type 1 error.
* If Ho is the hypothesis (usually called the *null hypothesis*) to be tested: Wasserman (2004) states that "Informally, the p-value is a measure of the evidence against Ho: the smaller the p-value, the stronger the evidence against Ho" (p. 156).
* Wasserman also offers a warning: "A large p-value is not strong evidence in favor of Ho" (p. 157).
* More formally, the p-value is p(get a result at least as extreme as the one we got in our sample | Ho is true).
* So, a p-value is a probability.
* Often, social scientists will reject Ho is the p-value, p, is less than 0.05.
* This is an arbitrary cutoff but one that is nonetheless often used.
* If we reject Ho when p ≤ 0.05, we recognize that there is a 5% (small) chance of making a Type 1 error (rejecting Ho when Ho is true).
* A p-value decision rule for rejecting a hypothesis should be stated in *advance*.
* It is improper to look at your data first and then make a decision rule based on the results you get.
* Define a critical region for the test statistic; if the test statistic falls in the critical region, we decide to reject Ho.
* Here is our R code:

```R
library(MASS)

# set random number seed

set.seed(231)

# create a sample data set

N <- 1250
V <- mvrnorm(n=N,mu=c(0,0),Sigma=matrix(c(1,0.07,0.07,1),2,2))
x <- V[,1]
y <- V[,2]

# numerator of correlation coefficient formula

num <- sum((x-mean(x))*(y-mean(y)))

# denominator of correlation coefficient formula

den <- sqrt(sum((x-mean(x))^2))*sqrt(sum((y-mean(y))^2))

# correlation coefficient estimate

num/den

# R function

cor(x,y)

# statistical inference
# permutation test p-value testing
# test hypothesis that true correlation coefficient = 0
# alternative hypothesis is that true correlation coefficient
# is not equal to zero

pvec <- vector()

for(i in 1:1e5){
  xs <- sample(x,replace=F)
  pvec[i] <- cor(xs,y)
  }

# define the critical region
# 0.05 significance level, two-tailed test

quantile(pvec,0.025)
quantile(pvec,0.975)

# create histogram of the permutation distribution
# of correlation coefficients. how unusual would it
# be to get a correlation as big as the one we got
# if we were just calculating correlations on randomly
# shuffled datasets?

hist(pvec)
abline(v=quantile(pvec,0.025),lty=2,lwd=2,col="blue")
abline(v=quantile(pvec,0.975),lty=2,lwd=2,col="blue")
abline(v=cor(x,y),lty=2,lwd=2,col="darkred")
```

* And here are our results:

```Rout
> # statistical inference
> # permutation test p-value testing
> # test hypothesis that true correlation coefficient = 0
> # alternative hypothesis is that true correlation coefficient
> # is not equal to zero
> 
> pvec <- vector()
> 
> for(i in 1:1e5){
+   xs <- sample(x,replace=F)
+   pvec[i] <- cor(xs,y)
+   }
> 
> # define the critical region
> # 0.05 significance level, two-tailed test
> 
> quantile(pvec,0.025)
       2.5% 
-0.05532854 
> quantile(pvec,0.975)
     97.5% 
0.05540046 
> 
> # create histogram of the permutation distribution
> # of correlation coefficients. how unusual would it
> # be to get a correlation as big as the one we got
> # if we were just calculating correlations on randomly
> # shuffled datasets?
> 
> hist(pvec)
> abline(v=quantile(pvec,0.025),lty=2,lwd=2,col="blue")
> abline(v=quantile(pvec,0.975),lty=2,lwd=2,col="blue")
> abline(v=cor(x,y),lty=2,lwd=2,col="darkred")
>
```

<p align="center">
<img src="/gfiles/fig9.png" width="500px">
</p>

* Since the observed sample correlation is in the critical region, we reject the hypothesis that the population correlation is equal to zero
* We can also address this issue using the bootstrap:

```R
# statistical inference using bootstrap
# yields a confidence interval

bvec <- vector()

for(i in 1:1e6){
  b <- sample(1:1250,size=1250,replace=T)
  bvec[i] <- cor(x[b],y[b])
  }

quantile(bvec,0.025)
quantile(bvec,0.975)

# generate histogram of bvec
# gives us the expected sampling
# distribution of bootstrapped correlations
# 

hist(bvec)
abline(v=quantile(bvec,0.025),lty=2,lwd=2,col="darkred")
abline(v=quantile(bvec,0.975),lty=2,lwd=2,col="darkred")
```

* Here is our output:

```Rout
> # statistical inference using bootstrap
> # yields a confidence interval
> 
> bvec <- vector()
> 
> for(i in 1:1e6){
+   b <- sample(1:1250,size=1250,replace=T)
+   bvec[i] <- cor(x[b],y[b])
+   }
> 
> quantile(bvec,0.025)
      2.5% 
0.03339516 
> quantile(bvec,0.975)
    97.5% 
0.1372181 
> 
```

* Since this is a 95% confidence interval, we have a two-tailed test of the hypothesis that the population correlation coefficient is equal to zero.
* The confidence interval does not include zero, so we reject Ho.
* R also has a procedure for calculating the significance test and confidence interval:

```R
# statistical inference using cor.test
# relies on normality assumption

cor.test(x,y)
```

which gives the following output:

```Rout
> cor.test(x,y)

	Pearson's product-moment correlation

data:  x and y
t = 3.0355, df = 1248, p-value = 0.002451
alternative hypothesis: true correlation is not equal to 0
95 percent confidence interval:
 0.03030782 0.14038932
sample estimates:
       cor 
0.08560983 
```

* Notice that the confidence interval is similar but not identical to bootstrap confidence interval.
* Correlations do not have a normal sampling distribution (see Weisburd and Britt, pp. 618-619).
* Weisburd and Britt (page 409) provide the formula for the *t*-statistic:
* The confidence interval is described in Weisburd and Britt on pp. 618-620.
* Note that this is an approximate formula; there are several of these formulas in the literature.
* The one in your book is a reasonable approximation.
* It gives us a result that is close to but not exactly the same as the cor.test() procedure.
* The substantive result is in agreement with what we get from cor.test() and the bootstrap.

#### Practice Problems (week 3)

1. Consider the following sample of 78 persons drawn from a population of persons arrested within the past year in a large city. For each person in the sample, we have an offense gravity score, *ys* (higher scores correspond to more serious offenses).

```R
set.seed(387)
ys  <- abs(rnorm(n=78,mean=0,sd=1.4))
hist(ys)
```

Based on this sample, you are to:

* calculate the sample mean
* calculate the standard error of the sample mean
* calculate the sample median
* use the *t*-distribution to calculate a 93% confidence interval for the population mean
* use the bootstrap to calculate a 93% confidence interval for the population mean
* use the bootstrap to calculate a 91% confidence interval for the population median
* use the bootstrap to calculate a 87% confidence interval for the population median
* choose one of the confidence intervals you calculated above and provide a written interpretation of that interval.

2. Suppose we have a sample of 88 cities. For each of the cities, the unemployment rate (u) and the crime rate (c) have been measured and expressed in z-score terms (i.e., each variable has been normalized to have a mean of 0 and a standard deviation of 1). The population correlation is 0.032. Here is the dataset:

```R
library(MASS)
set.seed(55)
N <- 88
V <- mvrnorm(n=N,mu=c(0,0),Sigma=matrix(c(1,0.032,0.032,1),2,2))
u <- V[,1]
c <- V[,2]
```

* calculate the Pearson correlation between *u* and *c*, using either the textbook formula or the formula used in class.
* use the cor() function to calculate the Pearson correlation and verify that you get the same answer
* conduct a permutation test to determine whether the hypothesis that the population correlation is equal to zero (Ho) should be rejected.
* use the bootstrap to calculate a 93% confidence interval for the correlation coefficient.
* determine whether the hypothesis that the population correlation coefficient is equal to zero should be rejected based on the confidence interval.
* use the cor.test() function to determine whether the hypothesis that the population correlation coefficient is equal to zero should be rejected.
* since you know the population correlation coefficient, determine whether the 93% confidence interval actually trapped the true population value.
* is Ho true or false?; Considering your hypothesis tests, which ones led you to the correct decision?; which ones missed the mark?

3. Let's say we have a large population of persons released from prison. Each person has a number of years of formal education. The mean of that population distribution is 10.5 years. The population years of education variable is specified below:
   
```R
set.seed (78)
yp <- rnorm(n=1e6,mean=10.5,sd=2)
```
With this population in hand, conduct a Monte Carlo simulation study where you examine the performance of a 92% confidence interval for the population mean procedure based on the t-distribution. For your simulation study, you should draw 100,000 (1e5) samples of size N = 38 and you should calculate the coverage rate for your confidence interval procedure.


### Lesson 4: Monday 2/17/25

* First assignment will be distributed today. It will be due on 2/24/25.
* In today's class we explore the use of scatterplots and regression lines.

#### Lesson 3 Practice Problems

1. Here is the histogram:

<p align="center">
<img src="/gfiles/fig9x.png" width="500px">
</p>

* calculate the sample mean

```Rout
> mean(ys)
[1] 1.074752
> 1/length(ys)*sum(ys)
[1] 1.074752
>
```

* calculate the standard error of the sample mean

```Rout
> sd(ys)/sqrt(length(ys))
[1] 0.1007956
> 
> mvec <- vector()
> 
> for(i in 1:1e4){
+   b <- sample(1:78,size=78,replace=T)
+   ysb <- ys[b]
+   mvec[i] <- mean(ysb)
+   }
> 
> mean(mvec)
[1] 1.07545
> bootse <- sd(mvec)
> bootse
[1] 0.09972524
> 
```

* calculate the sample median:

```Rout
> median(ys)
[1] 0.8273744
>
> # middle position
> # even number of scores
> # 78+1 = 79
> # 79/2 = 39.5
> # identify 39th and 40th observations in the dataset
> 
> sort(ys)[39]
[1] 0.8207189
> sort(ys)[40]
[1] 0.83403
> 
> (sort(ys)[39]+sort(ys)[40])/2
[1] 0.8273744
>
```

* use the *t*-distribution to calculate a 93% confidence interval for the population mean

```
> # t-multipliers for 93% confidence interval
> # with df=78-1 
> 
> lcl.mult <- qt(p=0.035,df=78-1)
> lcl.mult
[1] -1.837459
> ucl.mult <- qt(p=0.965,df=78-1)
> ucl.mult
[1] 1.837459
>
> mean(ys)+lcl.mult*sd(ys)/sqrt(length(ys))
[1] 0.8895437
> mean(ys)+ucl.mult*sd(ys)/sqrt(length(ys))
[1] 1.259959
>
```

* use the bootstrap to calculate a 93% confidence interval for the population mean:

```Rout
> mean(ys)+lcl.mult*bootse
[1] 0.8915105
> mean(ys)+ucl.mult*bootse
[1] 1.257993
>
```

or we could do this:

```Rout
> mvec <- vector()
> 
> for(i in 1:1e5){
+   b <- sample(1:78,size=78,replace=T)
+   ysb <- ys[b]
+   mvec[i] <- mean(ysb)
+   }
> 
> mean(mvec)
[1] 1.075087
> quantile(mvec,0.035)
     3.5% 
0.8983753 
> quantile(mvec,0.965)
   96.5% 
1.260841 
> 
```

* use the bootstrap to calculate a 91% confidence interval for the population median

```Rout
> mvec <- vector()
> 
> for(i in 1:1e5){
+   b <- sample(1:78,size=78,replace=T)
+   ysb <- ys[b]
+   mvec[i] <- median(ysb)
+   }
> 
> quantile(mvec,0.045)
     4.5% 
0.7164798 
> quantile(mvec,0.955)
   95.5% 
1.069519 
>
```

* use the bootstrap to calculate a 87% confidence interval for the population median

```Rout
> mvec <- vector()
> 
> for(i in 1:1e5){
+   b <- sample(1:78,size=78,replace=T)
+   ysb <- ys[b]
+   mvec[i] <- median(ysb)
+   }
> 
> quantile(mvec,0.065)
     6.5% 
0.7306622 
> quantile(mvec,0.935)
   93.5% 
1.022807 
>
```

* choose one of the confidence intervals you calculated above and provide a written interpretation of that interval.

```Rout
There is an 87% chance that the last confidence interval calculated, [0.731,1.023] includes the true population median.
```

Problem 2:

* calculate the Pearson correlation between u and c, using either the textbook formula or the formula used in class.

```Rout
> # numerator of correlation coefficient formula
> 
> num <- sum((u-mean(u))*(c-mean(c)))
> 
> # denominator of correlation coefficient formula
> 
> den <- sqrt(sum((u-mean(u))^2))*sqrt(sum((c-mean(c))^2))
> 
> # correlation coefficient estimate
> 
> num/den
[1] -0.01464133
>
```

* use the cor() function to calculate the Pearson correlation and verify that you get the same answer

```Rout
> cor(u,c)
[1] -0.01464133
>
```

* conduct a permutation test to determine whether the hypothesis that the population correlation is equal to zero (Ho) should be rejected.

```Rout
# I am doing my test with a p < 0.05 significance level (two-tailed test)
# My critical region, expressed in terms of the permutation distribution,
# will be the area below the 2.5th and the area above the 97.5th percentiles
# If my actual correlation lies within the critical region, I will reject Ho

> p <- vector()
> 
> for(i in 1:3000){
+   up <- sample(u,replace=F)
+   p[i] <- cor(up,c)
+   }
> 
> quantile(p,0.025)
      2.5% 
-0.2136093 
> quantile(p,0.975)
    97.5% 
0.2139003 
>

# Since my observed correlation (-0.015) lies between the 2.5th and 97.5th percentiles,
# of the permutation distribution (i.e., it is not in the critical region) I fail to reject Ho.
```

<p align="center">
<img src="/gfiles/fig9y.png" width="500px">
</p>

* use the bootstrap to calculate a 93% confidence interval for the correlation coefficient.

```Rout
> cvec <- vector()
>  
> for(i in 1:1e5){
+   b <- sample(1:88,size=88,replace=T)
+   cvec[i] <- cor(u[b],c[b]) 
+   }
>  
> mean(cvec)
[1] -0.01328255
> quantile(cvec,0.035)
      3.5% 
-0.1941188 
> quantile(cvec,0.965)
    96.5% 
0.1738613 
>
```

* determine whether the hypothesis that the population correlation coefficient is equal to zero should be rejected based on the confidence interval.

```Rout
The Ho should not be rejected based on this evidence.
```

* use the cor.test() function to determine whether the hypothesis that the population correlation coefficient is equal to zero should be rejected.

```Rout
> cor.test(u,c)

	Pearson's product-moment correlation

data:  u and c
t = -0.13579, df = 86, p-value = 0.8923
alternative hypothesis: true correlation is not equal to 0
95 percent confidence interval:
 -0.2233985  0.1954001
sample estimates:
        cor 
-0.01464133 

>

Note: since the confidence interval includes the number zero, we fail to reject Ho at a 95% confidence level.
```

* I can also use cor.test() to calculate the 93% confidence interval:

```Rout
> cor.test(u,c,conf.level=0.93)

	Pearson's product-moment correlation

data:  u and c
t = -0.13579, df = 86, p-value = 0.8923
alternative hypothesis: true correlation is not equal to 0
93 percent confidence interval:
 -0.2080877  0.1799073
sample estimates:
        cor 
-0.01464133 

>
```

* since you know the population correlation coefficient (0.032), determine whether the 93% confidence interval actually trapped the true population value.

```Rout
Yes, the confidence interval did trap the true population parameter value.
```

* is Ho true or false?; Considering your hypothesis tests, which ones led you to the correct decision?; which ones missed the mark?

```Rout
Ho is false (the population correlation is not equal to zero).
Since all of my significance tests failed to reject Ho, they all led me to make a Type I error.
*Note*: a problem here is that the population correlation is small (close to zero) and my sample
size is small. This means my test has low *power*.
```

Problem 3: With the given population, conduct a Monte Carlo simulation study where you examine the performance of a 92% confidence interval for the population mean procedure based on the t-distribution. For your simulation study, you should draw 100,000 (1e5) samples of size N = 38 and you should calculate the coverage rate for your confidence interval procedure.

```Rout
> set.seed (78)
> yp <- rnorm(n=1e6,mean=10.5,sd=2)
> 
> t.mult.lcl <- qt(p=0.04,df=38-1)
> t.mult.ucl <- qt(p=0.96,df=38-1)
> 
> lcl <- vector()
> ucl <- vector()
> 
> for(i in 1:1e5){
+   s <- sample(1:length(yp),size=38,replace=T)
+   ys <- yp[s]
+   mean.ys <- mean(ys)
+   se.ys <- sd(ys)/sqrt(38)
+   lcl[i] <- mean.ys+t.mult.lcl*se.ys
+   ucl[i] <- mean.ys+t.mult.ucl*se.ys
+   }
> 
> trap <- ifelse(lcl<10.5 & ucl>10.5,1,0)
> mean(trap)
[1] 0.92041
>
```

Note that the coverage rate is very close to the expected 92%.

#### Topic 5: Scatterplots

* Relevant reading: Weisburd and Britt, Chapter 15; Sheather Chapter 2.1
* A scatterplot displays the joint distribution of the independent variable (x) and the dependent variable (y).
* By joint distribution, I mean that we plot each data point according to both its location on *x* and *y*.
* Let's regenerate the data we were working with last week:

```R
library(MASS)
set.seed(231)
N <- 1250
V <- mvrnorm(n=N,mu=c(0,0),Sigma=matrix(c(1,0.07,0.07,1),2,2))
x <- V[,1]
y <- V[,2]
num <- sum((x-mean(x))*(y-mean(y)))
den <- sqrt(sum((x-mean(x))^2))*sqrt(sum((y-mean(y))^2))
num/den
cor(x,y)
```

* Here is our intitial output:

```Rout
> library(MASS)
> set.seed(231)
> N <- 1250
> V <- mvrnorm(n=N,mu=c(0,0),Sigma=matrix(c(1,0.07,0.07,1),2,2))
> x <- V[,1]
> y <- V[,2]
> num <- sum((x-mean(x))*(y-mean(y)))
> den <- sqrt(sum((x-mean(x))^2))*sqrt(sum((y-mean(y))^2))
> num/den
[1] 0.08560983
> cor(x,y)
[1] 0.08560983
>
```

* Here is the R code to generate a scatterplot:

```R
plot(x,y)
```

<p align="center">
<img src="/gfiles/fig10.png" width="500px">
</p>

#### Topic 6: Least Squares

* Relevant reading: Weisburd and Britt, Chapter 15; Sheather Chapter 2.1
* If we want to draw a "best fitting" line through these points, how would we do that?
* One way would be to draw a line that minimizes the deviations between the individual data points and the line itself.
* The problem here is that negative deviations cancel out positive deviations.
* There are a couple of alternatives.
* First is the so-called least squares line:

```R
library(MASS)
set.seed(231)
N <- 1250
V <- mvrnorm(n=N,mu=c(0,0),Sigma=matrix(c(1,0.07,0.07,1),2,2))
x <- V[,1]
y <- V[,2]
num <- sum((x-mean(x))*(y-mean(y)))
den <- sqrt(sum((x-mean(x))^2))*sqrt(sum((y-mean(y))^2))
num/den
cor(x,y)

# estimate a regression line - part I
# least squares solution

int   <- seq(from=-3,to=3,by=0.01)
slope <- seq(from=-3,to=3,by=0.01)
g <- expand.grid(int,slope)
head(g)

int   <- g$Var1
slope <- g$Var2
nrow(g)

sse <- vector()

for(i in 1:361201){
  yfit <- int[i]+slope[i]*x
  sse[i] <- sum((y-yfit)^2)
  }

F <- data.frame(int,slope,sse)
Fsort <- F[order(sse),]
head(Fsort)

int.hat <- Fsort$int[1]
slope.hat <- Fsort$slope[1]

yxminus3 <- int.hat+slope.hat*(-3)
yxplus3 <- int.hat+slope.hat*3
segments(x0=-3,y0=yxminus3,x1=3,y1=yxplus3,lty=1,lwd=2,col="blue")
```

* Here are the results:

```Rout
> # estimate a regression line - part I
> # least squares solution
> 
> int   <- seq(from=-3,to=3,by=0.01)
> slope <- seq(from=-3,to=3,by=0.01)
> g <- expand.grid(int,slope)
> head(g)
   Var1 Var2
1 -3.00   -3
2 -2.99   -3
3 -2.98   -3
4 -2.97   -3
5 -2.96   -3
6 -2.95   -3
> 
> int   <- g$Var1
> slope <- g$Var2
> nrow(g)
[1] 361201
> 
> 
> sse <- vector()
> 
> for(i in 1:361201){
+   yfit <- int[i]+slope[i]*x
+   sse[i] <- sum((y-yfit)^2)
+   }
> 
> F <- data.frame(int,slope,sse)
> Fsort <- F[order(sse),]
> head(Fsort)
        int slope      sse
185411 0.02  0.08 1208.208
185410 0.01  0.08 1208.210
186011 0.01  0.09 1208.215
186012 0.02  0.09 1208.223
184810 0.02  0.07 1208.443
184809 0.01  0.07 1208.454
> 
> int.hat <- Fsort$int[1]
> slope.hat <- Fsort$slope[1]
> 
> yxminus3 <- int.hat+slope.hat*(-3)
> yxplus3 <- int.hat+slope.hat*3
> segments(x0=-3,y0=yxminus3,x1=3,y1=yxplus3,lty=1,lwd=2,col="blue")
> 
```

* Another option is to draw the least absolute value line:

```R
# estimate a regression line - part II
# least absolute value of residuals solution

int   <- seq(from=-3,to=3,by=0.01)
slope <- seq(from=-3,to=3,by=0.01)
g <- expand.grid(int,slope)
head(g)

int   <- g$Var1
slope <- g$Var2

slad <- vector()

for(i in 1:361201){
  yfit <- int[i]+slope[i]*x
  slad[i] <- sum(abs(y-yfit))
  }

F <- data.frame(int,slope,slad)
Fsort <- F[order(slad),]
head(Fsort)

int.hat <- Fsort$int[1]
slope.hat <- Fsort$slope[1]

yxminus3 <- int.hat+slope.hat*(-3)
yxplus3 <- int.hat+slope.hat*3
segments(x0=-3,y0=yxminus3,x1=3,y1=yxplus3,lty=1,lwd=2,col="red")
```

* Here is the output:

```Rout
> # estimate a regression line - part II
> # least absolute value of residuals solution
> 
> int   <- seq(from=-3,to=3,by=0.01)
> slope <- seq(from=-3,to=3,by=0.01)
> g <- expand.grid(int,slope)
> head(g)
   Var1 Var2
1 -3.00   -3
2 -2.99   -3
3 -2.98   -3
4 -2.97   -3
5 -2.96   -3
6 -2.95   -3
> 
> int   <- g$Var1
> slope <- g$Var2
> 
> slad <- vector()
> 
> for(i in 1:361201){
+   yfit <- int[i]+slope[i]*x
+   slad[i] <- sum(abs(y-yfit))
+   }
> 
> F <- data.frame(int,slope,slad)
> Fsort <- F[order(slad),]
> head(Fsort)
         int slope     slad
186008 -0.02  0.09 977.4879
186009 -0.01  0.09 977.5055
185407 -0.02  0.08 977.5135
185408 -0.01  0.08 977.5359
186609 -0.02  0.10 977.5547
186007 -0.03  0.09 977.5645
> 
> int.hat <- Fsort$int[1]
> slope.hat <- Fsort$slope[1]
> 
> yxminus3 <- int.hat+slope.hat*(-3)
> yxplus3 <- int.hat+slope.hat*3
> segments(x0=-3,y0=yxminus3,x1=3,y1=yxplus3,lty=1,lwd=2,col="red")
> 
```

<p align="center">
<img src="/gfiles/fig11a.png" width="500px">
</p>

* Notice the two lines are slightly different.
* As we will see later, the least squares solution has compelling properties that merit its centrality in applied use.

#### Topic 7: Maximum Likelihood

* Relevant reading: section 7.1 of Freedman and Sheather, pp. 90-91; also see definitions of maximum likelihood in Weisburd and Britt.
* In topic 6, we defined the LS estimator as the (unique) solution that minimizes the sum of the squared differences between predicted and actual values.
* So topic 6 describes a *minimization* problem.
* We now turn to a maximization problem: find the (unique) solution that maximizes the probability of the data looking the way they do.
* Using probability notation, we find the model, M, that maximizes the probability of the data, y, p(y|M)
* p(y|M) is called the likelihood function and the value of M that maximizes p(y|M) is called the maximum likelihood estimate.
* Let's illustrate with an example.

```R
library(MASS)
set.seed(231)
N <- 1250
V <- mvrnorm(n=N,mu=c(0,0),Sigma=matrix(c(1,0.07,0.07,1),2,2))
x <- V[,1]
y <- V[,2]
num <- sum((x-mean(x))*(y-mean(y)))
den <- sqrt(sum((x-mean(x))^2))*sqrt(sum((y-mean(y))^2))
num/den
cor(x,y)

int   <- seq(from=-3,to=3,by=0.01)
slope <- seq(from=-3,to=3,by=0.01)
sigma <- seq(from=0,to=3,by=0.1)
g <- expand.grid(int,slope,sigma)
head(g)

int   <- g$Var1
slope <- g$Var2
sigma <- g$Var3

loglike <- vector()

for(i in 1:11197231){
  yfit <- int[i]+slope[i]*x
  pt1 <- 1/sqrt(2*pi*sigma[i]^2)
  pt2 <- -(y-yfit)^2
  pt3 <- 2*sigma[i]^2
  pt4 <- pt2/pt3
  lpdf <- log(pt1*exp(pt2/pt3))
  loglike[i] <- sum(lpdf)
  }

F <- data.frame(int,slope,sigma,loglike)
Fsort <- F[order(loglike,decreasing=T),]
head(Fsort)
```
```Rout
> int   <- seq(from=-3,to=3,by=0.01)
> slope <- seq(from=-3,to=3,by=0.01)
> sigma <- seq(from=0,to=3,by=0.1)
> g <- expand.grid(int,slope,sigma)
> head(g)
   Var1 Var2 Var3
1 -3.00   -3    0
2 -2.99   -3    0
3 -2.98   -3    0
4 -2.97   -3    0
5 -2.96   -3    0
6 -2.95   -3    0
> 
> int   <- g$Var1
> slope <- g$Var2
> sigma <- g$Var3
> 
> loglike <- vector()
> 
> for(i in 1:11197231){
+   yfit <- int[i]+slope[i]*x
+   pt1 <- 1/sqrt(2*pi*sigma[i]^2)
+   pt2 <- -(y-yfit)^2
+   pt3 <- 2*sigma[i]^2
+   pt4 <- pt2/pt3
+   lpdf <- log(pt1*exp(pt2/pt3))
+   loglike[i] <- sum(lpdf)
+   }
> 
> F <- data.frame(int,slope,sigma,loglike)
> Fsort <- F[order(loglike,decreasing=T),]
> head(Fsort)
         int slope sigma   loglike
3797421 0.02  0.08     1 -1752.777
3797420 0.01  0.08     1 -1752.778
3798021 0.01  0.09     1 -1752.780
3798022 0.02  0.09     1 -1752.785
3796820 0.02  0.07     1 -1752.895
3796819 0.01  0.07     1 -1752.900
>
```
* This is a first principles observation: maximum likelihood and least squares are leading us to the same estimates for the intercept and the slope. They will yield slightly different estimates for the variance (or standard deviation) of the error term but we will address this later in the semester.

#### Topic 8: Gauss-Markov Theorem

* We now discuss the closed-form (analytic) formulas for intercept, slope, and variance of the error term.
* First, we estimate the slope:

<p align="center">
<img src="/gfiles/slope-eqn.png" width="300px">
</p>

* Here is the R code:

```R
library(MASS)
set.seed(231)
N <- 1250
V <- mvrnorm(n=N,mu=c(0,0),Sigma=matrix(c(1,0.07,0.07,1),2,2))
x <- V[,1]
y <- V[,2]
num <- sum((x-mean(x))*(y-mean(y)))
den <- sqrt(sum((x-mean(x))^2))*sqrt(sum((y-mean(y))^2))
num/den
cor(x,y)

pt1 <- x-mean(x)
pt2 <- y-mean(y)
pt3 <- (x-mean(x))^2
slope.num <- sum(pt1*pt2)
slope.den <- sum(pt3)
slope <- slope.num/slope.den
slope
```
```Rout
> pt1 <- x-mean(x)
> pt2 <- y-mean(y)
> pt3 <- (x-mean(x))^2
> slope.num <- sum(pt1*pt2)
> slope.den <- sum(pt3)
> slope <- slope.num/slope.den
> slope
[1] 0.0846087
>
```

* Second, we estimate the intercept term:

<p align="center">
<img src="/gfiles/int-eqn.png" width="300px">
</p>

```R
ybar <- mean(y)
xbar <- mean(x)
int <- ybar-slope*xbar
int
```
```Rout
> ybar <- mean(y)
> xbar <- mean(x)
> int <- ybar-slope*xbar
> int
[1] 0.01487913
>
```

* Third, we estiamte the variance (standard deviation) of the error term (sometimes called the residual sum of squares). Note that the error term for an individual case is given by $\hat{e}_i = Y_i - \hat{Y}_i$. The "^" symbol means the *predicted* or *estimated* value of $e$ or $Y$. Then, we have:

<p align="center">
<img src="/gfiles/var-eqn.png" width="200px">
</p>

```R
e <- y-(int+slope*x)
esq <- e*e
sigsq <- 1/(N-2)*sum(esq)
sigsq
sig <- sqrt(sigsq)
sig
```
```Rout
> e <- y-(int+slope*x)
> esq <- e*e
> sigsq <- 1/(N-2)*sum(esq)
> sigsq
[1] 0.9680698
> 
> sig <- sqrt(sigsq)
> sig
[1] 0.9839054
>
```

* We can also calculate the proportion of the variance of the outcome variable that is explained by the independent variable, $r^2$.

```R
tss <- sum((y-ybar)^2)
tss
rss <- sum((y-(int+slope*x))^2)
rsq <- 1-rss/tss
rsq
sqrt(rsq)
```
```Rout
> tss <- sum((y-ybar)^2)
> tss
[1] 1217.071
> rss <- sum((y-(int+slope*x))^2)
> rsq <- 1-rss/tss
> rsq
[1] 0.007329043
> sqrt(rsq)
[1] 0.08560983
>
```

* Now, let's verify our results using the linear regression function in R:

```R
summary(lm(y~1+x))
```
```Rout
> summary(lm(y~1+x))

Call:
lm(formula = y ~ 1 + x)

Residuals:
    Min      1Q  Median      3Q     Max 
-3.5020 -0.6206 -0.0334  0.6681  3.0366 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)   
(Intercept)  0.01488    0.02785   0.534  0.59325   
x            0.08461    0.02787   3.035  0.00245 **
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.9839 on 1248 degrees of freedom
Multiple R-squared:  0.007329,	Adjusted R-squared:  0.006534 
F-statistic: 9.214 on 1 and 1248 DF,  p-value: 0.002451

>
```

* The intercept is the estimated value of the outcome variable when the independent variable is set to zero.
* The slope is the estimated amount of change in the outcome when the independent variable increases by 1 unit.
* Gauss-Markov Theorem: If x is fixed, the average of the error terms is zero (no specification error), the error terms have constant variance (homoscedasticity), and the error terms are independent of each other, then the linear regression model (often referred to as the ordinary least squares estimator) is BLUE.
* BLUE means Best Linear Unbiased Estimator.
* Best means *most efficient* (smallest variance).
* Linear means a linear model of the form: $y = a+bx+e$ where *a* is the intercept term, *b* is the slope term, *x* is the independent variable, and *e* is the error or residual term.
* Unbiased means the parameter estimates are correct, *on average*.
* An estimator is a formula that produces an estimate. There are other estimators that are not the *best*, not *linear*, and *biased*. These estimators will sometimes have other properties that make them appealing.
* Consider the following equation:

<p align="center">
<img src="/gfiles/expectation.png" width="300px">
</p>

* There is no error term on this equation (which is an important distinction).
* Now, if a = 0.01488 and b = 0.08461, then we can calculate the *expected value* of the outcome when x = 0 by:

```R
a <- 0.01488
b <- 0.08461
a+b*0
```
```Rout
> a <- 0.01488
> b <- 0.08461
> a+b*0
[1] 0.01488
>
```

which is just the intercept. Now, if we set x to 1, we have:

```Rout
> a <- 0.01488
> b <- 0.08461
> a+b*1
[1] 0.09949
>
```

* Notice that the difference between the two expectations, E(y|x=1)-E(y|x=0) = 0.09949-0.01488 = 0.08461, which is the value of b (the slope). So, the slope represents the amount of change in the expected value of the outcome when the independent variable increases by 1 unit.

### Assignment #1 (Due on ELMS at 11:59pm on Monday 2/24/25)

Instructions: please review the guidelines for assignments and submission of assignments in the syllabus above. You should not discuss this assignment with others; the work you submit should be your own work. If I receive questions related to the assignment that I judge to be of interest to the entire class, I will post them below with the answers. I will respond to all questions submitted by 11:59pm (ET) on Friday 2/21/25. I will not be able to respond to any questions received after that time (so that all students will have ample time to take such questions into consideration before the Monday 2/24/25 deadline). Good luck!

1. Consider the following dataset:

```Rout
> table(y)
y
 0  1  2  3  4  5  6 
 8 27 22 30  3  9  1 
>
```

In this case, *y* is based on a sample of 15-year-old juveniles appearing in the local juvenile court last month and measures the number of prior juvenile court appearances for each person. 

- a. Calculate the average number of prior court appearances in the sample (5pts).
- b. Calculate the standard error of the sample mean (5pts).
- c. Use the appropriate percentiles of the t-distribution to calculate a 89% confidence interval for the mean (7pts).
- d. Use the bootstrap to create a 89% confidence interval for the mean (7pts).
- e. Explain why we can use the t-distribution (which is symmetric) to develop a 89% confidence interval for the mean (which is based on raw data points that are skewed); (4pts).
- f. Use the bootstrap to calculate a 97% confidence interval for the median (7pts).

2. Here is a dataset with 2 variables, *x* and *y*:

```R
x <- c(-0.47977510,1.16861329,-2.46667866,0.17826383,
       -0.60534305,-0.80975857,-1.05864910,0.25372928,
        0.15288052,-0.86883576,-1.82683789,0.10042614,  
        0.05388706,0.79631057,0.50712787,-0.58209653,
       -0.11583157)
y <- c(0.3464074,1.4334348,-0.5924495,1.1842742,
       0.4081207,0.5262941,-0.2749569,-2.3724632,
       1.0493061,-1.1020648,0.1192672,0.6126463,
       0.2745064,-0.4594763,0.7329235,1.5497059,
      -1.0191696)
```

- a. Use the cor() function and the formula-based approach to calculate the correlation coefficient between *x* and *y* (5pts).
- b. Use the cor.test() function to calculate a 83% confidence interval for the correlation (5pts).
- c. Use the bootstrap to calculate a 83% confidence interval for the correlation (7pts).
- d. Based on the evidence in 2b and 2c, report what you conclude about a hypothesis test that the population correlation coefficient is equal to zero. Explain your reasoning (5pts).
- e. Conduct a permutation test of the hypothesis that the population correlation coefficient is equal to zero. Conduct your test at the p < 0.07 significance level (two-tailed). Report your conclusion and create a histogram of the permutation distribution to summarize your results (10pts).
- f. Create a scatterplot showing the joint distribution of *x* and *y*. (5pts).
- g. Estimate a linear regression model using the lm() function (5pts).
- h. Using your estimates in 2g, calculate the expected value of the outcome variable when x is -1; then calculate the expected value of the outcome variable x is +2. What is the difference between the two expected outcomes? How does this difference relate to what you see in 2g? Hint: focus on the estimated slope coefficient. (7pts).
- i. Use the formulas described in Topic 8 to calculate the slope, intercept, and residual standard error estimates. Verify that your calculations agree with those from the summary table estimated in 2g (4pts).

3. You are given the following population of risk assessment scores.

```R
set.seed(your student id number)
yp <- rnorm(n=1e5,mean=7,sd=0.5)
```

Conduct a Monte Carlo study of the performance of the 93% confidence interval for the mean using the t-distribution. For this study, you should draw 100,000 samples of size N=10 (with replacement) from the population. Based on this exercise, what do you conclude about the validity of the procedure used to calculate this confidence interval? (12pts).

#### Questions from Students About the Assignment

1. There have been a couple of questions about proper programming or interpretation of the bootstrap in Question 1. Because this is a graded assignment, I am very limited in being able to answer these sorts of questions at this point but what I will say to all of you is that I encourage you to look back at the practice problems that we did and connect what you are being asked to do in the assignment back to what you (we) did when we solved the practice problems. This may involve you going back and working through a practice problem from start to finish in order to be able to solve a related problem on the assignment. Good luck!

2. For creating the scatter plot in Question 2 Part F on the assignment, should we also include a regression line or additional labels?

My response: I recommend doing only what the question is asking you to do.

### Lesson 5: Monday 2/24/25

* Reminder: first assignment is due tonight at 11:59pm on ELMS.
* Tonight, we will focus on topics 9, 10, and 11.
* Relevant reading for tonight's topics is in Chapter 15 of Weisburd and Britt, 2.1-2.2 of Sheather's book, and 2.1-2.2 of Freedman's book

#### Topic 9: Linear regression with standardized variables

```R
# options for numbers on printout

options(scipen=100)

# set random number seed for reproducibility

set.seed(487)

# create a sample data set
# r = risk score
# y = offense score

N <- 1e5
r <- 100+rnorm(n=N,mean=0,sd=10)
e <- rnorm(n=N,mean=0,sd=10)
y <- 27+1/7*r+e

# standardize the predictor/outcome variables

rs <- (r-mean(r))/sd(r)
ys <- (y-mean(y))/sd(y)

# estimate the population statistical model

M <- lm(ys~1+rs)
M
```

* Note that this code generates the population and estimates the population regression when both the independent and outcome variables are standardized (i.e., a mean of zero and a standard deviation of 1).

```Rout
> # options for numbers on printout
> 
> options(scipen=100)
> 
> # set random number seed for reproducibility
> 
> set.seed(487)
> 
> # create a sample data set
> # r = risk score
> # y = offense score
> 
> N <- 1e5
> r <- 100+rnorm(n=N,mean=0,sd=10)
> e <- rnorm(n=N,mean=0,sd=10)
> y <- 27+1/7*r+e
> 
> # standardize the predictor/outcome variables
> 
> rs <- (r-mean(r))/sd(r)
> ys <- (y-mean(y))/sd(y)
> 
> # estimate the population statistical model
> 
> M <- lm(ys~1+rs)
> M

Call:
lm(formula = ys ~ 1 + rs)

Coefficients:
          (Intercept)                     rs  
0.0000000000000003728  0.1436803493136980803  

>
```

* Next, we calculate the Pearson correlation coefficient:

```R
# calculate the population Pearson correlation

cor(rs,ys)
```

* Here is the output:

```Rout
> # calculate the population Pearson correlation
> 
> cor(rs,ys)
[1] 0.1436803
```

* Notice that this correlation coefficient is equal to the slope coefficient estimated in the population regression equation.
* Here is the code to create a scatterplot for the population:

```R
# create a scatterplot

plot(rs,ys,pch=19)
abline(M,lty=1,lwd=2,col="red")
abline(h=-3:3,lty=3,lwd=0.8)
abline(v=-3:3,lty=3,lwd=0.8)
```

* Here is what the scatterplot looks like:

<p align="center">
<img src="/gfiles/fig91.png" width="600px">
</p>

* So far, we've just been looking at the population. Now, we will draw several samples of size N = 100 from the population.
* At the end of this code block we get a panel of scatterplots summarizing the results for each of the samples.

```R
s1 <- sample(1:N,size=100,replace=T)
s2 <- sample(1:N,size=100,replace=T)
s3 <- sample(1:N,size=100,replace=T)
s4 <- sample(1:N,size=100,replace=T)
s5 <- sample(1:N,size=100,replace=T)
s6 <- sample(1:N,size=100,replace=T)

y1 <- (y[s1]-mean(y[s1]))/sd(y[s1])
y2 <- (y[s2]-mean(y[s2]))/sd(y[s2])
y3 <- (y[s3]-mean(y[s3]))/sd(y[s3])
y4 <- (y[s4]-mean(y[s4]))/sd(y[s4])
y5 <- (y[s5]-mean(y[s5]))/sd(y[s5])
y6 <- (y[s6]-mean(y[s6]))/sd(y[s6])

r1 <- (r[s1]-mean(r[s1]))/sd(r[s1])
r2 <- (r[s2]-mean(r[s2]))/sd(r[s2])
r3 <- (r[s3]-mean(r[s3]))/sd(r[s3])
r4 <- (r[s4]-mean(r[s4]))/sd(r[s4])
r5 <- (r[s5]-mean(r[s5]))/sd(r[s5])
r6 <- (r[s6]-mean(r[s6]))/sd(r[s6])

m1 <- lm(y1~1+r1)
m2 <- lm(y2~1+r2)
m3 <- lm(y3~1+r3)
m4 <- lm(y4~1+r4)
m5 <- lm(y5~1+r5)
m6 <- lm(y6~1+r6)

par(mfrow=c(2,3))

plot(x=r1,y=y1,pch=19)
abline(m1,lty=1,lwd=2,col="red")

plot(x=r2,y=y2,pch=19)
abline(m2,lty=1,lwd=2,col="red")

plot(x=r3,y=y3,pch=19)
abline(m3,lty=1,lwd=2,col="red")

plot(x=r4,y=y4,pch=19)
abline(m4,lty=1,lwd=2,col="red")

plot(x=r5,y=y5,pch=19)
abline(m5,lty=1,lwd=2,col="red")

plot(x=r6,y=y6,pch=19)
abline(m6,lty=1,lwd=2,col="red")
```

* Here are the resulting plots:

<p align="center">
<img src="/gfiles/fig92.png" width="600px">
</p>

* These were samples of size N = 100 each. Now let's draw samples of size N = 1000 each and see what changes:

```R
s1 <- sample(1:N,size=1000,replace=T)
s2 <- sample(1:N,size=1000,replace=T)
s3 <- sample(1:N,size=1000,replace=T)
s4 <- sample(1:N,size=1000,replace=T)
s5 <- sample(1:N,size=1000,replace=T)
s6 <- sample(1:N,size=1000,replace=T)

y1 <- (y[s1]-mean(y[s1]))/sd(y[s1])
y2 <- (y[s2]-mean(y[s2]))/sd(y[s2])
y3 <- (y[s3]-mean(y[s3]))/sd(y[s3])
y4 <- (y[s4]-mean(y[s4]))/sd(y[s4])
y5 <- (y[s5]-mean(y[s5]))/sd(y[s5])
y6 <- (y[s6]-mean(y[s6]))/sd(y[s6])

r1 <- (r[s1]-mean(r[s1]))/sd(r[s1])
r2 <- (r[s2]-mean(r[s2]))/sd(r[s2])
r3 <- (r[s3]-mean(r[s3]))/sd(r[s3])
r4 <- (r[s4]-mean(r[s4]))/sd(r[s4])
r5 <- (r[s5]-mean(r[s5]))/sd(r[s5])
r6 <- (r[s6]-mean(r[s6]))/sd(r[s6])

m1 <- lm(y1~1+r1)
m2 <- lm(y2~1+r2)
m3 <- lm(y3~1+r3)
m4 <- lm(y4~1+r4)
m5 <- lm(y5~1+r5)
m6 <- lm(y6~1+r6)

par(mfrow=c(2,3))

plot(x=r1,y=y1,pch=19)
abline(m1,lty=1,lwd=2,col="red")

plot(x=r2,y=y2,pch=19)
abline(m2,lty=1,lwd=2,col="red")

plot(x=r3,y=y3,pch=19)
abline(m3,lty=1,lwd=2,col="red")

plot(x=r4,y=y4,pch=19)
abline(m4,lty=1,lwd=2,col="red")

plot(x=r5,y=y5,pch=19)
abline(m5,lty=1,lwd=2,col="red")

plot(x=r6,y=y6,pch=19)
abline(m6,lty=1,lwd=2,col="red")
```

* Here is our output:

<p align="center">
<img src="/gfiles/fig93.png" width="600px">
</p>

* Next, let's focus on the estimates we get from our 3rd sample of size 1,000 cases above.

```
# interpret model 3

boxplot(r3,y3)
summary(m3)
cor.test(r3,y3)

rvalues <- -3:3
yvalues <- 0+0.201*rvalues
data.frame(rvalues,yvalues)
```

* Here is our output. First, the boxplot (showing the ranges of our independent and outcome variables). Then, we will look at the model that was estimated for the 3rd sample and the predictions that the model makes conditioning on different values of the predictor variables.

<p align="center">
<img src="/gfiles/fig93.png" width="500px">
</p>

```Rout
> summary(m3)

Call:
lm(formula = y3 ~ 1 + r3)

Residuals:
    Min      1Q  Median      3Q     Max 
-2.5627 -0.6689 -0.0437  0.6238  3.5271 

Coefficients:
                          Estimate             Std. Error
(Intercept) -0.0000000000000001449  0.0309902612584614726
r3           0.2014077078535495835  0.0310057680201316112
            t value      Pr(>|t|)    
(Intercept)   0.000             1    
r3            6.496 0.00000000013 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.98 on 998 degrees of freedom
Multiple R-squared:  0.04057,	Adjusted R-squared:  0.0396 
F-statistic:  42.2 on 1 and 998 DF,  p-value: 0.0000000001301

> cor.test(r3,y3)

	Pearson's product-moment correlation

data:  r3 and y3
t = 6.4958, df = 998, p-value = 0.0000000001301
alternative hypothesis: true correlation is not equal to 0
95 percent confidence interval:
 0.1411773 0.2601526
sample estimates:
      cor 
0.2014077 

> 
> rvalues <- -3:3
> yvalues <- 0+0.201*rvalues
> data.frame(rvalues,yvalues)
  rvalues yvalues
1      -3  -0.603
2      -2  -0.402
3      -1  -0.201
4       0   0.000
5       1   0.201
6       2   0.402
7       3   0.603
>
```

#### Topic 10: Linear regression with unstandardized variables

* Keep the same R session open from Topic 9 above.
* We will now consider what happens if we study the relationship between the unstandardized version of the outcome variable and the standardized version of the independent variable.
* Again, our focus here is on what happens in the 3rd sample we drew up above.

```R
# first, put r in its standardized metric
# and put y in its raw metric

yraw3 <- y[s3]
rstd3 <- (r[s3]-mean(r[s3]))/sd(r[s3])

m3a <- lm(yraw3~1+rstd3)
summary(m3a)
cor.test(rstd3,yraw3)

rvalues <- -3:3
yvalues <- 41.4086+1.9741*rvalues
data.frame(rvalues,yvalues)
```

* Here is our output:

```Rout
> yraw3 <- y[s3]
> rstd3 <- (r[s3]-mean(r[s3]))/sd(r[s3])
> 
> m3a <- lm(yraw3~1+rstd3)
> summary(m3a)

Call:
lm(formula = yraw3 ~ 1 + rstd3)

Residuals:
    Min      1Q  Median      3Q     Max 
-25.118  -6.557  -0.428   6.115  34.571 

Coefficients:
            Estimate Std. Error t value             Pr(>|t|)
(Intercept)  41.4086     0.3038 136.323 < 0.0000000000000002
rstd3         1.9741     0.3039   6.496        0.00000000013
               
(Intercept) ***
rstd3       ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 9.606 on 998 degrees of freedom
Multiple R-squared:  0.04057,	Adjusted R-squared:  0.0396 
F-statistic:  42.2 on 1 and 998 DF,  p-value: 0.0000000001301

> cor.test(rstd3,yraw3)

	Pearson's product-moment correlation

data:  rstd3 and yraw3
t = 6.4958, df = 998, p-value = 0.0000000001301
alternative hypothesis: true correlation is not equal to 0
95 percent confidence interval:
 0.1411773 0.2601526
sample estimates:
      cor 
0.2014077 

> 
> rvalues <- -3:3
> yvalues <- 41.4086+1.9741*rvalues
> data.frame(rvalues,yvalues)
  rvalues yvalues
1      -3 35.4863
2      -2 37.4604
3      -1 39.4345
4       0 41.4086
5       1 43.3827
6       2 45.3568
7       3 47.3309
>
```

* Next, we analyze the understandardized version of the independent variable and the standardized version of the outcome (the opposite of what we did in the last example):

```R
ystd3 <- (y[s3]-mean(y[s3]))/sd(y[s3])
rraw3 <- r[s3]

hist(rraw3)

m3b <- lm(ystd3~1+rraw3)
summary(m3b)
cor.test(rraw3,ystd3)

rvalues <- seq(from=70,to=130,by=10)
yvalues <- -2.004471+0.019987*rvalues
data.frame(rvalues,yvalues)
```

* Here is our output -- again, this is all for the 3rd sample:

```Rout
> ystd3 <- (y[s3]-mean(y[s3]))/sd(y[s3])
> rraw3 <- r[s3]
> 
> hist(rraw3)
> 
> m3b <- lm(ystd3~1+rraw3)
> summary(m3b)

Call:
lm(formula = ystd3 ~ 1 + rraw3)

Residuals:
    Min      1Q  Median      3Q     Max 
-2.5627 -0.6689 -0.0437  0.6238  3.5271 

Coefficients:
             Estimate Std. Error t value      Pr(>|t|)    
(Intercept) -2.004471   0.310131  -6.463 0.00000000016 ***
rraw3        0.019987   0.003077   6.496 0.00000000013 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.98 on 998 degrees of freedom
Multiple R-squared:  0.04057,	Adjusted R-squared:  0.0396 
F-statistic:  42.2 on 1 and 998 DF,  p-value: 0.0000000001301

> cor.test(rraw3,ystd3)

	Pearson's product-moment correlation

data:  rraw3 and ystd3
t = 6.4958, df = 998, p-value = 0.0000000001301
alternative hypothesis: true correlation is not equal to 0
95 percent confidence interval:
 0.1411773 0.2601526
sample estimates:
      cor 
0.2014077 

> 
> rvalues <- seq(from=70,to=130,by=10)
> yvalues <- -2.004471+0.019987*rvalues
> data.frame(rvalues,yvalues)
  rvalues   yvalues
1      70 -0.605381
2      80 -0.405511
3      90 -0.205641
4     100 -0.005771
5     110  0.194099
6     120  0.393969
7     130  0.593839
>
```

* Finally, we examine what happens when we work with the unstandardized versions of both the independent and the outcome variables:

```R
yraw3 <- y[s3]
rraw3 <- r[s3]

m3c <- lm(yraw3~1+rraw3)
summary(m3c)
cor.test(rraw3,yraw3)

rvalues <- seq(from=70,to=130,by=10)
yvalues <- 21.76159+0.19590*rvalues
data.frame(rvalues,yvalues)
```

* Here is our output:

```Rout
> yraw3 <- y[s3]
> rraw3 <- r[s3]
> 
> m3c <- lm(yraw3~1+rraw3)
> summary(m3c)

Call:
lm(formula = yraw3 ~ 1 + rraw3)

Residuals:
    Min      1Q  Median      3Q     Max 
-25.118  -6.557  -0.428   6.115  34.571 

Coefficients:
            Estimate Std. Error t value         Pr(>|t|)    
(Intercept) 21.76159    3.03978   7.159 0.00000000000157 ***
rraw3        0.19590    0.03016   6.496 0.00000000013008 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 9.606 on 998 degrees of freedom
Multiple R-squared:  0.04057,	Adjusted R-squared:  0.0396 
F-statistic:  42.2 on 1 and 998 DF,  p-value: 0.0000000001301

> cor.test(rraw3,yraw3)

	Pearson's product-moment correlation

data:  rraw3 and yraw3
t = 6.4958, df = 998, p-value = 0.0000000001301
alternative hypothesis: true correlation is not equal to 0
95 percent confidence interval:
 0.1411773 0.2601526
sample estimates:
      cor 
0.2014077 

> 
> rvalues <- seq(from=70,to=130,by=10)
> yvalues <- 21.76159+0.19590*rvalues
> data.frame(rvalues,yvalues)
  rvalues  yvalues
1      70 35.47459
2      80 37.43359
3      90 39.39259
4     100 41.35159
5     110 43.31059
6     120 45.26959
7     130 47.22859
>
```

* In each of the examples above, we note that the substantive conclusions are the same.
* The results are hard to compare, however, since the variables are expressed in different metrics.
* Here are a series of scatterplots to show the results are actually exactly the same across the different analyses.

```R
par(mfrow=c(2,2))
plot(x=rstd3,y=ystd3,pch=19)
abline(m3,col="red")
plot(x=rstd3,y=yraw3,pch=19)
abline(m3a,col="red")
plot(x=rraw3,y=ystd3,pch=19)
abline(m3b,col="red")
plot(x=rraw3,y=yraw3,pch=19)
abline(m3c,col="red")
```

<p align="center">
<img src="/gfiles/fig95.png" width="600px">
</p>

#### Practice Problems for Week of 2/24/25-3/3/25

Problem 1 - Read in the following dataset:

```R
set.seed(202)
x <- rnorm(n=832,mean=15,sd=2.2)
y <- 9-1/8*x+rnorm(n=832,mean=0,sd=2.1)
d <- data.frame(x,y)
head(d,n=12)
```

* Convert *x* and *y* into z-score form.
* Calculate the Pearson correlation coefficient summarizing the linear relationship between *x* and *y*.
* Calculate the Pearson correlation coefficient summarizing the linear relationship between the standardized versions of *x* and *y*.
* Estimate a linear regression where the outcome is the standardized version of *y* and the independent variable is the standardized version of *x*.
* Compare the slope coefficient from the linear regression to the correlation coefficient; what do you conclude?
* Create a table where you show how the expected value of the standardized *y* varies with the standardized *x*.
* Test the hypothesis that the population correlation coefficient/slope is equal to zero at the *p* < .05 significance level. What evidence do you cite to support your conclusion?
* Estimate a linear regression and correlation using the unstandardized versions of *x* and *y*.
* Create scatterplots (with regression lines) that show the joint distribution of *x* and *y* and the standardized version of *x* and *y*. Summarize the relationship that you see between *x* and *y* based on the information in the scatterplots.

Problem 2 - Read in the following dataset:

```R
set.seed(397)
x <- rnorm(n=309,mean=7,sd=2)
y <- 3+0*x+rnorm(n=309,mean=0,sd=1.5)
d <- data.frame(x,y)
head(d,n=12)
```

* Convert *x* and *y* into z-score form.
* Calculate the Pearson correlation coefficient summarizing the linear relationship between *x* and *y*.
* Calculate the Pearson correlation coefficient summarizing the linear relationship between the standardized versions of *x* and *y*.
* Estimate a linear regression where the outcome is the standardized version of *y* and the independent variable is the standardized version of *x*.
* Compare the slope coefficient from the linear regression to the correlation coefficient; what do you conclude?
* Create a table where you show how the expected value of the standardized *y* varies with the standardized *x*.
* Test the hypothesis that the population correlation coefficient/slope is equal to zero at the *p* < .05 significance level. What evidence do you cite to support your conclusion?
* Estimate a linear regression and correlation using the unstandardized versions of *x* and *y*.
* Create scatterplots (with regression lines) that show the joint distribution of *x* and *y* and the standardized version of *x* and *y*. Summarize the relationship that you see between *x* and *y* based on the information in the scatterplots.


### Lesson 6: Monday 3/3/25

* Reminder: next assignment will be distributed next week and will be due after spring break.
* Tonight, we turn to the problem of estimating a linear regression model with a binary independent variable (Topic 11; Section 2.6 of Sheather's book).
* Following that we will consider the problem of measurement error; (Blalock et al., 1970; [link](https://www.jstor.org/stable/270784))
* And then we will turn to the problem of extrapolation (Manski, 1993; [link](https://www.jstor.org/stable/271005))
* We will have an overview of topic #14 (causal inference and omitted variables). You should look at Freedman Chapter 1 for a discussion of this issue.
* You can also look at the Minneapolis Domestic Violence Experiment ([link](https://www.jstor.org/stable/pdf/2288920.pdf)).

#### Topic 11: Regression with a categorical (binary) independent variable

* Here is some R code to generate a population dataset with a "treatment" independent variable and a continuous (addiction severity score) outcome.
  
```R
set.seed(329)
N <- 1e5
treatment <- rbinom(n=N,size=1,p=0.5)
e <- rnorm(n=N,mean=10,sd=1)
y <- -1/5*treatment+e
d <- data.frame(treatment,y)

# boxplot of population distribution of y
# stratified by treatment group

boxplot(d$y~d$treatment)
```

* Here is the resulting (population) boxplot:

<p align="center">
<img src="/gfiles/trt-boxplot.png" width="600px">
</p>

* Next, we separate the population into 2 datasets:

```R
table(d$treatment)
t0 <- subset(d,treatment==0)
nrow(t0)
t1 <- subset(d,treatment==1)
nrow(t1)
mean(t0$y)
mean(t1$y)

# calculate difference between means for
# the two groups in the population

mean(t1$y)-mean(t0$y)
```

* Here are the results (again, this is for the population data):
  
```Rout
> table(d$treatment)

    0     1 
49779 50221 
> t0 <- subset(d,treatment==0)
> nrow(t0)
[1] 49779
> t1 <- subset(d,treatment==1)
> nrow(t1)
[1] 50221
> mean(t0$y)
[1] 9.995286
> mean(t1$y)
[1] 9.811327
> 
> # calculate difference between means for
> # the two groups in the population
> 
> mean(t1$y)-mean(t0$y)
[1] -0.1839596
>
```

* Now, we estimate a population regression model:

```R
M <- lm(y~1+treatment,data=d)
M
```
which gives the following output:

```Rout
> M <- lm(y~1+treatment,data=d)
> M

Call:
lm(formula = y ~ 1 + treatment, data = d)

Coefficients:
(Intercept)    treatment  
      9.995       -0.184  

>
```

* Now, we draw a random sample from the population and perform some calculations:

```R
s <- sample(1:N,size=300,replace=T)
ys <- y[s]
ts <- treatment[s]
samp <- data.frame(ts,ys)

# estimate a regression using the sample

ms <- lm(ys~1+ts,data=samp)
summary(ms)

y.group0 <- 9.93052
y.group0
y.group1 <- 9.93052+(-0.15636)
y.group1
y.group1-y.group0

# calculate a t-test for the difference between
# the two means

t.test(ys~ts,data=samp,var.equal=T)
```

* Here is our *sample* output:

```Rout
> s <- sample(1:N,size=300,replace=T)
> ys <- y[s]
> ts <- treatment[s]
> samp <- data.frame(ts,ys)
> 
> # estimate a regression using the sample
> 
> ms <- lm(ys~1+ts,data=samp)
> summary(ms)

Call:
lm(formula = ys ~ 1 + ts, data = samp)

Residuals:
     Min       1Q   Median       3Q      Max 
-2.96639 -0.59833 -0.04011  0.57416  2.62609 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  9.93052    0.07825 126.901   <2e-16 ***
ts          -0.15636    0.10887  -1.436    0.152    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.9423 on 298 degrees of freedom
Multiple R-squared:  0.006875,	Adjusted R-squared:  0.003542 
F-statistic: 2.063 on 1 and 298 DF,  p-value: 0.152

> 
> y.group0 <- 9.93052
> y.group0
[1] 9.93052
> y.group1 <- 9.93052+(-0.15636)
> y.group1
[1] 9.77416
> y.group1-y.group0
[1] -0.15636
> 
> # calculate a t-test for the difference between
> # the two means
> 
> t.test(ys~ts,data=samp,var.equal=T)

	Two Sample t-test

data:  ys by ts
t = 1.4363, df = 298, p-value = 0.152
alternative hypothesis: true difference in means between group 0 and group 1 is not equal to 0
95 percent confidence interval:
 -0.05788325  0.37061295
sample estimates:
mean in group 0 mean in group 1 
       9.930517        9.774152 

>
```

* The purpose of this exercise is to establish an equivalence between what we learn from a linear regression model with a binary independent variable and a two-sample *t*-test (assuming the variances of the groups are equal).
* We will return to the problem of what happens when the variances are not equal (topic 16).

#### Topic 12: (Random) Measurement error

* There are three versions of the measurement error problem.
* Version 1: measurement error in the dependent variable.
* Version 2: measurement error in the independent variable.
* We deal with the correctly measured case first:

```R
set.seed(342)

intvec <- vector()
slopevec <- vector()
sigmavec <- vector()

for(i in 1:1e4){
  x <- rnorm(n=300,mean=5.7,sd=1.3)
  y <- 7-0.05*x+rnorm(n=300,mean=0,sd=2)
  M <- lm(y~1+x)
  intvec[i] <- coef(M)[1]
  slopevec[i] <- coef(M)[2]
  sigmavec[i] <- sigma(M)
  }

mean(intvec)
mean(slopevec)
mean(sigmavec)
median(sigmavec)
sd(intvec)
sd(slopevec)

par(mfrow=c(1,3))
hist(intvec)
hist(slopevec)
hist(sigmavec)
```

* Here is the output:

```Rout
> set.seed(342)
> 
> intvec <- vector()
> slopevec <- vector()
> sigmavec <- vector()
> 
> for(i in 1:1e4){
+   x <- rnorm(n=300,mean=5.7,sd=1.3)
+   y <- 7-0.05*x+rnorm(n=300,mean=0,sd=2)
+   M <- lm(y~1+x)
+   intvec[i] <- coef(M)[1]
+   slopevec[i] <- coef(M)[2]
+   sigmavec[i] <- sigma(M)
+   }
> 
> mean(intvec)
[1] 6.99662
> mean(slopevec)
[1] -0.04912021
> mean(sigmavec)
[1] 1.999042
> median(sigmavec)
[1] 1.998748
> sd(intvec)
[1] 0.5207726
> sd(slopevec)
[1] 0.08882824
>
> par(mfrow=c(1,3))
> hist(intvec)
> hist(slopevec)
> hist(sigmavec)
>
```

<p align="center">
<img src="/gfiles/hist-plots.png" width="600px">
</p>

* Now, let's suppose our dependent variable is measured with random error.

```R
set.seed(358)

intvec.true <- vector()
slopevec.true <- vector()
sigmavec.true <- vector()
intvec.err <- vector()
slopevec.err <- vector()
sigmavec.err <- vector()

for(i in 1:1e4){
  x <- rnorm(n=300,mean=5.7,sd=1.3)
  rme <- rnorm(n=300,mean=0,sd=0.5)
  ytrue <- 7-0.05*x+rnorm(n=300,mean=0,sd=2)
  yrme <- ytrue+rme
  Mtrue <- lm(ytrue~1+x)
  Merr <- lm(yrme~1+x)
  intvec.true[i] <- coef(Mtrue)[1]
  slopevec.true[i] <- coef(Mtrue)[2]
  sigmavec.true[i] <- sigma(Mtrue)
  intvec.err[i] <- coef(Merr)[1]
  slopevec.err[i] <- coef(Merr)[2]
  sigmavec.err[i] <- sigma(Merr)
  }

mean(intvec.true)
mean(slopevec.true)
mean(sigmavec.true)
median(sigmavec.true)
sd(intvec.true)
sd(slopevec.true)

mean(intvec.err)
mean(slopevec.err)
mean(sigmavec.err)
median(sigmavec.err)
sd(intvec.err)
sd(slopevec.err)
```

* Here is our output:

```Rout
> set.seed(358)
> 
> intvec.true <- vector()
> slopevec.true <- vector()
> sigmavec.true <- vector()
> intvec.err <- vector()
> slopevec.err <- vector()
> sigmavec.err <- vector()
> 
> for(i in 1:1e4){
+   x <- rnorm(n=300,mean=5.7,sd=1.3)
+   rme <- rnorm(n=300,mean=0,sd=0.5)
+   ytrue <- 7-0.05*x+rnorm(n=300,mean=0,sd=2)
+   yrme <- ytrue+rme
+   Mtrue <- lm(ytrue~1+x)
+   Merr <- lm(yrme~1+x)
+   intvec.true[i] <- coef(Mtrue)[1]
+   slopevec.true[i] <- coef(Mtrue)[2]
+   sigmavec.true[i] <- sigma(Mtrue)
+   intvec.err[i] <- coef(Merr)[1]
+   slopevec.err[i] <- coef(Merr)[2]
+   sigmavec.err[i] <- sigma(Merr)
+   }
> 
> mean(intvec.true)
[1] 7.006265
> mean(slopevec.true)
[1] -0.05111041
> mean(sigmavec.true)
[1] 1.997589
> median(sigmavec.true)
[1] 1.996715
> sd(intvec.true)
[1] 0.5214808
> sd(slopevec.true)
[1] 0.08897388
> 
> mean(intvec.err)
[1] 7.005513
> mean(slopevec.err)
[1] -0.05101773
> mean(sigmavec.err)
[1] 2.058758
> median(sigmavec.err)
[1] 2.058886
> sd(intvec.err)
[1] 0.5398686
> sd(slopevec.err)
[1] 0.09214619
> 
```

* Next, let's see what happens when we induce random measurement error into our independent variable:

```R
set.seed(409)

intvec.true <- vector()
slopevec.true <- vector()
sigmavec.true <- vector()
intvec.err <- vector()
slopevec.err <- vector()
sigmavec.err <- vector()

for(i in 1:1e4){
  rme <- rnorm(n=300,mean=0,sd=0.5)
  xtrue <- rnorm(n=300,mean=5.7,sd=1.3)
  xerr <- xtrue+rme
  y <- 7-0.05*xtrue+rnorm(n=300,mean=0,sd=2)
  Mtrue <- lm(y~1+xtrue)
  Merr <- lm(y~1+xerr)
  intvec.true[i] <- coef(Mtrue)[1]
  slopevec.true[i] <- coef(Mtrue)[2]
  sigmavec.true[i] <- sigma(Mtrue)
  intvec.err[i] <- coef(Merr)[1]
  slopevec.err[i] <- coef(Merr)[2]
  sigmavec.err[i] <- sigma(Merr)
  }

mean(intvec.true)
mean(slopevec.true)
mean(sigmavec.true)
median(sigmavec.true)
sd(intvec.true)
sd(slopevec.true)

mean(intvec.err)
mean(slopevec.err)
mean(sigmavec.err)
median(sigmavec.err)
sd(intvec.err)
sd(slopevec.err)
```

* Here is our output:

```Rout
> set.seed(409)
> 
> intvec.true <- vector()
> slopevec.true <- vector()
> sigmavec.true <- vector()
> intvec.err <- vector()
> slopevec.err <- vector()
> sigmavec.err <- vector()
> 
> for(i in 1:1e4){
+   rme <- rnorm(n=300,mean=0,sd=0.5)
+   xtrue <- rnorm(n=300,mean=5.7,sd=1.3)
+   xerr <- xtrue+rme
+   y <- 7-0.05*xtrue+rnorm(n=300,mean=0,sd=2)
+   Mtrue <- lm(y~1+xtrue)
+   Merr <- lm(y~1+xerr)
+   intvec.true[i] <- coef(Mtrue)[1]
+   slopevec.true[i] <- coef(Mtrue)[2]
+   sigmavec.true[i] <- sigma(Mtrue)
+   intvec.err[i] <- coef(Merr)[1]
+   slopevec.err[i] <- coef(Merr)[2]
+   sigmavec.err[i] <- sigma(Merr)
+   }
> 
> mean(intvec.true)
[1] 7.000103
> mean(slopevec.true)
[1] -0.04992191
> mean(sigmavec.true)
[1] 1.998765
> median(sigmavec.true)
[1] 1.997828
> sd(intvec.true)
[1] 0.524732
> sd(slopevec.true)
[1] 0.08991167
> 
> mean(intvec.err)
[1] 6.96308
> mean(slopevec.err)
[1] -0.04342411
> mean(sigmavec.err)
[1] 1.998874
> median(sigmavec.err)
[1] 1.997653
> sd(intvec.err)
[1] 0.494161
> sd(slopevec.err)
[1] 0.08431833
>
```

* Regression coefficients are unbiased when only the DV is measured with error.
* The regression coefficient for an IV is biased toward zero when the IV is measured with error.
* If there is more than one variable in the statistical model, then the bias can affect our conclusions about the coefficients for other variables.
* We will return to this issue when we reach multivariate regression later in the semester.

#### Topic 13: Extrapolation

* Extrapolation occurs when we make predictions off the support of the data we have available for our study.
* Let's consider an example:
  
```R
set.seed(202)
x <- rnorm(n=300,mean=5.7,sd=1.3)
y <- 7-0.1*x+rnorm(n=300,mean=0,sd=1.6)
M <- lm(y~1+x)
summary(M)
plot(x,y,pch=19)
abline(h=2:11,lty=3,lwd=0.8)
abline(v=2:10,lty=3,lwd=0.8)
abline(M,lty=1,lwd=3,col="red")
```

* Here is the output:

```Rout
> set.seed(202)
> x <- rnorm(n=300,mean=5.7,sd=1.3)
> y <- 7-0.1*x+rnorm(n=300,mean=0,sd=1.6)
> M <- lm(y~1+x)
> summary(M)

Call:
lm(formula = y ~ 1 + x)

Residuals:
    Min      1Q  Median      3Q     Max 
-4.5123 -1.1212 -0.0856  1.0991  4.2859 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  7.09237    0.41448  17.111   <2e-16 ***
x           -0.14577    0.06996  -2.084    0.038 *  
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.618 on 298 degrees of freedom
Multiple R-squared:  0.01436,	Adjusted R-squared:  0.01105 
F-statistic: 4.341 on 1 and 298 DF,  p-value: 0.03805

> plot(x,y,pch=19)
> abline(h=2:11,lty=3,lwd=0.8)
> abline(v=2:10,lty=3,lwd=0.8)
> abline(M,lty=1,lwd=3,col="red")
>
```

<p align="center">
<img src="/gfiles/scatter-extrapolation.png" width="600px">
</p>

* The question of extrapolation revolves around whether we are justified in making predictions about the distribution of *y* when we move into more sparse regions of *x*.
* As an example, we could use this model to make a prediction about the expected value of *y* when *x* is equal to 12.
* The prediction would be:

```Rout
> ey <- 7.09237-0.14577*12
> ey
[1] 5.34313
>
```

* But how justified would we be in making such a prediction when we don't have any observations in our data with *x* equal to 12?

#### Topic 14: Causal Inference and Omitted Variables

* Relevant reading for this section: Freedman (Chapter 1)
* An overview of the problem:
 
<p align="center">
<img src="/gfiles/g1.png" width="600px">
</p>

* And how random assignment of treatment solves the problem:
  
<p align="center">
<img src="/gfiles/g2.png" width="600px">
</p>

#### Practice Problems - From Lesson 6

1. Enter the following dataset (*x* and *y*) into R:

```Rout
> d
   x    y
1  0  8.1
2  0 10.6
3  0  9.4
4  0  9.1
5  0 11.6
6  0  9.6
7  0 11.3
8  1 10.0
9  1 10.8
10 1 10.9
11 1 12.0
12 1 12.6
13 1 12.1
14 1 10.9
>
```

* estimate a linear regression model where *x* is the independent variable and *y* is the outcome variable.
* use the *t*-test function (with equal variances) to test the hypothesis that the population treatment effect is equal to 0.
* calculate the E(y|x=1) and E(y|x=0) (the predicted values of *y* when *x* is equal to 0 and 1, respectively.
* calculate the difference between the expected values and verify that the difference is equal to the regression coefficient.
* create a boxplot showing the distribution of *y* for each level of *x*.

2. 
