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
* #3: distributed on ~~4/7~~ 4/14; due on ~~4/14~~ 4/21 at 11:59pm (ET)
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
21. ~~prediction interval~~
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
* calculate the E(y|x=1) and E(y|x=0) (the predicted values of *y* when *x* is equal to 0 and 1, respectively).
* calculate the difference between the expected values and verify that the difference is equal to the regression coefficient.
* create a boxplot showing the distribution of *y* for each level of *x*.

2. Consider this N = 18 dataset with independent variable, *x*, and dependent variable *y*. There is also an random error-contaminated version of *x* called *xs*. Estimate linear regression models, one with *x* and the other with *xs*. Compare and interpret the results from each estimation.

```Rout
> d
     x  xs    y
1  6.5 7.4 17.9
2  9.5 7.9 22.9
3  8.0 7.4 17.8
4  7.3 7.3 18.4
5  6.8 6.1 17.8
6  8.9 7.9 21.6
7  6.9 6.4 19.5
8  6.8 7.4 21.2
9  6.8 7.1 19.8
10 7.3 6.4 24.0
11 6.2 7.0 17.2
12 7.1 5.5 19.1
13 7.7 8.2 17.4
14 6.9 5.6 20.0
15 6.2 6.8 15.8
16 6.1 5.6 18.2
17 7.9 6.9 17.1
18 9.0 8.2 21.5
```

3. Using the following N = 15 dataset (which includes *x*, *y*, and an error-contaminated version of *y* called *ys), estimate separate regressions for *y* and *ys*. Then, create scatterplots with regression lines for each analysis. Compare the results across the two analyses. What do you conclude about the effect of measurement error in *y*?

```Rout
     x    y   ys
1  6.4 17.7 16.6
2  7.0 18.0 17.1
3  5.5 18.0 18.7
4  5.6 15.8 14.2
5  8.2 18.8 17.9
6  6.1 16.2 16.7
7  8.3 19.9 19.7
8  7.6 18.4 19.9
9  7.0 19.0 18.4
10 6.0 17.3 17.0
11 6.2 17.5 15.9
12 6.7 17.7 17.7
13 5.5 15.4 16.3
14 6.7 17.7 16.8
15 5.9 15.5 16.4
```

### Lesson 7: Monday 3/10/25

* Reminder: next assignment will be posted on Tuesday 3/11/25 and will be due by 11:59pm (ET) on  Tuesday 3/25/25.
* Tonight, we will work through recent practice problems.
* Then, we will turn to topic 15 (predictions and residuals).

#### Recent Practice Problems

2/24/25: Problem 1 - Read in the following dataset:

```R
set.seed(202)
x <- rnorm(n=832,mean=15,sd=2.2)
y <- 9-1/8*x+rnorm(n=832,mean=0,sd=2.1)
d <- data.frame(x,y)
head(d,n=12)
```

* Here is the output:

```Rout
> set.seed(202)
> x <- rnorm(n=832,mean=15,sd=2.2)
> y <- 9-1/8*x+rnorm(n=832,mean=0,sd=2.1)
> d <- data.frame(x,y)
> head(d,n=12)
          x         y
1  12.51007  6.749658
2  14.03091  7.826028
3  14.25992  9.761354
4  13.13649  6.314485
5  14.67874  6.170043
6  11.85279 11.141628
7  13.29148  7.225280
8  10.74671  6.644228
9  15.68870  8.133211
10 16.03103  6.177561
11 14.69543  5.752079
12 17.59574  5.099188
>
```

* Convert *x* and *y* into z-score form.

```R
> # calculate std. versions of x and y
> 
> zx <- (x-mean(x))/sd(x)
> zy <- (y-mean(y))/sd(y)
> mean(zx)
[1] -3.015208e-16
> sd(zx)
[1] 1
> mean(zy)
[1] 1.262345e-16
> sd(zy)
[1] 1
>
```

* Calculate the Pearson correlation coefficient summarizing the linear relationship between *x* and *y*.

```Rout
> cor(x,y)
[1] -0.1265627
>
```

* Calculate the Pearson correlation coefficient summarizing the linear relationship between the standardized versions of *x* and *y*.

```Rout
> cor(zx,zy)
[1] -0.1265627
>
```

* Estimate a linear regression where the outcome is the standardized version of *y* and the independent variable is the standardized version of *x*.

```Rout
> options(scipen=100)
> m <- lm(zy~1+zx)
> summary(m)

Call:
lm(formula = zy ~ 1 + zx)

Residuals:
    Min      1Q  Median      3Q     Max 
-3.4011 -0.6514 -0.0215  0.6305  4.0540 

Coefficients:
                           Estimate              Std. Error t value
(Intercept)  0.00000000000000005889  0.03441068785761793730   0.000
zx          -0.12656269289509791687  0.03443138601759943712  -3.676
            Pr(>|t|)    
(Intercept) 1.000000    
zx          0.000252 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.9926 on 830 degrees of freedom
Multiple R-squared:  0.01602,	Adjusted R-squared:  0.01483 
F-statistic: 13.51 on 1 and 830 DF,  p-value: 0.0002523

> 
```

* Compare the slope coefficient from the linear regression to the correlation coefficient; what do you conclude?

```Rout
The estimates are the same.
```

* Create a table where you show how the expected value of the standardized *y* varies with the standardized *x*.

```Rout
> xseq <- -3:3
> yfit <- 0+(-0.1265627)*xseq
> data.frame(xseq,yfit)
  xseq       yfit
1   -3  0.3796881
2   -2  0.2531254
3   -1  0.1265627
4    0  0.0000000
5    1 -0.1265627
6    2 -0.2531254
7    3 -0.3796881
>
```

* Test the hypothesis that the population correlation coefficient/slope is equal to zero at the *p* < .05 significance level. What evidence do you cite to support your conclusion?

```Rout
> cor.test(zx,zy)

	Pearson's product-moment correlation

data:  zx and zy
t = -3.6758, df = 830, p-value = 0.0002523
alternative hypothesis: true correlation is not equal to 0
95 percent confidence interval:
 -0.1928710 -0.0591037
sample estimates:
       cor 
-0.1265627 

>
```

- Note: the 95% confidence interval for the correlation coefficient does not include zero. We reject the hypothesis that the population correlation coefficient is equal to zero.

* Estimate a linear regression and correlation using the unstandardized versions of *x* and *y*.

```Rout
> # unstandardized
> 
> mu <- lm(y~1+x)
> summary(mu)

Call:
lm(formula = y ~ 1 + x)

Residuals:
    Min      1Q  Median      3Q     Max 
-6.9533 -1.3317 -0.0439  1.2890  8.2881 

Coefficients:
            Estimate Std. Error t value             Pr(>|t|)    
(Intercept)  8.79965    0.47497  18.527 < 0.0000000000000002 ***
x           -0.11522    0.03135  -3.676             0.000252 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.029 on 830 degrees of freedom
Multiple R-squared:  0.01602,	Adjusted R-squared:  0.01483 
F-statistic: 13.51 on 1 and 830 DF,  p-value: 0.0002523

>
> cor.test(x,y)

	Pearson's product-moment correlation

data:  x and y
t = -3.6758, df = 830, p-value = 0.0002523
alternative hypothesis: true correlation is not equal to 0
95 percent confidence interval:
 -0.1928710 -0.0591037
sample estimates:
       cor 
-0.1265627 

>
```

* Create scatterplots (with regression lines) that show the joint distribution of *x* and *y* and the standardized version of *x* and *y*. Summarize the relationship that you see between *x* and *y* based on the information in the scatterplots.

<p align="center">
<img src="/gfiles/scplots.png" width="600px">
</p>

- The association and the inference about the association are the same between the plots.
- The measurement scales differ, but the substantive conclusions of the 2 analyses are the same.

2/24/25: Problem 2 - Read in the following dataset:

```R
set.seed(397)
x <- rnorm(n=309,mean=7,sd=2)
y <- 3+0*x+rnorm(n=309,mean=0,sd=1.5)
d <- data.frame(x,y)
head(d,n=12)
```

* Here is the output:

```Rout
> set.seed(397)
> x <- rnorm(n=309,mean=7,sd=2)
> y <- 3+0*x+rnorm(n=309,mean=0,sd=1.5)
> d <- data.frame(x,y)
> head(d,n=12)
          x        y
1  4.468167 4.222566
2  6.579566 1.073933
3  6.559347 2.933832
4  6.577238 3.701537
5  4.679728 3.658967
6  7.744755 2.987424
7  5.752921 3.117328
8  5.878631 1.994634
9  6.255906 2.891284
10 6.820775 2.620848
11 8.088127 4.287889
12 5.140359 1.413774
>
```

* Convert x and y into z-score form.

```Rout
> zx <- (x-mean(x))/sd(x)
> zy <- (y-mean(y))/sd(y)
> mean(zx)
[1] -1.552606e-16
> sd(zx)
[1] 1
> mean(zy)
[1] -3.485166e-17
> sd(zy)
[1] 1
>
```

* Calculate the Pearson correlation coefficient summarizing the linear relationship between *x* and *y*.

```Rout
> cor(x,y)
[1] 0.03721465
>
```

* Calculate the Pearson correlation coefficient summarizing the linear relationship between the standardized versions of x and y.

```Rout
> cor(zx,zy)
[1] 0.03721465
>
```

* Estimate a linear regression where the outcome is the standardized version of y and the independent variable is the standardized version of x.

```Rout
> m <- lm(zy~1+zx)
> summary(m)

Call:
lm(formula = zy ~ 1 + zx)

Residuals:
     Min       1Q   Median       3Q      Max 
-2.48932 -0.72501 -0.02424  0.70785  2.90834 

Coefficients:
              Estimate Std. Error t value Pr(>|t|)
(Intercept) -6.014e-17  5.694e-02   0.000    1.000
zx           3.721e-02  5.703e-02   0.653    0.515

Residual standard error: 1.001 on 307 degrees of freedom
Multiple R-squared:  0.001385,	Adjusted R-squared:  -0.001868 
F-statistic: 0.4258 on 1 and 307 DF,  p-value: 0.5146

>
```

* Compare the slope coefficient from the linear regression to the correlation coefficient; what do you conclude?

The slope and correlation coefficient are the same.

* Create a table where you show how the expected value of the standardized y varies with the standardized x.

```Rout
> min(zx)
[1] -3.074007
> max(zx)
[1] 2.707538
>
> xseq <- -3:3
> yfit <- 0+0.03721465*xseq
> data.frame(xseq,yfit)
  xseq        yfit
1   -3 -0.11164395
2   -2 -0.07442930
3   -1 -0.03721465
4    0  0.00000000
5    1  0.03721465
6    2  0.07442930
7    3  0.11164395
>
```

* Test the hypothesis that the population correlation coefficient/slope is equal to zero at the p < .05 significance level. What evidence do you cite to support your conclusion?

```Rout
> cor.test(zx,zy)

	Pearson's product-moment correlation

data:  zx and zy
t = 0.65251, df = 307, p-value = 0.5146
alternative hypothesis: true correlation is not equal to 0
95 percent confidence interval:
 -0.07467258  0.14817655
sample estimates:
       cor 
0.03721465 

> qt(p=0.025,df=307-2)
[1] -1.967772
> qt(p=0.975,df=307-2)
[1] 1.967772
>
```

Our obtained t-value of 0.653 is not in the critical region (i.e., it is between the 2 critical region boundaries above (-1.968,1.968), we fail to reject the hypothesis that the population correlation coefficient/slope is equal to zero. Also, the correlation coefficient confidence interval, [-0.075,0.148] includes zero so from that vantage point the evidence is also not strong enough to reject the null hypothesis.

* Estimate a linear regression and correlation using the unstandardized versions of x and y.

```Rout
> mu <- lm(y~1+x)
> summary(mu)

Call:
lm(formula = y ~ 1 + x)

Residuals:
    Min      1Q  Median      3Q     Max 
-3.7281 -1.0858 -0.0363  1.0601  4.3556 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  2.83808    0.30971   9.164   <2e-16 ***
x            0.02794    0.04281   0.653    0.515    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.499 on 307 degrees of freedom
Multiple R-squared:  0.001385,	Adjusted R-squared:  -0.001868 
F-statistic: 0.4258 on 1 and 307 DF,  p-value: 0.5146

>
```

* Create scatterplots (with regression lines) that show the joint distribution of x and y and the standardized version of x and y. Summarize the relationship that you see between x and y based on the information in the scatterplots.

<p align="center">
<img src="/gfiles/scplots.png" width="600px">
</p>

The association and the inference about the association are the same between the plots; the measurement scales differ, but the substantive conclusions of the 2 analyses are the same.

3/3/25 Problem 1: Enter the following dataset (*x* and *y*) into R:

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

* Here is the output:

```Rout
> x <- c(rep(0,7),rep(1,7))
> y <- c(8.1,10.6,9.4,9.1,11.6,9.6,11.3,
+   10.0,10.8,10.9,12.0,12.6,12.1,10.9)
>
> d
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

```Rout
> M <- lm(y~1+x)
> summary(M)

Call:
lm(formula = y ~ 1 + x)

Residuals:
    Min      1Q  Median      3Q     Max 
-1.8571 -0.5500 -0.3929  0.7464  1.6429 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   9.9571     0.4171  23.874 1.75e-11 ***
x             1.3714     0.5898   2.325   0.0384 *  
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.103 on 12 degrees of freedom
Multiple R-squared:  0.3106,	Adjusted R-squared:  0.2531 
F-statistic: 5.406 on 1 and 12 DF,  p-value: 0.03841

>
```


* use the *t*-test function (with equal variances) to test the hypothesis that the population treatment effect is equal to 0.

```Rout
> t.test(y~x,data=d,equal.variance=T)

	Welch Two Sample t-test

data:  y by x
t = -2.3252, df = 10.976, p-value = 0.04026
alternative hypothesis: true difference in means between group 0 and group 1 is not equal to 0
95 percent confidence interval:
 -2.66996615 -0.07289099
sample estimates:
mean in group 0 mean in group 1 
       9.957143       11.328571 

>
```

* calculate the E(y|x=1) and E(y|x=0) (the predicted values of *y* when *x* is equal to 0 and 1, respectively).

```Rout
> d0 <- subset(d,x==0)
> d1 <- subset(d,x==1)
> mean(d0$y)
[1] 9.957143
> mean(d1$y)
[1] 11.32857
>
```

or, equivalently,

```Rout
> eyx0 <- 9.9571
> eyx0
[1] 9.9571
> eyx1 <- 9.9571+1.3714
> eyx1
[1] 11.3285
>
```

* calculate the difference between the expected values and verify that the difference is equal to the regression coefficient.

```Rout
> eyx1-eyx0
[1] 1.3714
> coef(M)[2]
       x 
1.371429 
>
```

* create a boxplot showing the distribution of *y* for each level of *x*.

```Rout
boxplot(y~x)
```

<p align="center">
<img src="/gfiles/scboxplot.png" width="600px">
</p>

3/3/25 Problem 2:  Consider this N = 18 dataset with independent variable, x, and dependent variable y. There is also an random error-contaminated version of x called xs. Estimate linear regression models, one with x and the other with xs. Compare and interpret the results from each estimation.

```Rout
> x <- c(6.5,9.5,8.0,7.3,6.8,8.9,6.9,6.8,6.8,7.3,6.2,7.1,7.7,6.9,6.2,6.1,7.9,9.0)
> xs <- c(7.4,7.9,7.4,7.3,6.1,7.9,6.4,7.4,7.1,6.4,7.0,5.5,8.2,5.6,6.8,5.6,6.9,8.2)
> y <- c(17.9,22.9,17.8,18.4,17.8,21.6,19.5,21.2,19.8,24.0,17.2,19.1,17.4,20.0,
+   15.8,18.2,17.1,21.5)
> d <- data.frame(x,xs,y)
> d
     x  xs    y
1  6.5 7.4 17.9
2  9.5 7.9 22.9
3  8.0 7.4 17.8
4  7.3 7.3 18.4
5  6.8 6.1 17.8
6  8.9 7.9 21.6
7  6.9 6.4 19.5
8  6.8 7.4 21.2
9  6.8 7.1 19.8
10 7.3 6.4 24.0
11 6.2 7.0 17.2
12 7.1 5.5 19.1
13 7.7 8.2 17.4
14 6.9 5.6 20.0
15 6.2 6.8 15.8
16 6.1 5.6 18.2
17 7.9 6.9 17.1
18 9.0 8.2 21.5
>
```

* Here are the regression results:

```Rout
> m1 <- lm(y~1+x)
> m2 <- lm(y~1+xs)
> summary(m1)

Call:
lm(formula = y ~ 1 + x)

Residuals:
    Min      1Q  Median      3Q     Max 
-2.8678 -0.8610  0.1543  0.9551  4.7441 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)   
(Intercept)  10.5952     3.4652   3.058  0.00752 **
x             1.1864     0.4688   2.531  0.02226 * 
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.927 on 16 degrees of freedom
Multiple R-squared:  0.2858,	Adjusted R-squared:  0.2412 
F-statistic: 6.404 on 1 and 16 DF,  p-value: 0.02226

> summary(m2)

Call:
lm(formula = y ~ 1 + xs)

Residuals:
    Min      1Q  Median      3Q     Max 
-3.4275 -1.6480 -0.0662  1.5907  4.9361 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)   
(Intercept)  16.4458     4.4070   3.732  0.00182 **
xs            0.4091     0.6295   0.650  0.52501   
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.251 on 16 degrees of freedom
Multiple R-squared:  0.02572,	Adjusted R-squared:  -0.03518 
F-statistic: 0.4223 on 1 and 16 DF,  p-value: 0.525

>
```

* Both slope coefficients are positive but the coefficient for *xs* is smaller (attenuated) in comparison to the coefficient for *x*. Remember that in this dataset, xs = x+e where e is an error term with a mean of zero (meaning that positive errors tend to cancel out negative errors).

3/3/25 Problem 3: Using the following N = 15 dataset (which includes *x*, *y*, and an error-contaminated version of *y* called *ys), estimate separate regressions for *y* and *ys*. Then, create scatterplots with regression lines for each analysis. Compare the results across the two analyses. What do you conclude about the effect of measurement error in *y*?

```Rout
     x    y   ys
1  6.4 17.7 16.6
2  7.0 18.0 17.1
3  5.5 18.0 18.7
4  5.6 15.8 14.2
5  8.2 18.8 17.9
6  6.1 16.2 16.7
7  8.3 19.9 19.7
8  7.6 18.4 19.9
9  7.0 19.0 18.4
10 6.0 17.3 17.0
11 6.2 17.5 15.9
12 6.7 17.7 17.7
13 5.5 15.4 16.3
14 6.7 17.7 16.8
15 5.9 15.5 16.4
```

* Here is the output:

```Rout
> x <- c(6.4,7.0,5.5,5.6,8.2,6.1,8.3,7.6,7.0,6.0,6.2,6.7,5.5,6.7,5.9)
> y <- c(17.7,18.0,18.0,15.8,18.8,16.2,19.9,18.4,19.0,17.3,17.5,17.7,15.4,17.7,15.5)
> ys <- c(16.6,17.1,18.7,14.2,17.9,16.7,19.7,19.9,18.4,17.0,15.9,17.7,16.3,16.8,16.4)
> d <- data.frame(x,y,ys)
> d
     x    y   ys
1  6.4 17.7 16.6
2  7.0 18.0 17.1
3  5.5 18.0 18.7
4  5.6 15.8 14.2
5  8.2 18.8 17.9
6  6.1 16.2 16.7
7  8.3 19.9 19.7
8  7.6 18.4 19.9
9  7.0 19.0 18.4
10 6.0 17.3 17.0
11 6.2 17.5 15.9
12 6.7 17.7 17.7
13 5.5 15.4 16.3
14 6.7 17.7 16.8
15 5.9 15.5 16.4
>
```

* Here are the regressions:

```Rout
> m1 <- lm(y~1+x)
> m2 <- lm(ys~1+x)
> summary(m1)

Call:
lm(formula = y ~ 1 + x)

Residuals:
     Min       1Q   Median       3Q      Max 
-1.22880 -0.60213  0.03253  0.40187  1.74053 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   9.8061     1.5649   6.266  2.9e-05 ***
x             1.1733     0.2357   4.977 0.000253 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.7996 on 13 degrees of freedom
Multiple R-squared:  0.6558,	Adjusted R-squared:  0.6293 
F-statistic: 24.77 on 1 and 13 DF,  p-value: 0.000253

> summary(m2)

Call:
lm(formula = ys ~ 1 + x)

Residuals:
     Min       1Q   Median       3Q      Max 
-2.02557 -0.62901 -0.06694  0.44616  2.58271 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  10.1621     2.2597   4.497  0.00060 ***
x             1.0828     0.3404   3.181  0.00723 ** 
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.155 on 13 degrees of freedom
Multiple R-squared:  0.4376,	Adjusted R-squared:  0.3944 
F-statistic: 10.12 on 1 and 13 DF,  p-value: 0.007232

>
```

* Here is the code to generate the 2 scatterplots:

```Rout
par(mfrow=c(1,2))
plot(x=x,y=y,pch=19)
abline(m1,lty=1,lwd=3,col="blue")
plot(x=x,y=ys,pch=19)
abline(m2,lty=1,lwd=3,col="blue")
```

<p align="center">
<img src="/gfiles/ysplots.png" width="600px">
</p>

* Despite some differences in the appearances of the two plots (in terms of *ys* versus *y*, not *x*), the substantive conclusions from the two scatterplots are virtually identical.
* This serves as an example of how *y* measured with random error reduces efficiency but does not induce bias (compared to estimation with the actual true *y*).

#### Topic 15 Begins Here

* One way we use regression models is to use information about an independent variable to make predictions about the dependent variable.
* The diffference between the predicted and actual values of the dependent variable is called a residual.
* Each observation in the dataset will have a residual (even if the residual is zero).
* Let's read in an example dataset (from the email I sent you).

```R
d <- read.csv(file="ih.csv",header=T,sep=",")
d

sum(d$p18)
sum(d$h18)

h <- (d$h18/d$p18)*100000
i <- d$i18/d$p18*100

par(mfrow=c(1,2))
hist(i,prob=T)
lines(density(i),lty=1,lwd=2,col="red")
hist(h,prob=T)
lines(density(h),lty=1,lwd=2,col="red")
```

* Here is the output:

```Rout
> d <- read.csv(file="ih.csv",header=T,sep=",")
> d
            state  h18  u18      p18     i18 moe18  h19  u19      p19
1         alabama  560   69  4887871   60000 10000  579   51  4903185
2          alaska   56   32   737438   10000  5000   76   27   731545
3         arizona  411  150  7171646  275000 20000  412  149  7278717
4        arkansas  257   61  3013825   70000  5000  264   60  3017804
5      california 1848  234 39557045 1950000 70000 1766  222 39512223
6        colorado  269   53  5695564  170000 20000  247   53  5758736
7     connecticut   87   32  3572665  140000 15000  109   23  3565287
8        delaware   53   NA   967171   30000 10000   50   NA   973764
9         florida 1319  146 21299325  800000 50000 1318  151 21477737
10        georgia  790   91 10519475  375000 25000  866   90 10617423
11         hawaii   40   15  1420491   45000 15000   37   25  1415872
12          idaho   36   22  1754208   40000 10000   24   21  1787065
13       illinois  970  162 12741080  400000 25000  941  146 12671821
14        indiana  467  141  6691878  110000 10000  436  150  6732219
15           iowa   79   39  3156145   55000 10000   79   30  3155070
16         kansas  154   53  2911505   75000 10000  131   27  2913314
17       kentucky  260   67  4468402   45000 10000  256   61  4467673
18      louisiana  601  102  4659978   70000 10000  636  107  4648794
19          maine   20   17  1338404    4999  3000   23   11  1344212
20       maryland  528 1782  6042718  275000 20000  580 1827  6045680
21  massachusetts  148   54  6902149  275000 25000  145   80  6892503
22       michigan  607  356  9995915  120000 25000  601  373  9986857
23      minnesota  122   56  5611179   85000 15000  150   70  5639632
24    mississippi  372   47  2986530   25000  5000  420   42  2976149
25       missouri  687   69  6126452   60000 15000  650   83  6137428
26        montana   43   24  1062305    4999  4000   38   23  1068778
27       nebraska   40   18  1929268   55000 10000   57   19  1934408
28         nevada  227   39  3034392  210000 15000  163   51  3080156
29  new hampshire   25   10  1356458   15000  5000   35   11  1359711
30     new jersey  292   77  8908520  425000 30000  265   50  8882190
31     new mexico  208   26  2095428   55000 10000  231   37  2096829
32       new york  587  309 19542209  600000 45000  581  310 19453561
33 north carolina  625   69 10383620  325000 15000  693   69 10488084
34   north dakota   23   15   760077    5000  5000   22   23   762062
35           ohio  748  110 11689442  110000 15000  718  117 11689100
36       oklahoma  262   86  3943079   90000 10000  338   71  3956971
37         oregon  107   63  4190713  110000 15000  122   39  4217737
38   pennsylvania  793  188 12807060  190000 25000  734  173 12801989
39   rhode island   18   19  1057315   35000 10000   26   14  1059361
40 south carolina  472   32  5084127   90000 10000  513   41  5148714
41   south dakota   26   NA   882235   10000  3000   30   10   884659
42      tennessee  624  107  6770010  130000 15000  631  119  6829174
43          texas 1517  228 28701845 1600000 55000 1672  258 28995881
44           utah   66   61  3161105  100000 10000   80   67  3205958
45        vermont   13   22   626299    4999  4000   12   14   623989
46       virginia  412   42  8517685  300000 20000  437   36  8535519
47     washington  264   88  7535591  300000 25000  238   94  7614893
48  west virginia   99   32  1805832    4999  3000   98   39  1792147
49      wisconsin  197   61  5813568   80000 15000  209   52  5822434
50        wyoming   19   NA   577737    5000  3000   21   NA   578759

       i19 moe19  h21  u21      p21     i21 moe21  h22  u22      p22
1    60000 10000  750   89  5039877   60000 10000  702   70  5074296
2    10000  5000   48   31   732673    5000  5000   74   31   733583
3   250000 25000  546  186  7276316  250000 20000  625  162  7359197
4    70000  5000  326   77  3025891   70000  5000  322   72  3045637
5  1900000 65000 2475  232 39237836 1850000 65000 2228  251 39029342
6   170000 15000  374   76  5812069  160000 15000  412   68  5839926
7   140000 15000  156   28  3605597  140000 20000  146   25  3626205
8    30000  5000   97   NA  1003384   30000 10000   58   NA  1018396
9   775000 40000 1477  181 21781128  900000 50000 1474  169 22244823
10  350000 25000 1212   84 10799566  350000 25000 1222  120 10912876
11   40000 15000   35   20  1441553   40000 10000   39   22  1440196
12   40000 10000   40   44  1900923   35000 10000   48   24  1939033
13  400000 30000 1434  125 12671469  400000 30000 1258  113 12582032
14  110000 15000  636  210  6805985  110000 15000  555  206  6833037
15   45000 10000   97   40  3193079   45000 10000   90   46  3200517
16   70000 10000  178   33  2934582   75000 10000  174   44  2937150
17   50000 10000  401   74  4509394   55000 10000  346   63  4512310
18   65000 10000  928  177  4624047   70000 10000  847  162  4590241
19    5000  4000   21   26  1376247    5000  5000   32   16  1385340
20  275000 20000  672 1772  6165129  275000 20000  593 1282  6164660
21  275000 25000  146   87  6984723  300000 20000  166  106  6981974
22  120000 20000  811  456 10050811  120000 20000  761  419 10034113
23   80000 20000  220   76  5707390   90000 20000  204   71  5717184
24   20000  5000  612   54  2949965   20000  5000  551   62  2940057
25   60000 15000  747   98  6168187   65000 10000  742  122  6177957
26    4999  4000   43   25  1104271    4999  3000   58   17  1122867
27   45000 10000   68   17  1963692   45000 10000   67   16  1967923
28  200000 20000  272   33  3143991  190000 15000  245   35  3177772
29   15000  5000   14   NA  1388992   15000  5000   25   NA  1395231
30  400000 30000  393   85  9267130  450000 30000  306   81  9261699
31   55000 10000  306   44  2115877   55000 10000  289   47  2113344
32  575000 55000  882  347 19835913  600000 45000  820  336 19677151
33  325000 20000  955  126 10551162  325000 15000  941   90 10698973
34    5000  5000   23   NA   774948    5000  5000   28   13   779261
35  110000 20000 1012  117 11780017  120000 15000  905  107 11756058
36   85000 10000  340   62  3986639   85000  5000  319   56  4019800
37  110000 15000  218   68  4246155  120000 15000  217   55  4240137
38  200000 25000 1098  149 12964056  220000 25000 1054  117 12972008
39   35000 10000   40   18  1095610   40000  5000   25   NA  1093734
40   90000 10000  644   47  5190705   95000 10000  578   43  5282634
41    5000  5000   43   NA   895376   10000  4000   55   NA   909824
42  130000 15000  844  126  6975218  140000 15000  760  127  7051339
43 1550000 55000 2370  279 29527941 1600000 60000 2277  251 30029572
44  100000 10000   90   63  3337975   95000 15000   76   60  3380800
45    4999  4000   NA   16   645570    4999  4000   24   18   647064
46  300000 20000  591   61  8642274  275000 20000  628   59  8683619
47  300000 25000  333  112  7738692  300000 25000  412  112  7785786
48    4999  3000  114   21  1782959    4999  3000  112   20  1775156
49   75000 15000  345   51  5895908   80000 15000  328   81  5892539
50    5000  3000   15   NA   578803    4999  3000   15   NA   581381

       i22 moe22
1    65000 10000
2    10000  5000
3   250000 20000
4    70000 10000
5  1800000 75000
6   170000 15000
7   150000 15000
8    25000  5000
9  1150000 50000
10  375000 25000
11   45000 15000
12   40000 10000
13  400000 30000
14  120000 15000
15   55000 10000
16   80000 10000
17   50000 10000
18   65000 10000
19    5000  5000
20  300000 20000
21  325000 20000
22  130000 20000
23   95000 20000
24   25000  5000
25   70000 10000
26    4999  4000
27   40000 10000
28  190000 15000
29   15000  5000
30  475000 30000
31   50000 10000
32  650000 45000
33  325000 20000
34   10000  4000
35  130000 15000
36   95000 10000
37  120000 15000
38  230000 30000
39   45000 10000
40   90000 10000
41   10000  4000
42  140000 15000
43 1650000 55000
44  110000 10000
45    4999  4000
46  275000 25000
47  325000 20000
48    5000  3000
49   80000 10000
50    5000  3000
> 
> sum(d$p18)
[1] 326464979
> sum(d$h18)
[1] 18448
> 
> h <- (d$h18/d$p18)*100000
> i <- d$i18/d$p18*100
> 
> par(mfrow=c(1,2))
> hist(i,prob=T)
> lines(density(i),lty=1,lwd=2,col="red")
> hist(h,prob=T)
> lines(density(h),lty=1,lwd=2,col="red")
>
```

<p align="center">
<img src="/gfiles/ih-hist.png" width="600px">
</p>

* Now, we will use our formulas to calculate the intercept and slope estimates (Sheather, pp. 18-19):

```
b1pt1 <- i-mean(i)
b1pt2 <- h-mean(h)
b1.num <- sum(b1pt1*b1pt2)
b1.pt3 <- (i-mean(i))^2
b1.den <- sum(b1.pt3)
b1 <- b1.num/b1.den
b1
b0 <- mean(h)-b1*mean(i)
b0
```

* Here are the estimates:

```Rout
> b1pt1 <- i-mean(i)
> b1pt2 <- h-mean(h)
> b1.num <- sum(b1pt1*b1pt2)
> b1.pt3 <- (i-mean(i))^2
> b1.den <- sum(b1.pt3)
> b1 <- b1.num/b1.den
> b1
[1] -0.1469111
> b0 <- mean(h)-b1*mean(i)
> b0
[1] 5.762181
>
```

* Now, we calculate predicted values and residuals (Sheather, sec. 2.1):

```R
yp <- b0+b1*i
r <- h-yp
```

* With these in hand, we can create a scatterplot and a residual plot (see below):

```R
par(mfrow=c(1,2))

# create a scatterplot with a regression line

plot(x=i,y=h,pch=19,xlim=c(0,8),ylim=c(0,14),
  xlab="% of Population Classified as Undocumented Immigrants",
  ylab="# of Homicides per 100,000 Population")
abline(a=b0,b=b1,lty=1,lwd=3,col="darkgreen")
abline(h=seq(from=0,to=14,by=0.5),lty=3,lwd=0.8)
abline(v=seq(from=0,to=8,by=0.5),lty=3,lwd=0.8)

# create a residual plot with a horizontal zero line

plot(x=i,y=r,pch=19,xlim=c(0,8),
  xlab="% of Population Classified as Undocumented Immigrants",
  ylab="homicide rate - predicted(homicide rate)")
abline(h=0,lty=1,lwd=3,col="darkgreen")
abline(h=seq(from=-4,to=7,by=0.5),lty=3,lwd=0.8)
abline(v=seq(from=0,to=8,by=0.5),lty=3,lwd=0.8)
```

* Here are the results:

<p align="center">
<img src="/gfiles/ih-scat.png" width="600px">
</p>

* Ideally, the points in the residual plot should be randomly scattered throughout the plotspace.
* We see that is not the case here as it appears the dispersion of the residuals is greater for small values of *i*.
* Next, we calculate the (root) mean square error and the standard errors of the parameter estimates:

```R
# calculate (root) mean square error of the regression (Sheather, p. 20)

N <- 50
sigsq.pt1 <- 1/(N-2)
sigsq.pt2 <- sum(r^2)
sigsq <- sigsq.pt1*sigsq.pt2
sigsq
sig <- sqrt(sigsq)
sig

# calculate standard error of the intercept (Sheather, sec. 2.2.3)

seb0.pt1 <- 1/N
seb0.pt2 <- mean(i)^2
seb0.pt3 <- sum((i-mean(i))^2)
seb0 <- sig*sqrt(seb0.pt1+seb0.pt2/seb0.pt3)
seb0

# calculate standard error of the slope (Sheather, sec. 2.2.2)

seb1.pt1 <- sum((i-mean(i))^2)
seb1.pt2 <- sqrt(seb1.pt1)
seb1 <- sig/seb1.pt2
seb1
```

* And the results are:

```Rout
> N <- 50
> sigsq.pt1 <- 1/(N-2)
> sigsq.pt2 <- sum(r^2)
> sigsq <- sigsq.pt1*sigsq.pt2
> sigsq
[1] 9.31581
> sig <- sqrt(sigsq)
> sig
[1] 3.052181
> 
> # calculate standard error of the intercept (Sheather, sec. 2.2.3)
> 
> seb0.pt1 <- 1/N
> seb0.pt2 <- mean(i)^2
> seb0.pt3 <- sum((i-mean(i))^2)
> seb0 <- sig*sqrt(seb0.pt1+seb0.pt2/seb0.pt3)
> seb0
[1] 0.8407883
> 
> # calculate standard error of the slope (Sheather, sec. 2.2.2)
> 
> seb1.pt1 <- sum((i-mean(i))^2)
> seb1.pt2 <- sqrt(seb1.pt1)
> seb1 <- sig/seb1.pt2
> seb1
[1] 0.2954161
>
```

* Once we have the standard errors, we can calculate our *t*-statistics:

```R
# calculate t-ratios and significance tests

t.b0 <- b0/seb0
t.b0

t.b1 <- b1/seb1
t.b1
```

* The results are:

```Rout
> t.b0 <- b0/seb0
> t.b0
[1] 6.853308
> 
> t.b1 <- b1/seb1
> t.b1
[1] -0.4973022
>
```

* To interpret these *t*-statistics, we draw a large number of random *t*-values from a *t*-distribution with 50-2=48 degrees of freedom.
* We will focus on the *t*-statistic for the slope in this example.
* This *t*-distribution gives us the expected sampling distribution of test statistics when the true population *t*-value (or slope) is equal to zero.

```R
# simulate tdistribution assuming a zero slope

tdist <- rt(n=1e7,df=N-2)
pvalue <- mean(ifelse(tdist<t.b1 | tdist>(-1*t.b1),1,0))
pvalue
```

* Now, with this simulated *t*-distribution, we can estimate the probability that we would get a *t*-statistic at least as large (two-tailed) as the one we got in our sample if the true population *t*-statistic (or slope) is equal to zero. This probability is called a *p*-value.
* Another way to say this is that we want to estimate p(t-stat in our sample is less than -0.497 or greater than 0.497|population t-stat=0).

```Rout
> pvalue <- mean(ifelse(tdist<t.b1 | tdist>(-1*t.b1),1,0))
> pvalue
[1] 0.6212581
```

* This tells us that it would not be unusual to get a sample *t*-statistic (or slope) at least as large as this one (two-tailed) is if the true population *t*-statistic (or slope) is equal to zero. We, therefore, fail to reject the hypothesis that the true population *t*-statistic (or slope) is equal to zero.
* Now, let's estimate the linear regression using the lm() function and save the key quantities from the analysis:

```R
# estimate linear regression with lm() function

m  <- lm(h~1+i)
summary(m)

# extract parameter estimates (using lm() output)

int <- coef(m)[1]
int
slope <- coef(m)[2]
slope
sig <- sigma(m)
sig

# extract standard errors (using lm() output)

vcov(m)
se.b0 <- sqrt(vcov(m)[1,1])
se.b0
se.b1 <- sqrt(vcov(m)[2,2])
se.b1
```

* Here are the results (please verify they are the same as what we calculated above; particularly the p-value for the slope coefficient):

```Rout
> # estimate linear regression with lm() function
> 
> m  <- lm(h~1+i)
> summary(m)

Call:
lm(formula = h ~ 1 + i)

Residuals:
    Min      1Q  Median      3Q     Max 
-4.2130 -2.6463 -0.1668  1.8877  7.3556 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   5.7622     0.8408   6.853 1.23e-08 ***
i            -0.1469     0.2954  -0.497    0.621    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 3.052 on 48 degrees of freedom
Multiple R-squared:  0.005126,	Adjusted R-squared:  -0.0156 
F-statistic: 0.2473 on 1 and 48 DF,  p-value: 0.6212

> 
> # extract parameter estimates (using lm() output)
> 
> int <- coef(m)[1]
> int
(Intercept) 
   5.762181 
> slope <- coef(m)[2]
> slope
         i 
-0.1469111 
> sig <- sigma(m)
> sig
[1] 3.052181
> 
> # extract standard errors (using lm() output)
> 
> vcov(m)
            (Intercept)           i
(Intercept)   0.7069250 -0.21315223
i            -0.2131522  0.08727066
> se.b0 <- sqrt(vcov(m)[1,1])
> se.b0
[1] 0.8407883
> se.b1 <- sqrt(vcov(m)[2,2])
> se.b1
[1] 0.2954161
>
```

* With this information in hand, we can now calculate confidence intervals for the intercept and slope, respectively.

```R
# 93% confidence interval for the intercept (Sheather, sec. 2.2.3)

int+qt(0.035,df=N-2)*se.b0
int+qt(1-0.035,df=N-2)*se.b0

# 88% confidence interval for the slope (Sheather, sec. 2.2.2)

slope+qt(0.06,df=N-2)*se.b1
slope+qt(1-0.06,df=N-2)*se.b1
```

* And we get the following results:

```Rout
> # 93% confidence interval for the intercept (Sheather, sec. 2.2.3)
> 
> int+qt(0.035,df=N-2)*se.b0
(Intercept) 
   4.203997 
> int+qt(1-0.035,df=N-2)*se.b0
(Intercept) 
   7.320364 
> 
> # 88% confidence interval for the slope (Sheather, sec. 2.2.2)
> 
> slope+qt(0.06,df=N-2)*se.b1
         i 
-0.6145403 
> slope+qt(1-0.06,df=N-2)*se.b1
        i 
0.3207182 
>
```

* This tells us that the 93% confidence interval for the intercept *does not* include zero.
* But the 88% confidence interval for the slope does include zero (which is consistent with our decision above when we failed to reject Ho).

### Assignment #2 (Due on ELMS at 11:59pm on Tuesday 3/25/25)

Instructions: please review the guidelines for assignments and submission of assignments in the syllabus above. You should not discuss this assignment with others; the work you submit should be your own work. If I receive questions related to the assignment that I judge to be of interest to the entire class, I will post them below with the answers. I will respond to all questions submitted by 11:59pm (ET) on Saturday 3/22/25. I will not be able to respond to any questions received after that time (so that all students will have ample time to take such questions into consideration before the submission deadline). Each problem below is worth 5 points. Good luck!

Part I: Use the following dataset where we have 2 versions of *x* (x is well measured and xs is measured with error).

```Rout
> x
 [1]  8.1  9.7  9.7  9.9  8.9  9.1  9.1 10.2  9.7  8.1
> xs
 [1]  8.3 10.3  9.8 10.3  8.6  9.1  9.7 11.1  9.2  9.2
> y
 [1]  8.9  8.9  9.8 10.6  7.9  8.4  9.6  9.4 11.8  9.3
>
```

1. Use your formulas to calculate regressions of *y* on *x* and *y* on *xs* (just the intercept and slope estimates). Verify you get the same results using lm().
2. Create a scatterplot to go with each regression. Be sure to include the regression line for each scatterplot.
3. Calculate a 75% confidence interval for the slope coefficients in each regression.
4. What decision do you make concerning Ho that the population slope is equal to zero for each regression (at the 75% confidence level)? 
5. Explain how measurement error might be affecting the results that you see in the two regression analyses.
6. If *x* is a measure of sentence severity and *y* is a measure of future criminal behavior, why would it be problematic to interpret the results of the regression analysis as evidence of a causal effect of *x* on *y*? Desribe an example of what could go wrong.

Part II: For this assignment, you will be using the homicide dataset I sent at the beginning of the last class; *i* refers to the estimated fraction of undocumented immigrants in the population; *h* refers to the number of homicides per 100,000 population.

1. Use the cor.test() function to calculate a 93% confidence interval for the correlation between *i* and *h* for the year 2018.
2. Standardize *i* and *h* for 2018 (mean zero and standard deviation one) and estimate a linear regression with *h* as the outcome.
3. Calculate a 93% confidence interval for the slope coefficient in the regression you estimated in #2. Verify agreement with #1 above.
4. Calculate the correlation between undocumented immigration rates (i) and homicide rates (h) for the year 2019.
5. Create a scatterplot showing the regression line for *i* and *h* in the year 2019.
6. What is the 87% confidence interval for the correlation coefficient of *i* and *h* in 2019? 
7. If Ho is that the 2019 correlation between *i* and *h* is equal to zero, do you reject or fail to reject Ho (at the 87% confidence level)? What is the basis for your decision?
8. Use your formulas to calculate the intercept and slope of the 2019 regression of *h* on *i*.
9. Use your formulas to calculate the standard errors and *t*-statistics for the intercept and slope in #8.
10. Verify that your results in #8 and #9 agree with the summary printout from the lm() function.
11. Based on the regression in #10, calculate the expected value of *h* when *i* takes on the values: 1,2,3,4,5, and 6.
12. Using your results in #11, what is E(h|i=5)-E(h|i=4)? How does this number compare to the slope coefficient you estimated in #8 and #11?
13. What is the *p*-value for the slope *t*-statistic you estimated in #9? How does it compare to the *p*-value for the slope coefficient on the lm() printout in #10 above?
14. Create a residual plot for your 2019 regression. Do you see anything that concerns you?

### Lesson 8 - Monday 3/24/25

* Reminder: Assignment #2 is due tomorrow at 11:59pm on ELMS.
* Tonight, we finish topic 15 and also cover topics 16.

#### Topic 15: Residuals/Prediction Errors (Continued)

* We begin by reading in the ih.csv dataset I sent 2 weeks ago.
* Here is the R code to read the dataset:

```R
d <- read.csv(file="ih.csv",header=T,sep=",")

sum(d$p18)
sum(d$h18)

state <- d$state

h <- (d$h18/d$p18)*100000
i <- d$i18/d$p18*100
h
i
```

* Here is the output:

```Rout
> d <- read.csv(file="ih.csv",header=T,sep=",")
> 
> sum(d$p18)
[1] 326464979
> sum(d$h18)
[1] 18448
> 
> state <- d$state
> 
> h <- (d$h18/d$p18)*100000
> i <- d$i18/d$p18*100
> h
 [1] 11.456931  7.593859  5.730902  8.527370  4.671734  4.722974
 [7]  2.435157  5.479900  6.192685  7.509880  2.815928  2.052208
[13]  7.613169  6.978609  2.503054  5.289361  5.818635 12.897057
[19]  1.494317  8.737790  2.144260  6.072481  2.174231 12.455927
[25] 11.213668  4.047802  2.073325  7.480906  1.843035  3.277761
[31]  9.926373  3.003755  6.019095  3.026009  6.398937  6.644554
[37]  2.553265  6.191897  1.702425  9.283796  2.947061  9.217121
[43]  5.285375  2.087877  2.075686  4.836995  3.503375  5.482238
[49]  3.388625  3.288694
> i
 [1] 1.2275283 1.3560462 3.8345451 2.3226299 4.9295897 2.9847790
 [7] 3.9186434 3.1018300 3.7559876 3.5648167 3.1679187 2.2802313
[13] 3.1394513 1.6437837 1.7426322 2.5759873 1.0070714 1.5021530
[19] 0.3735046 4.5509322 3.9842663 1.2004904 1.5148332 0.8370919
[25] 0.9793597 0.4705805 2.8508222 6.9206615 1.1058212 4.7707139
[31] 2.6247621 3.0702773 3.1299296 0.6578281 0.9410201 2.2824803
[37] 2.6248517 1.4835567 3.3102718 1.7702154 1.1334848 1.9202335
[43] 5.5745545 3.1634508 0.7981811 3.5220838 3.9811078 0.2768253
[49] 1.3760912 0.8654457
>
```

* Now, let's estimate a linear regression model (regressing h on i):

```R
M <- lm(h~1+i)
summary(M)
a <- coef(M)[1]
a
b <- coef(M)[2]
b
s <- sigma(M)
s
```

* Here is our output:

```Rout
> M <- lm(h~1+i)
> summary(M)

Call:
lm(formula = h ~ 1 + i)

Residuals:
    Min      1Q  Median      3Q     Max 
-4.2130 -2.6463 -0.1668  1.8877  7.3556 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   5.7622     0.8408   6.853 1.23e-08 ***
i            -0.1469     0.2954  -0.497    0.621    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 3.052 on 48 degrees of freedom
Multiple R-squared:  0.005126,	Adjusted R-squared:  -0.0156 
F-statistic: 0.2473 on 1 and 48 DF,  p-value: 0.6212

> a <- coef(M)[1]
> a
(Intercept) 
   5.762181 
> b <- coef(M)[2]
> b
         i 
-0.1469111 
> s <- sigma(M)
> s
[1] 3.052181
>
```

* Estimate residuals:

```R
yp <- a+b*i
r <- h-yp
r
residuals(M)
```

* Here are the residual calculations:

```Rout
> yp <- a+b*i
> r <- h-yp
> r
 [1]  5.87508746  2.03089606  0.53205819  3.10640887 -0.36623539
 [6] -0.60070992 -2.75133184  0.17341190  0.98229978  2.27141064
[11] -2.48085082 -3.37498148  2.31220864  1.45791814 -3.00311535
[16] -0.09437917  0.20440400  7.35555862 -4.21299181  3.64419129
[21] -3.03258834  0.48666506 -3.36540400  6.81672430  5.59536610
[26] -1.64524568 -3.27003832  2.73544647 -3.75668819 -1.78354914
[31]  4.54979877 -2.30736857  0.71673589 -2.63952944  0.77500214
[36]  1.21769440 -2.82329631  0.64766731 -3.57343983  3.78167977
[41] -2.64859882  3.73704348  0.34215740 -3.20955745 -3.56923335
[46] -0.40775276 -1.67393723 -0.23927462 -2.17139316 -2.34634368
> residuals(M)
          1           2           3           4           5 
 5.87508746  2.03089606  0.53205819  3.10640887 -0.36623539 
          6           7           8           9          10 
-0.60070992 -2.75133184  0.17341190  0.98229978  2.27141064 
         11          12          13          14          15 
-2.48085082 -3.37498148  2.31220864  1.45791814 -3.00311535 
         16          17          18          19          20 
-0.09437917  0.20440400  7.35555862 -4.21299181  3.64419129 
         21          22          23          24          25 
-3.03258834  0.48666506 -3.36540400  6.81672430  5.59536610 
         26          27          28          29          30 
-1.64524568 -3.27003832  2.73544647 -3.75668819 -1.78354914 
         31          32          33          34          35 
 4.54979877 -2.30736857  0.71673589 -2.63952944  0.77500214 
         36          37          38          39          40 
 1.21769440 -2.82329631  0.64766731 -3.57343983  3.78167977 
         41          42          43          44          45 
-2.64859882  3.73704348  0.34215740 -3.20955745 -3.56923335 
         46          47          48          49          50 
-0.40775276 -1.67393723 -0.23927462 -2.17139316 -2.34634368 
>
```

* Now, we create 2 scatterplots:

```R
# plot 1: joint distribution of i and h
# plot 2: joint distribution of i and r(h)
# create a scatterplot with a regression line

par(mfrow=c(1,2))
plot(x=i,y=h,pch=19,xlim=c(0,8),ylim=c(0,14),
  xlab="% of Population Classified as Undocumented Immigrants",
  ylab="# of Homicides per 100,000 Population")
abline(a=a,b=b,lty=1,lwd=3,col="darkgreen")
abline(h=seq(from=0,to=14,by=0.5),lty=3,lwd=0.8)
abline(v=seq(from=0,to=8,by=0.5),lty=3,lwd=0.8)

# create a residual plot with a horizontal zero line

plot(x=i,y=r,pch=19,xlim=c(0,8),
  xlab="% of Population Classified as Undocumented Immigrants",
  ylab="homicide rate - predicted(homicide rate)")
abline(h=0,lty=1,lwd=3,col="darkgreen")
abline(h=seq(from=-4,to=7,by=0.5),lty=3,lwd=0.8)
abline(v=seq(from=0,to=8,by=0.5),lty=3,lwd=0.8)
```

* Here are the plots:

<p align="center">
<img src="/gfiles/hp1.png" width="800px">
</p>

* For a properly specified model, we want the residuals to appear randomly scattered about the plotspace.
* We definitely don't have that here.

#### Topic 16: Heteroscedasticity

* For the first part of our treatment of heteroscedasticity, we will work with simulated data:

```R
set.seed(984)

g <- c(rep(0,2500),rep(1,500))
y <- 10+g+rnorm(n=3000,mean=0,sd=1+2*g)
M <- lm(y~1+g)
summary(M)
```

* Here is the regression model for a sample of 3000 observations:

```Rout
> set.seed(984)
> 
> g <- c(rep(0,2500),rep(1,500))
> y <- 10+g+rnorm(n=3000,mean=0,sd=1+2*g)
> M <- lm(y~1+g)
> summary(M)

Call:
lm(formula = y ~ 1 + g)

Residuals:
    Min      1Q  Median      3Q     Max 
-8.7899 -0.7083  0.0286  0.7290  8.9911 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 10.02602    0.02854  351.31   <2e-16 ***
g            1.02545    0.06991   14.67   <2e-16 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.427 on 2998 degrees of freedom
Multiple R-squared:  0.06697,	Adjusted R-squared:  0.06665 
F-statistic: 215.2 on 1 and 2998 DF,  p-value: < 2.2e-16

>
```

* Based on this model, we will do some additional residual calculations (based on Sheather, pp. 56 and 59):

```R
a <- coef(M)[1]
b <- coef(M)[2]
s <- sigma(M)
yp <- a+b*g
r <- y-yp
h1 <- 1/3000
h2 <- (g-mean(g))^2
h3 <- sum((g-mean(g))^2)
h <- h1*(h2/h3)
sr <- r/(s*sqrt(1-h))
```

* Let's create 2 boxplots:

```R
par(mfrow=c(1,2))
boxplot(y~g,names=c("g=0","g=1"))
boxplot(sqrt(abs(sr))~g,names=c("g=0","g=1"))
```

which gives us these 2 charts:

<p align="center">
<img src="/gfiles/hp2.png" width="800px">
</p>

* Calculate a 92% confidence interval for the slope coefficient:

```R
# calculate t-values for a 92% confidence interval
# so we can check on confidence interval performance
# for the slope coefficient under repeated sampling

tmult.lcl <- qt(p=0.04,df=3000-2)
tmult.lcl
tmult.ucl <- qt(p=0.96,df=3000-2)
tmult.ucl

vcov(M)
se.slope <- sqrt(vcov(M)[2,2])
b+tmult.lcl*se.slope
b+tmult.ucl*se.slope
```

* Here is our output:

```Rout
> tmult.lcl <- qt(p=0.04,df=3000-2)
> tmult.lcl
[1] -1.75128
> tmult.ucl <- qt(p=0.96,df=3000-2)
> tmult.ucl
[1] 1.75128
> 
> vcov(M)
              (Intercept)             g
(Intercept)  0.0008144961 -0.0008144961
g           -0.0008144961  0.0048869767
> se.slope <- sqrt(vcov(M)[2,2])
> b+tmult.lcl*se.slope
        g 
0.9030223 
> b+tmult.ucl*se.slope
       g 
1.147875 
>
```

* Now, we can diagnose heteroscedasticity (quantitatively) by:

```R
hdv <- sqrt(abs(sr))
hm <- lm(hdv~1+g)
summary(hm)
library(lmtest)
bptest(M)
```

which gives us the following output:

```Rout
> hdv <- sqrt(abs(sr))
> hm <- lm(hdv~1+g)
> summary(hm)

Call:
lm(formula = hdv ~ 1 + g)

Residuals:
     Min       1Q   Median       3Q      Max 
-1.12157 -0.23312 -0.00436  0.21736  1.35685 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  0.66719    0.00654  102.01   <2e-16 ***
g            0.48610    0.01602   30.34   <2e-16 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.327 on 2998 degrees of freedom
Multiple R-squared:  0.2349,	Adjusted R-squared:  0.2347 
F-statistic: 920.6 on 1 and 2998 DF,  p-value: < 2.2e-16

> library(lmtest)
> bptest(M)

	studentized Breusch-Pagan test

data:  M
BP = 693.15, df = 1, p-value < 2.2e-16

>
```

* Once we have evidence of heteroscedasticity, one step that is often taken is to estimate White's heteroscedasticity consistent covariance matrix:

```R
library(sandwich)
H <- vcovHC(M)
summary(M)
a.se <- sqrt(H[1,1])
a.se
b.se <- sqrt(H[2,2])
b.se
a/a.se
b/b.se
```

* which gives us the following output:

```Rout
> library(sandwich)
> H <- vcovHC(M)
> summary(M)

Call:
lm(formula = y ~ 1 + g)

Residuals:
    Min      1Q  Median      3Q     Max 
-8.7899 -0.7083  0.0286  0.7290  8.9911 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 10.02602    0.02854  351.31   <2e-16 ***
g            1.02545    0.06991   14.67   <2e-16 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.427 on 2998 degrees of freedom
Multiple R-squared:  0.06697,	Adjusted R-squared:  0.06665 
F-statistic: 215.2 on 1 and 2998 DF,  p-value: < 2.2e-16

> a.se <- sqrt(H[1,1])
> a.se
[1] 0.0190963
> b.se <- sqrt(H[2,2])
> b.se
[1] 0.1254403
>
> a/a.se
(Intercept) 
   525.0242 
> b/b.se
       g 
8.174799 
>
```

* Note that the standard error of the slope is nearly 2x larger after adjusting for heteroscedasticity.
* How do we know this works or is accurate?

```
# calculate t-values for a 92% confidence interval
# so we can check on confidence interval performance
# for the slope coefficient under repeated sampling

tmult.lcl <- qt(p=0.04,df=3000-2)
tmult.lcl
tmult.ucl <- qt(p=0.96,df=3000-2)
tmult.ucl

bvec <- vector()
se.bvec <- vector()
b.lcl <- vector()
b.ucl <- vector()

for(i in 1:1e4){
  ys <- 10+g+rnorm(n=3000,mean=0,sd=1+2*g)
  Mwh <- lm(ys~1+g)
  H <- vcovHC(Mwh)
  bvec[i] <- coef(Mwh)[2]
  se.bvec[i] <- sqrt(H[2,2])
  b.lcl[i] <- bvec[i]+tmult.lcl*se.bvec[i]
  b.ucl[i] <- bvec[i]+tmult.ucl*se.bvec[i]
  }

mean(bvec)
sd(bvec)
mean(se.bvec)
mean(ifelse(b.lcl<1 & b.ucl>1,1,0))
```

* Here is our output:

```Rout
> # calculate t-values for a 92% confidence interval
> # so we can check on confidence interval performance
> # for the slope coefficient under repeated sampling
> 
> tmult.lcl <- qt(p=0.04,df=3000-2)
> tmult.lcl
[1] -1.75128
> tmult.ucl <- qt(p=0.96,df=3000-2)
> tmult.ucl
[1] 1.75128
> 
> bvec <- vector()
> se.bvec <- vector()
> b.lcl <- vector()
> b.ucl <- vector()
> 
> for(i in 1:1e4){
+   ys <- 10+g+rnorm(n=3000,mean=0,sd=1+2*g)
+   Mwh <- lm(ys~1+g)
+   H <- vcovHC(Mwh)
+   bvec[i] <- coef(Mwh)[2]
+   se.bvec[i] <- sqrt(H[2,2])
+   b.lcl[i] <- bvec[i]+tmult.lcl*se.bvec[i]
+   b.ucl[i] <- bvec[i]+tmult.ucl*se.bvec[i]
+   }
> 
> mean(bvec)
[1] 1.000479
> sd(bvec)
[1] 0.1353162
> mean(se.bvec)
[1] 0.1357184
> mean(ifelse(b.lcl<1 & b.ucl>1,1,0))
[1] 0.9219
>
```

* What would happen if we just used the standard linear model with no adjustment?

```R
bvec     <- vector()
se.bvec  <- vector()
b.lcl    <- vector()
b.ucl    <- vector()

for(i in 1:1e4){
  ys <- 10+g+rnorm(n=3000,mean=0,sd=1+2*g)
  Ms <- lm(ys~1+g)
  bvec[i] <- coef(Ms)[2]
  se.bvec[i] <- sqrt(vcov(Ms)[2,2])
  b.lcl[i] <- bvec[i]+tmult.lcl*se.bvec[i]
  b.ucl[i] <- bvec[i]+tmult.ucl*se.bvec[i]
  }

mean(bvec)
sd(bvec)
mean(se.bvec)
mean(ifelse(b.lcl<1 & b.ucl>1,1,0))
```

* Here is the (misspecified) output:

```Rout
> bvec     <- vector()
> se.bvec  <- vector()
> b.lcl    <- vector()
> b.ucl    <- vector()
> 
> for(i in 1:1e4){
+   ys <- 10+g+rnorm(n=3000,mean=0,sd=1+2*g)
+   Ms <- lm(ys~1+g)
+   bvec[i] <- coef(Ms)[2]
+   se.bvec[i] <- sqrt(vcov(Ms)[2,2])
+   b.lcl[i] <- bvec[i]+tmult.lcl*se.bvec[i]
+   b.ucl[i] <- bvec[i]+tmult.ucl*se.bvec[i]
+   }
> 
> mean(bvec)
[1] 0.9993553
> sd(bvec)
[1] 0.1351043
> mean(se.bvec)
[1] 0.07477787
> mean(ifelse(b.lcl<1 & b.ucl>1,1,0))
[1] 0.6662
>
```

* We could also use weighted least squares (Sheather Chapter 4).
* 2 different approaches could be used.
* Approach 1:

```R
# calculate weighted least squares estimates
# of the slope and intercept

wt <- 1/((g*sd(y[g==1])+(1-g)*sd(y[g==0]))^2)
table(wt)

xbar.wt <- sum(wt*g)/sum(wt)
ybar.wt <- sum(wt*y)/sum(wt)
bpt1 <- sum(wt*(g-xbar.wt)*(y-ybar.wt))
bpt2 <- sum(wt*(g-xbar.wt)^2)
bw <- bpt1/bpt2
bw
aw <- ybar.wt-bw*xbar.wt
aw
summary(lm(y~1+g,weights=wt))

bvec <- vector()
se.bvec <- vector()
b.lcl <- vector()
b.ucl <- vector()

for(i in 1:1e4){
  ys <- 10+g+rnorm(n=3000,mean=0,sd=1+2*g)
  wt <- 1/((g*sd(y[g==1])+(1-g)*sd(y[g==0]))^2)  
  Ms <- lm(ys~1+g,weights=wt)
  bvec[i] <- coef(Ms)[2]
  se.bvec[i] <- sqrt(vcov(Ms)[2,2])
  b.lcl[i] <- bvec[i]+tmult.lcl*se.bvec[i]
  b.ucl[i] <- bvec[i]+tmult.ucl*se.bvec[i]
  }

mean(bvec)
sd(bvec)
mean(se.bvec)
mean(ifelse(b.lcl<1 & b.ucl>1,1,0))
```

* Here is the output for Approach #1:

```Rout
> # calculate weighted least squares estimates
> # of the slope and intercept
> 
> wt <- 1/((g*sd(y[g==1])+(1-g)*sd(y[g==0]))^2)
> table(wt)
wt
0.130379389246642  1.09732500219079 
              500              2500 
> 
> xbar.wt <- sum(wt*g)/sum(wt)
> ybar.wt <- sum(wt*y)/sum(wt)
> bpt1 <- sum(wt*(g-xbar.wt)*(y-ybar.wt))
> bpt2 <- sum(wt*(g-xbar.wt)^2)
> bw <- bpt1/bpt2
> bw
[1] 1.025449
> aw <- ybar.wt-bw*xbar.wt
> aw
[1] 10.02602
> summary(lm(y~1+g,weights=wt))

Call:
lm(formula = y ~ 1 + g, weights = wt)

Weighted Residuals:
    Min      1Q  Median      3Q     Max 
-3.2596 -0.6541  0.0234  0.6734  3.5521 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 10.02602    0.01909 525.129  < 2e-16 ***
g            1.02545    0.12532   8.183 4.05e-16 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1 on 2998 degrees of freedom
Multiple R-squared:  0.02185,	Adjusted R-squared:  0.02152 
F-statistic: 66.96 on 1 and 2998 DF,  p-value: 4.052e-16

> 
> bvec <- vector()
> se.bvec <- vector()
> b.lcl <- vector()
> b.ucl <- vector()
> 
> for(i in 1:1e4){
+   ys <- 10+g+rnorm(n=3000,mean=0,sd=1+2*g)
+   wt <- 1/((g*sd(y[g==1])+(1-g)*sd(y[g==0]))^2)  
+   Ms <- lm(ys~1+g,weights=wt)
+   bvec[i] <- coef(Ms)[2]
+   se.bvec[i] <- sqrt(vcov(Ms)[2,2])
+   b.lcl[i] <- bvec[i]+tmult.lcl*se.bvec[i]
+   b.ucl[i] <- bvec[i]+tmult.ucl*se.bvec[i]
+   }
> 
> mean(bvec)
[1] 1.000876
> sd(bvec)
[1] 0.1350008
> mean(se.bvec)
[1] 0.1320025
> mean(ifelse(b.lcl<1 & b.ucl>1,1,0))
[1] 0.9147
>
```

* And here is approach #2:

```R
bvec <- vector()
se.bvec <- vector()
b.lcl <- vector()
b.ucl <- vector()

for(i in 1:1e4){
  ys <- 10+g+rnorm(n=3000,mean=0,sd=1+2*g)
  Ms <- lm(ys~1+g)
  rsq <- residuals(Ms)^2
  vf <- lm(rsq~1+g)
  vhat <- vf$fitted.values
  wt <- 1/vhat
  Mw <- lm(ys~1+g,weights=wt)
  bvec[i] <- coef(Mw)[2]
  se.bvec[i] <- sqrt(vcov(Mw)[2,2])
  b.lcl[i] <- bvec[i]+tmult.lcl*se.bvec[i]
  b.ucl[i] <- bvec[i]+tmult.ucl*se.bvec[i]
  }

mean(bvec)
sd(bvec)
mean(se.bvec)
mean(ifelse(b.lcl<1 & b.ucl>1,1,0))
```

* And the output is:

```Rout
> bvec <- vector()
> se.bvec <- vector()
> b.lcl <- vector()
> b.ucl <- vector()
> 
> for(i in 1:1e4){
+   ys <- 10+g+rnorm(n=3000,mean=0,sd=1+2*g)
+   Ms <- lm(ys~1+g)
+   rsq <- residuals(Ms)^2
+   vf <- lm(rsq~1+g)
+   vhat <- vf$fitted.values
+   wt <- 1/vhat
+   Mw <- lm(ys~1+g,weights=wt)
+   bvec[i] <- coef(Mw)[2]
+   se.bvec[i] <- sqrt(vcov(Mw)[2,2])
+   b.lcl[i] <- bvec[i]+tmult.lcl*se.bvec[i]
+   b.ucl[i] <- bvec[i]+tmult.ucl*se.bvec[i]
+   }
> 
> mean(bvec)
[1] 0.9991085
> sd(bvec)
[1] 0.1350936
> mean(se.bvec)
[1] 0.1354713
> mean(ifelse(b.lcl<1 & b.ucl>1,1,0))
[1] 0.9223
>
```

* Let's go back to our immigration/homicide dataset:

```R
d <- read.csv(file="ih.csv",header=T,sep=",")

sum(d$p18)
sum(d$h18)

state <- d$state

h <- (d$h18/d$p18)*100000
i <- d$i18/d$p18*100

M <- lm(h~1+i)
summary(M)
library(lmtest)
bptest(M)
library(sandwich)
H <- vcovHC(M)
a <- coef(M)[1]
b <- coef(M)[2]
a.se <- sqrt(H[1,1])
a.se
b.se <- sqrt(H[2,2])
b.se
a/a.se
b/b.se
```

* Here is our output:

```Rout
> d <- read.csv(file="ih.csv",header=T,sep=",")
> 
> sum(d$p18)
[1] 326464979
> sum(d$h18)
[1] 18448
> 
> state <- d$state
> 
> h <- (d$h18/d$p18)*100000
> i <- d$i18/d$p18*100
> 
> M <- lm(h~1+i)
> summary(M)

Call:
lm(formula = h ~ 1 + i)

Residuals:
    Min      1Q  Median      3Q     Max 
-4.2130 -2.6463 -0.1668  1.8877  7.3556 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   5.7622     0.8408   6.853 1.23e-08 ***
i            -0.1469     0.2954  -0.497    0.621    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 3.052 on 48 degrees of freedom
Multiple R-squared:  0.005126,	Adjusted R-squared:  -0.0156 
F-statistic: 0.2473 on 1 and 48 DF,  p-value: 0.6212

> library(lmtest)
Loading required package: zoo

Attaching package: ‘zoo’

The following objects are masked from ‘package:base’:

    as.Date, as.Date.numeric

> bptest(M)

	studentized Breusch-Pagan test

data:  M
BP = 3.8473, df = 1, p-value = 0.04983

> library(sandwich)
> H <- vcovHC(M)
> a <- coef(M)[1]
> b <- coef(M)[2]
> a.se <- sqrt(H[1,1])
> a.se
[1] 0.9573978
> b.se <- sqrt(H[2,2])
> b.se
[1] 0.2932637
> a/a.se
(Intercept) 
   6.018586 
> b/b.se
         i 
-0.5009522 
> 
```

* Based on these results, it looks like heteroscedasticity is a legitimate concern (significant bptest result and visual evidence of unequal error variance) yet adjustments for it did not have a large effect on our substantive conclusions.

### Lesson 9 - Monday 3/31/25

* Last week, I asked you to look at the 2019 data to investigate heteroscedasticity.
* Let's work through that now.

```R
d <- read.csv(file="ih.csv",header=T,sep=",")

sum(d$p19)
sum(d$h19)

state <- d$state

h <- (d$h19/d$p19)*100000
i <- d$i19/d$p19*100

M <- lm(h~1+i)
summary(M)
sr <- rstandard(M)
ysr <- sqrt(abs(sr))
RM <- lm(ysr~1+i)
RM
```

* Here is our output:

```Rout
> d <- read.csv(file="ih.csv",header=T,sep=",")
> 
> sum(d$p19)
[1] 327533774
> sum(d$h19)
[1] 18760
> 
> state <- d$state
> 
> h <- (d$h19/d$p19)*100000
> i <- d$i19/d$p19*100
> 
> M <- lm(h~1+i)
> summary(M)

Call:
lm(formula = h ~ 1 + i)

Residuals:
    Min      1Q  Median      3Q     Max 
-4.3616 -2.6326 -0.3897  1.8317  8.1135 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   6.1643     0.8957   6.882 1.11e-08 ***
i            -0.2465     0.3265  -0.755    0.454    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 3.264 on 48 degrees of freedom
Multiple R-squared:  0.01174,	Adjusted R-squared:  -0.008847 
F-statistic: 0.5703 on 1 and 48 DF,  p-value: 0.4538

> sr <- rstandard(M)
> ysr <- sqrt(abs(sr))
> RM <- lm(ysr~1+i)
> RM

Call:
lm(formula = ysr ~ 1 + i)

Coefficients:
(Intercept)            i  
    0.97906     -0.06337
```

* Now, we create 3 diagnostic plots:

```R
par(mfrow=c(1,3))

# fitted regression line plot

plot(x=i,y=h,pch=19,ylim=c(0,15),xlim=c(0,7))
abline(M,lty=1,lwd=3,col="darkgreen")
abline(v=seq(from=0,to=7,by=1),lty=3,lwd=0.8)
abline(h=seq(from=0,to=14,by=1),lty=3,lwd=0.8)

# residual plot

plot(x=i,y=residuals(M),pch=19,xlim=c(0,7))
abline(h=0,lty=1,lwd=3,col="darkgreen")
abline(v=seq(from=0,to=7,by=1),lty=3,lwd=0.8)
abline(h=seq(from=-4,to=8,by=1),lty=3,lwd=0.8)

# standardized residual plot

plot(x=i,y=ysr,pch=19,xlim=c(0,7))
abline(RM,lty=1,lwd=3,col="darkgreen")
abline(v=seq(from=0,to=7,by=1),lty=3,lwd=0.8)
abline(h=seq(from=0,to=1.6,by=0.1),lty=3,lwd=0.8)
```

* Which gives us these plots (the 3rd plot is similar to the one on page 74 in Sheather's book):
  
<p align="center">
<img src="/gfiles/h2019a.png" width="900px">
</p>

* Next, we calculate the Breusch-Pagan test.
* Ho: no heteroscedasiticity.

```R
library(lmtest)
bptest(M)
```

* In this case, we reject Ho:

```Rout
> library(lmtest)
Loading required package: zoo

Attaching package: ‘zoo’

The following objects are masked from ‘package:base’:

    as.Date, as.Date.numeric

> bptest(M)

	studentized Breusch-Pagan test

data:  M
BP = 4.7845, df = 1, p-value = 0.02872

>
```

* So, we reject Ho (at the 0.03 significance level).
* With these results in hand, we calculate Halbert White's heteroscedasticity-consistent variance-covariance matrix:

```R
library(sandwich)
H <- vcovHC(M)
a <- coef(M)[1]
b <- coef(M)[2]
a.se <- sqrt(H[1,1])
a.se
b.se <- sqrt(H[2,2])
b.se

# let's review the original model summary and combine with
# White's corrected standard errors

summary(M)
a/a.se
b/b.se
```

* Here is our output:

```Rout
> library(sandwich)
> H <- vcovHC(M)
> a <- coef(M)[1]
> b <- coef(M)[2]
> a.se <- sqrt(H[1,1])
> a.se
[1] 1.010112
> b.se <- sqrt(H[2,2])
> b.se
[1] 0.3008508
> 
> 
> summary(M)

Call:
lm(formula = h ~ 1 + i)

Residuals:
    Min      1Q  Median      3Q     Max 
-4.3616 -2.6326 -0.3897  1.8317  8.1135 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   6.1643     0.8957   6.882 1.11e-08 ***
i            -0.2465     0.3265  -0.755    0.454    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 3.264 on 48 degrees of freedom
Multiple R-squared:  0.01174,	Adjusted R-squared:  -0.008847 
F-statistic: 0.5703 on 1 and 48 DF,  p-value: 0.4538

> a/a.se
(Intercept) 
    6.10262 
> b/b.se
         i 
-0.8194828 
> 
```

* So, we do have evidence of heteroscedasticity; after correcting for it, the standard error of the slope coefficient decreases slightly.
* Let's estimate a 82% confidence interval for the slope -- with and without the correction.

```R
# calculate t-multipliers for 82% confidence interval

tmult.lcl <- qt(p=0.09,df=50-2)
tmult.lcl
tmult.ucl <- qt(p=0.91,df=50-2)
tmult.ucl

# lower and upper confidence limits 
# uncorrected standard error

b+tmult.lcl*sqrt(vcov(M)[2,2])
b+tmult.ucl*sqrt(vcov(M)[2,2])

# lower and upper confidence limits for 
# corrected standard error

b+tmult.lcl*sqrt(H[2,2])
b+tmult.ucl*sqrt(H[2,2])
```

* Here is our output:

```Rout
> # lower and upper confidence limits 
> # uncorrected standard error
> 
> b+tmult.lcl*sqrt(vcov(M)[2,2])
         i 
-0.6907349 
> b+tmult.ucl*sqrt(vcov(M)[2,2])
        i 
0.1976507 
> 
> # lower and upper confidence limits for 
> # corrected standard error
> 
> b+tmult.lcl*sqrt(H[2,2])
         i 
-0.6558751 
> b+tmult.ucl*sqrt(H[2,2])
        i 
0.1627909 
>
```

* In both cases, the confidence interval for the slope includes zero.
* However, the width of the corrected confidence interval is 0.1627909-(-0.6558751) = 0.818666 while the width of the uncorrected confidence interval is 0.1976507-(-0.6907349) = 0.8883856; so the corrected confidence interval is about 7.8% narrower, ((0.818666-0.8883856)/0.8883856)*100 = -7.847898.

#### Topic 17: Influential Observations

* Let's begin by estimating the one-variable linear regression model, using the 2018 data:

```R
d <- read.csv(file="ih.csv",header=T,sep=",")

sum(d$p18)
sum(d$h18)

state <- d$state

hm <- (d$h18/d$p18)*100000
i <- d$i18/d$p18*100

M <- lm(hm~1+i)
summary(M)
sr <- rstandard(M)
ysr <- sqrt(abs(sr))
RM <- lm(ysr~1+i)
RM
```

* Here is our output:

```Rout
> d <- read.csv(file="ih.csv",header=T,sep=",")
> 
> sum(d$p18)
[1] 326464979
> sum(d$h18)
[1] 18448
> 
> state <- d$state
> 
> hm <- (d$h18/d$p18)*100000
> i <- d$i18/d$p18*100
> 
> M <- lm(hm~1+i)
> summary(M)

Call:
lm(formula = hm ~ 1 + i)

Residuals:
    Min      1Q  Median      3Q     Max 
-4.2130 -2.6463 -0.1668  1.8877  7.3556 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   5.7622     0.8408   6.853 1.23e-08 ***
i            -0.1469     0.2954  -0.497    0.621    
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 3.052 on 48 degrees of freedom
Multiple R-squared:  0.005126,	Adjusted R-squared:  -0.0156 
F-statistic: 0.2473 on 1 and 48 DF,  p-value: 0.6212

> 
> 
> sr <- rstandard(M)
> ysr <- sqrt(abs(sr))
> RM <- lm(ysr~1+i)
> RM

Call:
lm(formula = ysr ~ 1 + i)

Coefficients:
(Intercept)            i  
    0.95505     -0.04752  

> 
> 
```

* Next, create our scatterplots:

```R
par(mfrow=c(1,3))

# fitted regression line plot

plot(x=i,y=hm,pch=19,ylim=c(0,15),xlim=c(0,7))
abline(M,lty=1,lwd=3,col="darkgreen")
abline(v=seq(from=0,to=7,by=1),lty=3,lwd=0.8)
abline(h=seq(from=0,to=14,by=1),lty=3,lwd=0.8)

# residual plot

plot(x=i,y=residuals(M),pch=19,xlim=c(0,7))
abline(h=0,lty=1,lwd=3,col="darkgreen")
abline(v=seq(from=0,to=7,by=1),lty=3,lwd=0.8)
abline(h=seq(from=-4,to=8,by=1),lty=3,lwd=0.8)

# standardized residual plot

plot(x=i,y=ysr,pch=19,xlim=c(0,7))
abline(RM,lty=1,lwd=3,col="darkgreen")
abline(v=seq(from=0,to=7,by=1),lty=3,lwd=0.8)
abline(h=seq(from=0,to=1.6,by=0.1),lty=3,lwd=0.8)
```

<p align="center">
<img src="/gfiles/hm18.png" width="900px">
</p>

* Each data point has a certain amount of *influence* on the parameter estimates associated with the regression.
* Sheather's book defines "leverage points" as "data points which exercise considerable influence on the fitted model" (p. 51).
* We can calculate the leverage statistic, *h*, (see Sheather, p. 56) for each data point by:

```R
h1 <- 1/50
h2 <- (i-mean(i))^2
h3 <- sum((i-mean(i))^2)
h <- h1+h2/h3
mean(h)
data.frame(d$state,h,hatvalues(M))
```

* Here is our output:

```Rout
> h1 <- 1/50
> h2 <- (i-mean(i))^2
> h3 <- sum((i-mean(i))^2)
> h <- h1+h2/h3
> mean(h)
[1] 0.04
> data.frame(d$state,h,hatvalues(M))
          d.state          h hatvalues.M.
1         alabama 0.03382700   0.03382700
2          alaska 0.03105635   0.03105635
3         arizona 0.03815515   0.03815515
4        arkansas 0.02013444   0.02013444
5      california 0.07795034   0.07795034
6        colorado 0.02275556   0.02275556
7     connecticut 0.04041492   0.04041492
8        delaware 0.02407333   0.02407333
9         florida 0.03616396   0.03616396
10        georgia 0.03180144   0.03180144
11         hawaii 0.02493074   0.02493074
12          idaho 0.02024645   0.02024645
13       illinois 0.02455138   0.02455138
14        indiana 0.02597521   0.02597521
15           iowa 0.02458764   0.02458764
16         kansas 0.02016711   0.02016711
17       kentucky 0.03930042   0.03930042
18      louisiana 0.02828241   0.02828241
19          maine 0.06009924   0.06009924
20       maryland 0.06164827   0.06164827
21  massachusetts 0.04227029   0.04227029
22       michigan 0.03444929   0.03444929
23      minnesota 0.02806053   0.02806053
24    mississippi 0.04414233   0.04414233
25       missouri 0.04005286   0.04005286
26        montana 0.05642452   0.05642452
27       nebraska 0.02156246   0.02156246
28         nevada 0.20787167   0.20787167
29  new hampshire 0.03673610   0.03673610
30     new jersey 0.07078326   0.07078326
31     new mexico 0.02031145   0.02031145
32       new york 0.02369283   0.02369283
33 north carolina 0.02442788   0.02442788
34   north dakota 0.04983520   0.04983520
35           ohio 0.04111760   0.04111760
36       oklahoma 0.02023966   0.02023966
37         oregon 0.02031176   0.02031176
38   pennsylvania 0.02861326   0.02861326
39   rhode island 0.02705556   0.02705556
40 south carolina 0.02423311   0.02423311
41   south dakota 0.03605050   0.03605050
42      tennessee 0.02255453   0.02255453
43          texas 0.11190232   0.11190232
44           utah 0.02487020   0.02487020
45        vermont 0.04532685   0.04532685
46       virginia 0.03091991   0.03091991
47     washington 0.04217914   0.04217914
48  west virginia 0.06393441   0.06393441
49      wisconsin 0.03065211   0.03065211
50        wyoming 0.04329704   0.04329704
>
```

* Sheather recommends that we "classify [an individual data point] as a point of high leverage (i.e., a leverage point) in a simple linear regression model if h > 2*mean(h)
* Here is the R code:

```R
h <- hatvalues(M)
mean(h)
flag <- ifelse(h>2*mean(h),1,0)
data.frame(d$state,h,flag)
```

* Here is our output:

```Rout
> h <- hatvalues(M)
> mean(h)
[1] 0.04
> flag <- ifelse(h>2*mean(h),1,0)
> data.frame(d$state,h,flag)
          d.state          h flag
1         alabama 0.03382700    0
2          alaska 0.03105635    0
3         arizona 0.03815515    0
4        arkansas 0.02013444    0
5      california 0.07795034    0
6        colorado 0.02275556    0
7     connecticut 0.04041492    0
8        delaware 0.02407333    0
9         florida 0.03616396    0
10        georgia 0.03180144    0
11         hawaii 0.02493074    0
12          idaho 0.02024645    0
13       illinois 0.02455138    0
14        indiana 0.02597521    0
15           iowa 0.02458764    0
16         kansas 0.02016711    0
17       kentucky 0.03930042    0
18      louisiana 0.02828241    0
19          maine 0.06009924    0
20       maryland 0.06164827    0
21  massachusetts 0.04227029    0
22       michigan 0.03444929    0
23      minnesota 0.02806053    0
24    mississippi 0.04414233    0
25       missouri 0.04005286    0
26        montana 0.05642452    0
27       nebraska 0.02156246    0
28         nevada 0.20787167    1
29  new hampshire 0.03673610    0
30     new jersey 0.07078326    0
31     new mexico 0.02031145    0
32       new york 0.02369283    0
33 north carolina 0.02442788    0
34   north dakota 0.04983520    0
35           ohio 0.04111760    0
36       oklahoma 0.02023966    0
37         oregon 0.02031176    0
38   pennsylvania 0.02861326    0
39   rhode island 0.02705556    0
40 south carolina 0.02423311    0
41   south dakota 0.03605050    0
42      tennessee 0.02255453    0
43          texas 0.11190232    1
44           utah 0.02487020    0
45        vermont 0.04532685    0
46       virginia 0.03091991    0
47     washington 0.04217914    0
48  west virginia 0.06393441    0
49      wisconsin 0.03065211    0
50        wyoming 0.04329704    0
>
```

* This shows that Nevada and Texas meet the definition of "high leverage points".
* We need to determine whether they are "good" or "bad".
* To do this, we have to calculate the standardized residuals (Sheather, p. 59):

```R
r <- residuals(M)
sr <- r/(sigma(M)*sqrt(1-h))
data.frame(d$state,h,sr,rstandard(M))
sr <- rstandard(M))
```

* Note that *outliers* are defined to be observations with *standardized residuals* > +2 or < -2 (Sheather, p. 60).
* Here is our output:

```Rout
> data.frame(d$state,h,sr,rstandard(M))
          d.state          h          sr rstandard.M.
1         alabama 0.03382700  1.95828803   1.95828803
2          alaska 0.03105635  0.67597109   0.67597109
3         arizona 0.03815515  0.17774455   0.17774455
4        arkansas 0.02013444  1.02817030   1.02817030
5      california 0.07795034 -0.12496052  -0.12496052
6        colorado 0.02275556 -0.19909158  -0.19909158
7     connecticut 0.04041492 -0.92021840  -0.92021840
8        delaware 0.02407333  0.05751220   0.05751220
9         florida 0.03616396  0.32781751   0.32781751
10        georgia 0.03180144  0.75631571   0.75631571
11         hawaii 0.02493074 -0.82313791  -0.82313791
12          idaho 0.02024645 -1.11712727  -1.11712727
13       illinois 0.02455138  0.76703380   0.76703380
14        indiana 0.02597521  0.48399159   0.48399159
15           iowa 0.02458764 -0.99624824  -0.99624824
16         kansas 0.02016711 -0.03123847  -0.03123847
17       kentucky 0.03930042  0.06832589   0.06832589
18      louisiana 0.02828241  2.44475482   2.44475482
19          maine 0.06009924 -1.42376823  -1.42376823
20       maryland 0.06164827  1.23255986   1.23255986
21  massachusetts 0.04227029 -1.01527026  -1.01527026
22       michigan 0.03444929  0.16226778   0.16226778
23      minnesota 0.02806053 -1.11842606  -1.11842606
24    mississippi 0.04414233  2.28438235   2.28438235
25       missouri 0.04005286  1.87108937   1.87108937
26        montana 0.05642452 -0.55492223  -0.55492223
27       nebraska 0.02156246 -1.08311850  -1.08311850
28         nevada 0.20787167  1.00697835   1.00697835
29  new hampshire 0.03673610 -1.25407119  -1.25407119
30     new jersey 0.07078326 -0.60620044  -0.60620044
31     new mexico 0.02031145  1.50604468   1.50604468
32       new york 0.02369283 -0.76509157  -0.76509157
33 north carolina 0.02442788  0.23774925   0.23774925
34   north dakota 0.04983520 -0.88719018  -0.88719018
35           ohio 0.04111760  0.25930442   0.25930442
36       oklahoma 0.02023966  0.40305848   0.40305848
37         oregon 0.02031176 -0.93454925  -0.93454925
38   pennsylvania 0.02861326  0.21530077   0.21530077
39   rhode island 0.02705556 -1.18694921  -1.18694921
40 south carolina 0.02423311  1.25429992   1.25429992
41   south dakota 0.03605050 -0.88385032  -0.88385032
42      tennessee 0.02255453  1.23843029   1.23843029
43          texas 0.11190232  0.11895570   0.11895570
44           utah 0.02487020 -1.06488724  -1.06488724
45        vermont 0.04532685 -1.19684324  -1.19684324
46       virginia 0.03091991 -0.13570841  -0.13570841
47     washington 0.04217914 -0.56038526  -0.56038526
48  west virginia 0.06393441 -0.08102764  -0.08102764
49      wisconsin 0.03065211 -0.72258396  -0.72258396
50        wyoming 0.04329704 -0.78594608  -0.78594608
>
```

* So, Louisiana and Mississippi qualify as outliers based on the 2 standard deviation rule.
* A leverage point that is also an outlier is a *bad* leverage point
* A plot of the leverage points by the standardized residuals is useful here.

```R
plot(x=sr,y=h,pch=19)
abline(h=2*mean(h),lty=2,lwd=2,col="darkred")
abline(v=2,lty=2,lwd=2,col="darkred")
```

<p align="center">
<img src="/gfiles/hsr.png" width="600px">
</p>

* Based on the plot, we do not have any observations that have are outliers *and* have high leverage (so-called "bad" leverage points). Such points would be in the upper right hand sector of the plot (observations with leverage exceeding 2*mean(h) and standardized residuals exceeding |2|).
* If we did have values that were bad leverage points, we would have to exercise judgment (should we fit another model with those data points removed? or should we try a different kind of regression model?).

#### Topic 18: Functional Form

* Sometimes it is useful to fit a regression curve rather than a straight line.
* We can still use linear models to do this (sometimes).
* Here is an example from Sheather (p. 46; dataset #2)

```R
xvals <- c(10,8,13,9,11,14,6,4,12,7,5)
yvals <- c(9.14,8.14,8.74,8.77,9.26,8.1,6.13,3.1,9.13,7.26,4.74)
M <- lm(yvals~1+xvals)
summary(M)
```

* Here is our output:

```Rout
> xvals <- c(10,8,13,9,11,14,6,4,12,7,5)
> yvals <- c(9.14,8.14,8.74,8.77,9.26,8.1,6.13,3.1,9.13,7.26,4.74)
> M <- lm(yvals~1+xvals)
> summary(M)

Call:
lm(formula = yvals ~ 1 + xvals)

Residuals:
    Min      1Q  Median      3Q     Max 
-1.9009 -0.7609  0.1291  0.9491  1.2691 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)   
(Intercept)    3.001      1.125   2.667  0.02576 * 
xvals          0.500      0.118   4.239  0.00218 **
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.237 on 9 degrees of freedom
Multiple R-squared:  0.6662,	Adjusted R-squared:  0.6292 
F-statistic: 17.97 on 1 and 9 DF,  p-value: 0.002179

> 
```

* Now, let's generate a scatterplot and residual plot:

```R
par(mfrow=c(1,2))

plot(x=xvals,y=yvals,pch=19,ylim=c(0,10))
abline(M,lty=1,lwd=3,col="red")
abline(h=0:10,lty=3,lwd=0.8)
abline(v=4:14,lty=3,lwd=0.8)

plot(x=xvals,y=residuals(M),pch=19)
abline(h=0,lty=1,lwd=3,col="red")
abline(h=seq(from=-2,to=1.5,by=0.5),lty=3,lwd=0.8)
abline(v=4:14,lty=3,lwd=0.8)
```

<p align="center">
<img src="/gfiles/curve.png" width="800px">
</p>

* It is clear that the functional form of this regression model is incorrect.
* Instead of fitting a line we need to fit a curve.
* Here is how we can use linear regression to fit a curve:
  
```R
xvals.sq <- xvals*xvals
Q <- lm(yvals~1+xvals+xvals.sq)
summary(Q)
```

* Here is the output:

```Rout
> xvals.sq <- xvals*xvals
> Q <- lm(yvals~1+xvals+xvals.sq)
> summary(Q)

Call:
lm(formula = yvals ~ 1 + xvals + xvals.sq)

Residuals:
       Min         1Q     Median         3Q        Max 
-0.0013287 -0.0011888 -0.0006294  0.0008741  0.0023776 

Coefficients:
              Estimate Std. Error t value Pr(>|t|)    
(Intercept) -5.9957343  0.0043299   -1385   <2e-16 ***
xvals        2.7808392  0.0010401    2674   <2e-16 ***
xvals.sq    -0.1267133  0.0000571   -2219   <2e-16 ***
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.001672 on 8 degrees of freedom
Multiple R-squared:      1,	Adjusted R-squared:      1 
F-statistic: 7.378e+06 on 2 and 8 DF,  p-value: < 2.2e-16

>
```

* Let's see how this fits:

```R
int.qrm <- coef(Q)[1]
b.qrm <- coef(Q)[2]
bsq.qrm <- coef(Q)[3]
x <- 4:14
xsq <- x*x
yfit <- int.qrm+b.qrm*x+bsq.qrm*xsq

plot(x=xvals,y=yvals,pch=19,ylim=c(0,10))
abline(M,lty=1,lwd=3,col="red")
abline(h=0:10,lty=3,lwd=0.8)
abline(v=4:14,lty=3,lwd=0.8)
lines(x=x,y=yfit,lty=1,lwd=3,col="darkred")
```

<p align="center">
<img src="/gfiles/curve2.png" width="600px">
</p>

#### Topics 19/20: Nonlinear Single Variable Regression/Difference Quotients

* Suppose we take the curve we just drew and we plot it in a 2-dimensional space.
* Start a new R session.

```R
x <- seq(from=4,to=14,by=0.1)
y <- -5.9957343+2.7808392*x-0.1267133*x*x
plot(x,y,type="l",lty=1,lwd=3,col="darkred")
abline(h=3:9,lty=3,lwd=0.8)
abline(v=4:14,lty=3,lwd=0.8)
data.frame(x,y)
```

* Here is the resulting plot:

<p align="center">
<img src="/gfiles/curve3.png" width="600px">
</p>

* And the x and y coordinates that underlie this plot:

```Rout
> data.frame(x,y)
       x        y
1    4.0 3.100210
2    4.1 3.275656
3    4.2 3.448568
4    4.3 3.618945
5    4.4 3.786789
6    4.5 3.952098
7    4.6 4.114873
8    4.7 4.275113
9    4.8 4.432819
10   4.9 4.587991
11   5.0 4.740629
12   5.1 4.890733
13   5.2 5.038302
14   5.3 5.183337
15   5.4 5.325838
16   5.5 5.465804
17   5.6 5.603236
18   5.7 5.738134
19   5.8 5.870498
20   5.9 6.000327
21   6.0 6.127622
22   6.1 6.252383
23   6.2 6.374609
24   6.3 6.494302
25   6.4 6.611460
26   6.5 6.726084
27   6.6 6.838173
28   6.7 6.947728
29   6.8 7.054749
30   6.9 7.159236
31   7.0 7.261188
32   7.1 7.360607
33   7.2 7.457490
34   7.3 7.551840
35   7.4 7.643655
36   7.5 7.732937
37   7.6 7.819683
38   7.7 7.903896
39   7.8 7.985574
40   7.9 8.064718
41   8.0 8.141328
42   8.1 8.215404
43   8.2 8.286945
44   8.3 8.355952
45   8.4 8.422425
46   8.5 8.486363
47   8.6 8.547767
48   8.7 8.606637
49   8.8 8.662973
50   8.9 8.716774
51   9.0 8.768041
52   9.1 8.816774
53   9.2 8.862973
54   9.3 8.906637
55   9.4 8.947767
56   9.5 8.986363
57   9.6 9.022424
58   9.7 9.055952
59   9.8 9.086945
60   9.9 9.115403
61  10.0 9.141328
62  10.1 9.164718
63  10.2 9.185574
64  10.3 9.203895
65  10.4 9.219683
66  10.5 9.232936
67  10.6 9.243655
68  10.7 9.251839
69  10.8 9.257490
70  10.9 9.260606
71  11.0 9.261188
72  11.1 9.259235
73  11.2 9.254748
74  11.3 9.247727
75  11.4 9.238172
76  11.5 9.226083
77  11.6 9.211459
78  11.7 9.194301
79  11.8 9.174608
80  11.9 9.152382
81  12.0 9.127621
82  12.1 9.100326
83  12.2 9.070496
84  12.3 9.038133
85  12.4 9.003235
86  12.5 8.965803
87  12.6 8.925836
88  12.7 8.883335
89  12.8 8.838300
90  12.9 8.790731
91  13.0 8.740628
92  13.1 8.687990
93  13.2 8.632818
94  13.3 8.575111
95  13.4 8.514871
96  13.5 8.452096
97  13.6 8.386787
98  13.7 8.318943
99  13.8 8.248566
100 13.9 8.175654
101 14.0 8.100208
>
```

* We can think of this as the graph of a function.
* What is the slope of the line that connects the points (x=5,y=4.740629) and (x=11,y=9.261188)?

```R
x1 <- 5
y1 <- 4.740629
x2 <- 11
y2 <- 9.261188

# point-slope formula

slope <- (y2-y1)/(x2-x1)
slope
int <- y1-slope*x1
int

# add information to the chart

points(x=x1,y=y1,pch=19,cex=1.2)
points(x=x2,y=y2,pch=19,cex=1.2)
abline(a=int,b=slope,col="darkgreen",lty=1,lwd=3)
```

* Here is what we get:

```Rout
> x1 <- 5
> y1 <- 4.740629
> x2 <- 11
> y2 <- 9.261188
> 
> # point-slope formula
> 
> slope <- (y2-y1)/(x2-x1)
> slope
[1] 0.7534265
> int <- y1-slope*x1
> int
[1] 0.9734965
>
```

<p align="center">
<img src="/gfiles/curve4.png" width="600px">
</p>

* Now let's consider the slope of a line connecting the points (x=7.5,y=7.732937) and (x=8.5,y=8.486363).

```R
x1 <- 7.5
y1 <- 7.732937
x2 <- 8.5
y2 <- 8.486363

# point-slope formula

slope <- (y2-y1)/(x2-x1)
slope
int <- y1-slope*x1
int

# add information to the chart

points(x=x1,y=y1,pch=19,cex=1.2)
points(x=x2,y=y2,pch=19,cex=1.2)
abline(a=int,b=slope,col="blue",lty=1,lwd=3)
```

* Here is what we get:

```Rout
> x1 <- 7.5
> y1 <- 7.732937
> x2 <- 8.5
> y2 <- 8.486363
> 
> # point-slope formula
> 
> slope <- (y2-y1)/(x2-x1)
> slope
[1] 0.753426
> int <- y1-slope*x1
> int
[1] 2.082242
> 
```

<p align="center">
<img src="/gfiles/curve5.png" width="600px">
</p>

* Notice how the slope of this line is very close to the average for the region x={5,11}
* Let's try a different set of points; this time we will look at x={6,7}

```R
x1 <- 6
y1 <- 6.127622
x2 <- 7
y2 <- 7.261188

# point-slope formula

slope <- (y2-y1)/(x2-x1)
slope
int <- y1-slope*x1
int

# add information to the chart

points(x=x1,y=y1,pch=19,cex=1.2)
points(x=x2,y=y2,pch=19,cex=1.2)
abline(a=int,b=slope,col="purple",lty=1,lwd=3)
```

* Here is our output:

```Rout
> x1 <- 6
> y1 <- 6.127622
> x2 <- 7
> y2 <- 7.261188
> 
> # point-slope formula
> 
> slope <- (y2-y1)/(x2-x1)
> slope
[1] 1.133566
> int <- y1-slope*x1
> int
[1] -0.673774
> 
> # add information to the chart
> 
> points(x=x1,y=y1,pch=19,cex=1.2)
> points(x=x2,y=y2,pch=19,cex=1.2)
> abline(a=int,b=slope,col="purple",lty=1,lwd=3)
>
```

<p align="center">
<img src="/gfiles/curve6.png" width="600px">
</p>

* Each of the straight lines is called a *secant*.
* The slope of the secant represents the average amount of change in *y* for a unit change in *x* in the neighborhood of x={5,7}.
* Notice that the secant slope is always positive in the regions we've been looking at.
* But let's calculate the slope of the secant in the domain of x={12,13}

```R
x1 <- 12
y1 <- 9.127621
x2 <- 13
y2 <- 8.740628

# point-slope formula

slope <- (y2-y1)/(x2-x1)
slope
int <- y1-slope*x1
int

# add information to the chart

points(x=x1,y=y1,pch=19,cex=1.2)
points(x=x2,y=y2,pch=19,cex=1.2)
abline(a=int,b=slope,col="red",lty=1,lwd=3)
```

* Here is our output:

```Rout
> x1 <- 12
> y1 <- 9.127621
> x2 <- 13
> y2 <- 8.740628
> 
> # point-slope formula
> 
> slope <- (y2-y1)/(x2-x1)
> slope
[1] -0.386993
> int <- y1-slope*x1
> int
[1] 13.77154
>
```

<p align="center">
<img src="/gfiles/curve7.png" width="600px">
</p>

* Notice that if we keep making the distance between x1 and x2 smaller, we will still be able to calculate the slope of the line.
* When the distance between x1 and x2 approaches zero, the secant becomes a tangent and we have the derivative of the function at that x point.

#### Example Problem

* Use the 2019 homicide data to estimate a linear regression of the 2019 homicide rate on the 2019 undocumented immigrant population rate. Use your residual diagnostics to determine whether there are any influential observations. What do you conclude?
  
* Please enter the following dataset into R:

```Rout
> data.frame(x,y)
           x         y
1  10.525025 10.006471
2   9.167082  8.477390
3  12.088710  8.502788
4   4.666047  2.950113
5   5.724271  5.258985
6  11.393397  8.239564
7  12.584118  9.191330
8   5.675389  4.865792
9   5.229290  4.914085
10  4.594962  4.980177
11  6.324089  6.676996
12  5.574342  5.389346
13  6.719233  6.950672
14 13.852802  7.767387
15 10.245633  9.038506
16 11.988984  9.181324
17  4.007869  2.827483
18 13.207840  9.468860
19  8.493307  8.110161
20 13.494317  8.335246
21  4.374399  4.258318
22  9.693014  9.805548
23 13.572246  8.259157
24  5.843392  5.444042
25  9.654258  8.487896
26 11.742820  8.913228
27  4.269311  3.191912
28 10.476408 10.021241
29  6.983456  7.329047
30 11.202451  9.429451
>
```

* Estimate a linear regression of *y* on *x*.
* Create a scatterplot (with the least squares line) and a residual plot for this regression.
* Estimate a quadratic regression of *y* on *x*.
* Calculate the coordinates for the parabola implied by this regression.
* Create a new scatterplot where you draw the parabola through the points.
* Create a new residual plot based on the quadratic regression. Do the residuals appear to be randomly distributed?
* Calculate E(y|x=12)-E(y|x=11) based on the linear regression model.
* Calculate E(y|x=12)-E(y|x=11) based on the quadratic regression model.
* Draw a secant on the quadratic regression plot space based on the difference quotient, E(y|x=12)-E(y|x=11)

### Lesson 10 - Monday 4/7/25

* Worked practice problem from last week.
* Let's read in a comma-separated version of the dataset:

```R
d <- read.csv(file="d.txt",header=T,sep=",")
d
```

* Next up, we estimate the linear regression model:

```R
L <- lm(y~1+x,data=d)
summary(L)
```

* Here is a summary of the regression analysis:

```Rout
> L <- lm(y~1+x,data=d)
> summary(L)

Call:
lm(formula = y ~ 1 + x, data = d)

Residuals:
    Min      1Q  Median      3Q     Max 
-2.3627 -0.5361 -0.0386  0.9158  2.0702 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   2.1550     0.6189   3.482  0.00165 ** 
x             0.5757     0.0661   8.710 1.85e-09 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.18 on 28 degrees of freedom
Multiple R-squared:  0.7304,	Adjusted R-squared:  0.7208 
F-statistic: 75.86 on 1 and 28 DF,  p-value: 1.85e-09

>
```

* Now, let's create a scatterplot:

```R
lint <- coef(L)[1]
lb1 <- coef(L)[2]
xstar <- seq(from=3,to=15,by=0.01)
yhatl <- lint+lb1*xstar
plot(d$x,d$y,pch=19)
lines(x=xstar,y=yhatl,lty=1,lwd=3,col="blue")
abline(h=3:10,lty=3,lwd=0.8)
abline(v=4:14,lty=3,lwd=0.8)
```

* Here is the plot:

<p align="center">
<img src="/gfiles/curve8.png" width="600px">
</p>

* The quadratic regression is:

```R
d$xsq <- d$x*d$x
Q <- lm(y~1+x+xsq,data=d)
summary(Q)
qint <- coef(Q)[1]
qb1 <- coef(Q)[2]
qb2 <- coef(Q)[3]
xstarsq <- xstar*xstar
yhatq <- qint+qb1*xstar+qb2*xstarsq
lines(x=xstar,y=yhatq,lty=1,lwd=3,col="red")
```

* And the output is:

```Rout
> d$xsq <- d$x*d$x
> Q <- lm(y~1+x+xsq,data=d)
> summary(Q)

Call:
lm(formula = y ~ 1 + x + xsq, data = d)

Residuals:
     Min       1Q   Median       3Q      Max 
-1.05165 -0.32329 -0.06149  0.25812  1.09661 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) -6.55382    0.93508  -7.009 1.56e-07 ***
x            2.87104    0.23599  12.166 1.81e-12 ***
xsq         -0.13048    0.01329  -9.814 2.12e-10 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.5621 on 27 degrees of freedom
Multiple R-squared:  0.941,	Adjusted R-squared:  0.9366 
F-statistic: 215.2 on 2 and 27 DF,  p-value: < 2.2e-16

> qint <- coef(Q)[1]
> qb1 <- coef(Q)[2]
> qb2 <- coef(Q)[3]
> xstarsq <- xstar*xstar
> yhatq <- qint+qb1*xstar+qb2*xstarsq
> lines(x=xstar,y=yhatq,lty=1,lwd=3,col="red")
>
```

<p align="center">
<img src="/gfiles/curve9.png" width="600px">
</p>

* Next, we create residual plots for both statistical models:

```R
par(mfrow=c(1,2))
plot(d$x,residuals(L),pch=19)
abline(h=0,lty=2,lwd=0.8)
plot(d$x,residuals(Q),pch=19)
abline(h=0,lty=2,lwd=0.8)
```

<p align="center">
<img src="/gfiles/resid-plot.png" width="600px">
</p>

* Again, we are looking for an approximately random distribution of residuals which is not evident in the left-hand plot (a horseshoe pattern) but is evident in the right-hand plot (correctly specified model).
* Let's generate the scatterplot again with a regression line and a quadratic regression curve.

```R
# redraw linear and quadratic scatterplot

plot(d$x,d$y,pch=19)
lines(x=xstar,y=yhatl,lty=1,lwd=3,col="blue")
abline(h=3:10,lty=3,lwd=0.8)
abline(v=4:14,lty=3,lwd=0.8)
lines(x=xstar,y=yhatq,lty=1,lwd=3,col="red")

eyx11.linear <- lint+lb1*11
eyx12.linear <- lint+lb1*12
slope.linear <- eyx12.linear-eyx11.linear
slope.linear
int.linear <- eyx11.linear-slope.linear*11
int.linear

eyx11.quadratic <- qint+qb1*11+qb2*11*11
eyx12.quadratic <- qint+qb1*12+qb2*12*12
slope.quadratic <- eyx12.quadratic-eyx11.quadratic
slope.quadratic
int.quadratic <- eyx11.quadratic-slope.quadratic*11
int.quadratic
abline(a=int.quadratic,b=slope.quadratic,lty=1,lwd=3,col="darkgreen")
```

<p align="center">
<img src="/gfiles/secant.png" width="600px">
</p>

* Note that the green line is a secant which shows the slope of the line connecting E(y|x=12) and E(y|x=11) based on the quadratic specification.
* With nonlinear regressions, it is important to be able to estimate the difference between conditional expectations because the magnitude of the estimated difference could vary depending on the value of *x*.
* When we estimate a conditional expectation or a difference between two conditional expectations, we need to provide a measure of uncertainty to accompany the estimate.
* Let's begin by calculating a 92% confidence interval for our estimate of the E(y|x=11) from the quadratic regression.
* We can use the following bootstrap code to estimate this confidence interval:

```R
eyx11.quadratic

library(boot)

eb <- function(data,i){
  b <- data[i,]
  Qb <- lm(y~1+x+xsq,data=b)
  eyx11b <- coef(Qb)[1]+coef(Qb)[2]*11+coef(Qb)[3]*11*11
  return(eyx11b)
  }

qb <- boot(data=d,statistic=eb,R=1e5)
qb
boot.ci(qb,conf=0.92,type="bca",index=1)
```

* Here is our output:

```Rout
> eyx11.quadratic
   9.239385 
> 
> library(boot)
> 
> eb <- function(data,i){
+   b <- data[i,]
+   Qb <- lm(y~1+x+xsq,data=b)
+   eyx11b <- coef(Qb)[1]+coef(Qb)[2]*11+coef(Qb)[3]*11*11
+   return(eyx11b)
+   }
> 
> qb <- boot(data=d,statistic=eb,R=1e5)
> qb

ORDINARY NONPARAMETRIC BOOTSTRAP


Call:
boot(data = d, statistic = eb, R = 1e+05)


Bootstrap Statistics :
    original      bias    std. error
t1* 9.239385 0.001603776   0.1467056
> boot.ci(qb,conf=0.92,type="bca",index=1)
BOOTSTRAP CONFIDENCE INTERVAL CALCULATIONS
Based on 100000 bootstrap replicates

CALL :
boot.ci(boot.out = qb, conf = 0.92, type = "bca", index = 1)

Intervals : 
Level       BCa          
92%   ( 8.986,  9.500 )  
Calculations and Intervals on Original Scale
>
```

* So, this analysis tells us that the point estimate of E(y|x=11) under the quadratic specification is 9.239; based on the BCa bootstrap, the 92% confidence interval around this estimate is [8.986,9.500].
* We can elaborate on this example by estimating Δ = E(y|x=12) - E(y|x=11) and then calculating a 94% confidence interval for that difference.

```R
eyx12.quadratic-eyx11.quadratic

library(boot)

eb <- function(data,i){
  b <- data[i,]
  Qb <- lm(y~1+x+xsq,data=b)
  eyx11b <- coef(Qb)[1]+coef(Qb)[2]*11+coef(Qb)[3]*11*11
  eyx12b <- coef(Qb)[1]+coef(Qb)[2]*12+coef(Qb)[3]*12*12
  delta <- eyx12b-eyx11b
  return(delta)
  }

qb <- boot(data=d,statistic=eb,R=1e5)
qb
boot.ci(qb,conf=0.94,type="bca",index=1)
```

* Here is our output (which confirms the negative slope of the secant in the chart posted above).

```Rout
> eyx12.quadratic-eyx11.quadratic
(Intercept) 
 -0.1300335 
> 
> library(boot)
> 
> eb <- function(data,i){
+   b <- data[i,]
+   Qb <- lm(y~1+x+xsq,data=b)
+   eyx11b <- coef(Qb)[1]+coef(Qb)[2]*11+coef(Qb)[3]*11*11
+   eyx12b <- coef(Qb)[1]+coef(Qb)[2]*12+coef(Qb)[3]*12*12
+   delta <- eyx12b-eyx11b
+   return(delta)
+   }
> 
> qb <- boot(data=d,statistic=eb,R=1e5)
> qb

ORDINARY NONPARAMETRIC BOOTSTRAP


Call:
boot(data = d, statistic = eb, R = 1e+05)


Bootstrap Statistics :
      original     bias    std. error
t1* -0.1300335 0.00254202  0.06748186
> boot.ci(qb,conf=0.94,type="bca",index=1)
BOOTSTRAP CONFIDENCE INTERVAL CALCULATIONS
Based on 100000 bootstrap replicates

CALL : 
boot.ci(boot.out = qb, conf = 0.94, type = "bca", index = 1)

Intervals : 
Level       BCa          
94%   (-0.2385,  0.0187 )  
Calculations and Intervals on Original Scale
>
```

* Our point estimate for the difference is -0.130 and the 94% confidence interval around this estimate is [-0.2385,0.0187] which includes zero. Based on this evidence, we would fail to reject Ho that Δ = E(y|x=12) - E(y|x=11) = 0 (at the 94% confidence level).

#### Practice Problem

* Read the ih.csv dataset (emailed to you on March 10th).
* Calculate the 2018 homicide rate per 100,000 population for each state; store the rate in an object called *h*.
* Calculate the 2018 undocumented immigration (as a percent of the population) for each state; store in an object called *i*.
* Estimate a linear regression model where *h* is the outcome and *i* is the independent variable.
* Create a scatterplot where *i* is on the horizontal axis and *h* is on the vertical axis.
* Use your linear model to draw a regression line through the scatterplot.
* Estimate a quadratic regression model where *h* is the outcome and *i* is the independent variable.
* Estimate E(y|x=3) for the linear model; calculate a 87% confidence interval around this estimate.
* Estimate E(y|x=3) for the quadratic model; calculate a 87% confidence interval around this estimate.
* Estimate Δ = E(y|x=4)-E(y|x=3) for the quadratic model; use this information to draw a secant on the scatterplot.
* Calculate a 93% confidence interval for Δ; use this confidence interval to test the hypothesis that Δ = 0.
* Challenge: design a simulation procedure that will allow you to verify that this confidence interval procedure has the correct coverage rate.

### Lesson 11 - Monday 4/14/25

* Worked practice problem from last week (topic 22)
* Read the ih.csv dataset (emailed to you on March 10th).

```R
d <- read.csv(file="ih.csv",header=T,sep=",")
```

* Calculate the 2018 homicide rate per 100,000 population for each state; store the rate in an object called *h*.
* Calculate the 2018 undocumented immigration (as a percent of the population) for each state; store in an object called *i*.

```R
h <- (d$h18/d$p18)*100000
i <- (d$i18/d$p18)*100
```

* Estimate a linear regression model where *h* is the outcome and *i* is the independent variable.

```R
L <- lm(h~1+i)
summary(L)
```

* Here is our output:

```Rout
> L <- lm(h~1+i)
> summary(L)

Call:
lm(formula = h ~ 1 + i)

Residuals:
    Min      1Q  Median      3Q     Max 
-4.2130 -2.6463 -0.1668  1.8877  7.3556 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   5.7622     0.8408   6.853 1.23e-08 ***
i            -0.1469     0.2954  -0.497    0.621    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 3.052 on 48 degrees of freedom
Multiple R-squared:  0.005126,	Adjusted R-squared:  -0.0156 
F-statistic: 0.2473 on 1 and 48 DF,  p-value: 0.6212

>
```

* Create a scatterplot where *i* is on the horizontal axis and *h* is on the vertical axis.
* Use your linear model to draw a regression line through the scatterplot.

```R
plot(i,h,pch=19,ylim=c(0,14))
abline(L,lty=1,lwd=3,col="red")
abline(h=0:14,lty=3,lwd=0.8)
abline(v=0:7,lty=3,lwd=0.8)
```

<p align="center">
<img src="/gfiles/s1.png" width="600px">
</p>

* Estimate a quadratic regression model where *h* is the outcome and *i* is the independent variable.

```R
isq <- i*i
Q <- lm(h~1+i+isq)
summary(Q)
```

```Rout
> isq <- i*i
> Q <- lm(h~1+i+isq)
> summary(Q)

Call:
lm(formula = h ~ 1 + i + isq)

Residuals:
    Min      1Q  Median      3Q     Max 
-4.5592 -2.6364 -0.1287  1.6218  7.3784 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  6.27590    1.30301   4.816 1.56e-05 ***
i           -0.62572    0.96951  -0.645    0.522    
isq          0.08095    0.15600   0.519    0.606    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 3.076 on 47 degrees of freedom
Multiple R-squared:  0.01079,	Adjusted R-squared:  -0.0313 
F-statistic: 0.2564 on 2 and 47 DF,  p-value: 0.7749

>
```

* Let's add to the scatterplot:

```R
x <- seq(from=0,to=7,by=0.1)
y <- 6.27590-0.62572*x+0.08095*x*x
plot(i,h,pch=19,ylim=c(0,14))
abline(L,lty=1,lwd=3,col="red")
abline(h=0:14,lty=3,lwd=0.8)
abline(v=0:7,lty=3,lwd=0.8)
lines(x,y,lty=1,lwd=3,col="blue")
```

<p align="center">
<img src="/gfiles/s2.png" width="600px">
</p>

* Estimate E(y|x=3) for the linear model; calculate a 87% confidence interval around this estimate.

```R
eyx3 <- 5.7622-0.1469*3

s <- data.frame(h,i,isq)

library(boot)

eb <- function(data,i){
  b <- data[i,]
  Lb <- lm(h~1+i,data=b)
  eyx3b <- coef(Lb)[1]+coef(Lb)[2]*3
  return(eyx3b)
  }

qb <- boot(data=s,statistic=eb,R=1e5)
qb
boot.ci(qb,conf=0.87,type="bca",index=1)
```

* Here is our output:

```Rout
> eyx3 <- 5.7622-0.1469*3
[1] 5.3215
> 
> s <- data.frame(h,i,isq)
> 
> library(boot)
> 
> eb <- function(data,i){
+   b <- data[i,]
+   Lb <- lm(h~1+i,data=b)
+   eyx3b <- coef(Lb)[1]+coef(Lb)[2]*3
+   return(eyx3b)
+   }
> 
> qb <- boot(data=s,statistic=eb,R=1e5)
> qb

ORDINARY NONPARAMETRIC BOOTSTRAP


Call:
boot(data = s, statistic = eb, R = 1e+05)


Bootstrap Statistics :
    original      bias    std. error
t1* 5.321448 -0.01957561   0.3997628
> boot.ci(qb,conf=0.87,type="bca",index=1)
BOOTSTRAP CONFIDENCE INTERVAL CALCULATIONS
Based on 100000 bootstrap replicates

CALL : 
boot.ci(boot.out = qb, conf = 0.87, type = "bca", index = 1)

Intervals : 
Level       BCa          
87%   ( 4.752,  5.966 )  
Calculations and Intervals on Original Scale
>
```

* Estimate E(y|x=3) for the quadratic model; calculate a 87% confidence interval around this estimate.

```R
eyx3b <- 6.27590-0.62572*3+0.08095*3*3
eyx3b

eb <- function(data,i){
  b <- data[i,]
  Qb <- lm(h~1+i+isq,data=b)
  eyx3b <- coef(Qb)[1]+coef(Qb)[2]*3+coef(Qb)[3]*3*3
  return(eyx3b)
  }

qb <- boot(data=s,statistic=eb,R=1e5)
qb
boot.ci(qb,conf=0.87,type="bca",index=1)
```

```Rout
> eyx3b <- 6.27590-0.62572*3+0.08095*3*3
> eyx3b
[1] 5.12729
> 
> eb <- function(data,i){
+   b <- data[i,]
+   Qb <- lm(h~1+i+isq,data=b)
+   eyx3b <- coef(Qb)[1]+coef(Qb)[2]*3+coef(Qb)[3]*3*3
+   return(eyx3b)
+   }
> 
> qb <- boot(data=s,statistic=eb,R=1e5)
> qb

ORDINARY NONPARAMETRIC BOOTSTRAP


Call:
boot(data = s, statistic = eb, R = 1e+05)


Bootstrap Statistics :
    original     bias    std. error
t1* 5.127302 0.05530494   0.5187268
> boot.ci(qb,conf=0.87,type="bca",index=1)
BOOTSTRAP CONFIDENCE INTERVAL CALCULATIONS
Based on 100000 bootstrap replicates

CALL : 
boot.ci(boot.out = qb, conf = 0.87, type = "bca", index = 1)

Intervals : 
Level       BCa          
87%   ( 4.359,  5.910 )  
Calculations and Intervals on Original Scale
> 
```

* Estimate Δ = E(y|x=4)-E(y|x=3) for the quadratic model; use this information to draw a secant on the scatterplot.

```R
eyx4.q <- 6.27590-0.62572*4+0.08095*4*4
eyx3.q <- 6.27590-0.62572*3+0.08095*3*3
slope.q <- eyx4.q-eyx3.q
slope.q
int.q <- eyx4.q-slope.q*4
int.q
abline(a=int.q,b=slope.q,lty=1,lwd=3,col="darkgreen")
```

* Here is our output:

```Rout
> eyx4.q <- 6.27590-0.62572*4+0.08095*4*4
> eyx3.q <- 6.27590-0.62572*3+0.08095*3*3
> slope.q <- eyx4.q-eyx3.q
> slope.q
[1] -0.05907
> int.q <- eyx4.quadratic-slope.q*4
> int.q
[1] 5.3045
```

<p align="center">
<img src="/gfiles/s3.png" width="600px">
</p>

* Calculate a 93% confidence interval for Δ; use this confidence interval to test the hypothesis that Δ = 0.

```
eb <- function(data,i){
  b <- data[i,]
  Qb <- lm(h~1+i+isq,data=b)
  eyx3b <- coef(Qb)[1]+coef(Qb)[2]*3+coef(Qb)[3]*3*3
  eyx4b <- coef(Qb)[1]+coef(Qb)[2]*4+coef(Qb)[3]*4*4
  delta <- eyx4b-eyx3b
  return(delta)
  }

qb <- boot(data=s,statistic=eb,R=1e5)
qb
boot.ci(qb,conf=0.93,type="bca",index=1)
```

* Here is our output:

```Rout
> eb <- function(data,i){
+   b <- data[i,]
+   Qb <- lm(h~1+i+isq,data=b)
+   eyx3b <- coef(Qb)[1]+coef(Qb)[2]*3+coef(Qb)[3]*3*3
+   eyx4b <- coef(Qb)[1]+coef(Qb)[2]*4+coef(Qb)[3]*4*4
+   delta <- eyx4b-eyx3b
+   return(delta)
+   }
> 
> qb <- boot(data=s,statistic=eb,R=1e5)
> qb

ORDINARY NONPARAMETRIC BOOTSTRAP


Call:
boot(data = s, statistic = eb, R = 1e+05)


Bootstrap Statistics :
      original     bias    std. error
t1* -0.0590562 -0.1535435   0.4354478
> boot.ci(qb,conf=0.93,type="bca",index=1)
BOOTSTRAP CONFIDENCE INTERVAL CALCULATIONS
Based on 100000 bootstrap replicates

CALL : 
boot.ci(boot.out = qb, conf = 0.93, type = "bca", index = 1)

Intervals : 
Level       BCa          
93%   (-0.7287,  0.4550 )  
Calculations and Intervals on Original Scale
>
```

* Notice that this confidence interval includes zero.
* The evidence is not strong enough to reject Ho that Δ = 0.
* Challenge: design a simulation procedure that will allow you to verify that this confidence interval procedure has the correct coverage rate.

```R
set.seed(3)

x <- rnorm(n=100,mean=10,sd=1)
xsq <- x*x
eyx10 <- 3+2*10-0.5*10*10
eyx11 <- 3+2*11-0.5*11*11
t <- eyx11-eyx10
t

lcl <- vector()
ucl <- vector()

for(i in 1:3000){
  y <- 3+2*x-0.5*xsq+rnorm(n=100,mean=0,sd=1)
  
  delta <- vector()

  for(j in 1:3000){
    b <- sample(1:100,size=100,replace=T)
    yb <- y[b]
    xb <- x[b]
    xsqb <- xsq[b]
  
    Qb <- lm(yb~1+xb+xsqb)
    eyx10b <- coef(Qb)[1]+coef(Qb)[2]*10+coef(Qb)[3]*10*10
    eyx11b <- coef(Qb)[1]+coef(Qb)[2]*11+coef(Qb)[3]*11*11
    delta[j] <- eyx11b-eyx10b
    }

  lcl[i] <- quantile(delta,0.035)
  ucl[i] <- quantile(delta,1-0.035)
  }

f <- ifelse(lcl<t & ucl>t,1,0)
mean(f)
```

* Here is the output:

```Rout
> set.seed(3)
> 
> x <- rnorm(n=100,mean=10,sd=1)
> xsq <- x*x
> eyx10 <- 3+2*10-0.5*10*10
> eyx11 <- 3+2*11-0.5*11*11
> t <- eyx11-eyx10
> t
[1] -8.5
> 
> lcl <- vector()
> ucl <- vector()
> 
> for(i in 1:3000){
+   y <- 3+2*x-0.5*xsq+rnorm(n=100,mean=0,sd=1)
+   
+   delta <- vector()
+ 
+   for(j in 1:3000){
+     b <- sample(1:100,size=100,replace=T)
+     yb <- y[b]
+     xb <- x[b]
+     xsqb <- xsq[b]
+   
+     Qb <- lm(yb~1+xb+xsqb)
+     eyx10b <- coef(Qb)[1]+coef(Qb)[2]*10+coef(Qb)[3]*10*10
+     eyx11b <- coef(Qb)[1]+coef(Qb)[2]*11+coef(Qb)[3]*11*11
+     delta[j] <- eyx11b-eyx10b
+     }
+ 
+   lcl[i] <- quantile(delta,0.035)
+   ucl[i] <- quantile(delta,1-0.035)
+   }
> 
> f <- ifelse(lcl<t & ucl>t,1,0)
> mean(f)
[1] 0.9226667
> 
```

#### Topic 23: Matrix Operations

* Define a vector:

```R
A <- c(3,5,2)
A
is.vector(A)
```

* Output:

```Rout
> A <- c(3,5,2)
> A
[1] 3 5 2
> is.vector(A)
[1] TRUE
>
```

* Define a matrix:

```R
B <- matrix(1:9, nrow = 3, ncol = 3)
B
is.matrix(B)
```

* Output:

```Rout
> B <- matrix(1:9, nrow = 3, ncol = 3)
> B
     [,1] [,2] [,3]
[1,]    1    4    7
[2,]    2    5    8
[3,]    3    6    9
>
> (B)
[1] TRUE
> 
```

* Now, let's transpose the matrix to get $\bf{B}^T$:

```R

> t(B)
     [,1] [,2] [,3]
[1,]    1    2    3
[2,]    4    5    6
[3,]    7    8    9
>
```

* Note that the *order* of the matrix is defined in terms of the number of rows and columns of the matrix; for example, matrix $\bf{B}$ above is a $3 \times 3$ matrix.
* Let's consider the following matrix, $\bf{C}$ which is a $3 \times 4$ matrix.

```R
C <- matrix(1:12, nrow = 3, ncol = 4)
C
is.matrix(C)
```

* Output:

```Rout
> C <- matrix(1:12, nrow = 3, ncol = 4)
> C
     [,1] [,2] [,3] [,4]
[1,]    1    4    7   10
[2,]    2    5    8   11
[3,]    3    6    9   12
> is.matrix(C)
[1] TRUE
>
```

* Note that matrix $\bf{B}$ is a square matrix because the number of rows is equal to the number of columns.
* Addition and subtraction of matrices; note that matrices must have the same order to be added or subtracted:

```R
B
t(B)
B+t(B)
B-t(B)
```

* Output:

```Rout
> B
     [,1] [,2] [,3]
[1,]    1    4    7
[2,]    2    5    8
[3,]    3    6    9
> t(B)
     [,1] [,2] [,3]
[1,]    1    2    3
[2,]    4    5    6
[3,]    7    8    9
> B+t(B)
     [,1] [,2] [,3]
[1,]    2    6   10
[2,]    6   10   14
[3,]   10   14   18
> B-t(B)
     [,1] [,2] [,3]
[1,]    0    2    4
[2,]   -2    0    2
[3,]   -4   -2    0
>
```

* Multiply a matrix by a single number (a scalar):

```R
B
2*B
```

* Output:

```Rout
> B
     [,1] [,2] [,3]
[1,]    1    4    7
[2,]    2    5    8
[3,]    3    6    9
> 2*B
     [,1] [,2] [,3]
[1,]    2    8   14
[2,]    4   10   16
[3,]    6   12   18
>
```

* Multiply a matrix by another matrix:

```R
M1 <- matrix(1:4, nrow = 2, ncol = 2)
M1
is.matrix(M1)
M2 <- matrix(5:8, nrow = 2, ncol = 2)
M2
is.matrix(M2)
M1%*%M2

c11 <- M1[1,1]*M2[1,1]+
       M1[1,2]*M2[2,1]
c11
c21 <- M1[2,1]*M2[1,1]+
       M1[2,2]*M2[2,1]
c21
c12 <- M1[1,1]*M2[1,2]+
       M1[1,2]*M2[2,2]
c12
c22 <- M1[2,1]*M2[1,2]+
       M1[2,2]*M2[2,2]
c22
```

* Output:

```Rout
> M1 <- matrix(1:4, nrow = 2, ncol = 2)
> M1
     [,1] [,2]
[1,]    1    3
[2,]    2    4
> is.matrix(M1)
[1] TRUE
> M2 <- matrix(5:8, nrow = 2, ncol = 2)
> M2
     [,1] [,2]
[1,]    5    7
[2,]    6    8
> is.matrix(M2)
[1] TRUE
> M1%*%M2
     [,1] [,2]
[1,]   23   31
[2,]   34   46
> 
> c11 <- M1[1,1]*M2[1,1]+
+        M1[1,2]*M2[2,1]
> c11
[1] 23
> c21 <- M1[2,1]*M2[1,1]+
+        M1[2,2]*M2[2,1]
> c21
[1] 34
> c12 <- M1[1,1]*M2[1,2]+
+        M1[1,2]*M2[2,2]
> c12
[1] 31
> c22 <- M1[2,1]*M2[1,2]+
+        M1[2,2]*M2[2,2]
> c22
[1] 46
>
```

* Note the following inequality:

```R
M1%*%M2
M2%*%M1
```

* Output:

```Rout
> M1%*%M2
     [,1] [,2]
[1,]   23   31
[2,]   34   46
> M2%*%M1
     [,1] [,2]
[1,]   19   43
[2,]   22   50
>
```

* Note that it is possible to multiply a $3 \times 4$ matrix by a $4 \times 2$ matrix but it is not possible to multiply the other way:

```R
> T1 <- matrix(1:12, nrow = 3, ncol = 4)
> T2 <- matrix(13:20,nrow = 4, ncol = 2)
> T1%*%T2
     [,1] [,2]
[1,]  334  422
[2,]  392  496
[3,]  450  570
> T2%*%T1
Error in T2 %*% T1 : non-conformable arguments
>
```

* Inverse of a number:

```R
x <- 3
ix <- 1/x
ix
ix*x
```

* Output:

```Rout
> x <- 3
> ix <- 1/x
> ix
[1] 0.3333333
> ix*x
[1] 1
>
```

* Inverse of a matrix:

```R
M <- matrix(1:4, nrow = 2, ncol = 2)
M
solve(M)
solve(M)%*%M
```

* Output:

```Rout
> M <- matrix(1:4, nrow = 2, ncol = 2)
> M
     [,1] [,2]
[1,]    1    3
[2,]    2    4
> solve(M)
     [,1] [,2]
[1,]   -2  1.5
[2,]    1 -0.5
>
> solve(M)%*%M
     [,1] [,2]
[1,]    1    0
[2,]    0    1
> 
```

* The last matrix, the product of $\bf{M}^{-1}$ and $\bf{M}$, is called the identity matrix.
* What does the solve() function do?

```R
a <- M[1,1]
b <- M[2,1]
c <- M[1,2]
d <- M[2,2]
D <- a*d-b*c
D
det(M)
MI11 <- d/D
MI12 <- -b/D
MI21 <- -c/D
MI22 <- a/D
mi.values <- c(MI11,MI12,MI21,MI22)
MI <- matrix(mi.values, nrow = 2, ncol = 2)
MI
solve(M)
```

* Output:

```Rout
> a <- M[1,1]
> b <- M[2,1]
> c <- M[1,2]
> d <- M[2,2]
> D <- a*d-b*c
> D
[1] -2
> det(M)
[1] -2
> MI11 <- d/D
> MI12 <- -b/D
> MI21 <- -c/D
> MI22 <- a/D
> mi.values <- c(MI11,MI12,MI21,MI22)
> MI <- matrix(mi.values, nrow = 2, ncol = 2)
> MI
     [,1] [,2]
[1,]   -2  1.5
[2,]    1 -0.5
> solve(M)
     [,1] [,2]
[1,]   -2  1.5
[2,]    1 -0.5
>
```

* Matrix solution for least squares regression:

```R
set.seed(5)
x <- rnorm(n=10,mean=10,sd=1)
o <- rep(1,10)
X <- cbind(o,x)
X
is.matrix(X)
t(X)
y <- 3+1*x+rnorm(n=10,mean=0,sd=1)
y
B <- solve(t(X)%*%X)%*%t(X)%*%y
summary(lm(y~1+x))
```

* Output:

```Rout
> set.seed(5)
> x <- rnorm(n=10,mean=10,sd=1)
> o <- rep(1,10)
> X <- cbind(o,x)
> X
      o         x
 [1,] 1  9.159145
 [2,] 1 11.384359
 [3,] 1  8.744508
 [4,] 1 10.070143
 [5,] 1 11.711441
 [6,] 1  9.397092
 [7,] 1  9.527834
 [8,] 1  9.364629
 [9,] 1  9.714226
[10,] 1 10.138108
> is.matrix(X)
[1] TRUE
> t(X)
      [,1]     [,2]     [,3]     [,4]     [,5]     [,6]
o 1.000000  1.00000 1.000000  1.00000  1.00000 1.000000
x 9.159145 11.38436 8.744508 10.07014 11.71144 9.397092
      [,7]     [,8]     [,9]    [,10]
o 1.000000 1.000000 1.000000  1.00000
x 9.527834 9.364629 9.714226 10.13811
>
> y <- 3+1*x+rnorm(n=10,mean=0,sd=1)
> y
 [1] 13.38677 13.58258 10.66412 12.91261 13.63968 12.25811
 [7] 11.93052 10.18066 12.95504 12.87875
>
> B <- solve(t(X)%*%X)%*%t(X)%*%y
> B
       [,1]
o 4.1738674
x 0.8330706
>
> summary(lm(y~1+x))

Call:
lm(formula = y ~ 1 + x)

Residuals:
     Min       1Q   Median       3Q      Max 
-1.79460 -0.26316  0.09027  0.32698  1.58269 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)  
(Intercept)   4.1739     3.3100   1.261   0.2428  
x             0.8331     0.3323   2.507   0.0365 *
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.9492 on 8 degrees of freedom
Multiple R-squared:   0.44,	Adjusted R-squared:   0.37 
F-statistic: 6.287 on 1 and 8 DF,  p-value: 0.03652
> 
```

* Next, we calculate the so-called "hat matrix", $\bf{H}$ which helps us to calculate some important quantities related to the error term of the regression:

```R
H <- X%*%solve(t(X)%*%X)%*%t(X)
e <- y-H%*%y
ess <- t(e)%*%e
tss <- sum((y-mean(y))^2)
rsq <- 1-(ess/tss)
rsq
mse <- ess/(10-2)
mse
sqrt(mse)
```

* Output:
  
```Rout
> H <- X%*%solve(t(X)%*%X)%*%t(X)
> e <- y-H%*%y
> ess <- t(e)%*%e
> tss <- sum((y-mean(y))^2)
> rsq <- 1-(ess/tss)
> rsq
          [,1]
[1,] 0.4400409
> mse <- ess/(10-2)
> mse
         [,1]
[1,] 0.901062
> sqrt(mse)
          [,1]
[1,] 0.9492428
> 
```

* Then, we calculate the variance-covariance matrix of the parameter estimates by:

```R
V <- as.vector(mse)*solve(t(X)%*%X)
V
sqrt(diag(V))
summary(lm(y~1+x))
```

* Output:

```Rout
> V <- as.vector(mse)*solve(t(X)%*%X)
> V
          o          x
o 10.955882 -1.0952135
x -1.095214  0.1103918
> sqrt(diag(V))
        o         x 
3.3099671 0.3322526 
>
> summary(lm(y~1+x))

Call:
lm(formula = y ~ 1 + x)

Residuals:
     Min       1Q   Median       3Q      Max 
-1.79460 -0.26316  0.09027  0.32698  1.58269 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)  
(Intercept)   4.1739     3.3100   1.261   0.2428  
x             0.8331     0.3323   2.507   0.0365 *
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.9492 on 8 degrees of freedom
Multiple R-squared:   0.44,	Adjusted R-squared:   0.37 
F-statistic: 6.287 on 1 and 8 DF,  p-value: 0.03652
```

#### Topic 24: 2 Continuous Variables

* Let's work with the more complicated example of 2 predictor variables:

```R
set.seed(17)
x1 <- rnorm(n=7,mean=10,sd=1)
x2 <- x1+rnorm(n=7,mean=10,sd=1)
y <- x1+x2+rnorm(n=7,mean=0,sd=3)
x0 <- rep(1,7)
X <- cbind(x0,x1,x2)
X
B <- solve(t(X)%*%X)%*%t(X)%*%y
B
H <- X%*%solve(t(X)%*%X)%*%t(X)
e <- y-H%*%y
ess <- t(e)%*%e
tss <- sum((y-mean(y))^2)
rsq <- 1-(ess/tss)
rsq
mse <- ess/(7-3)
mse
sqrt(mse)
summary(lm(y~1+x1+x2))
```

* Output:

```Rout
> set.seed(17)
> x1 <- rnorm(n=7,mean=10,sd=1)
> x2 <- x1+rnorm(n=7,mean=10,sd=1)
> y <- x1+x2+rnorm(n=7,mean=0,sd=3)
> x0 <- rep(1,7)
> X <- cbind(x0,x1,x2)
> X
     x0        x1       x2
[1,]  1  8.984991 20.70153
[2,]  1  9.920363 20.17560
[3,]  1  9.767013 20.13359
[4,]  1  9.182732 20.36352
[5,]  1 10.772091 21.41528
[6,]  1  9.834388 21.12971
[7,]  1 10.972874 21.16079
> B <- solve(t(X)%*%X)%*%t(X)%*%y
> B
          [,1]
x0 -24.6124172
x1  -0.2922613
x2   2.8985224
> H <- X%*%solve(t(X)%*%X)%*%t(X)
> e <- y-H%*%y
> ess <- t(e)%*%e
> tss <- sum((y-mean(y))^2)
> rsq <- 1-(ess/tss)
> rsq
          [,1]
[1,] 0.5228371
> mse <- ess/(7-3)
> mse
         [,1]
[1,] 2.618174
> sqrt(mse)
         [,1]
[1,] 1.618077
> summary(lm(y~1+x1+x2))

Call:
lm(formula = y ~ 1 + x1 + x2)

Residuals:
      1       2       3       4       5 
 1.6947 -1.0372  1.5253 -1.7036 -0.2468 
      6       7 
-0.8935  0.6611 

Coefficients:
            Estimate Std. Error t value
(Intercept) -24.6124    27.8773  -0.883
x1           -0.2923     1.1210  -0.261
x2            2.8985     1.5993   1.812
            Pr(>|t|)
(Intercept)    0.427
x1             0.807
x2             0.144

Residual standard error: 1.618 on 4 degrees of freedom
Multiple R-squared:  0.5228,	Adjusted R-squared:  0.2843 
F-statistic: 2.191 on 2 and 4 DF,  p-value: 0.2277

> 
```

* Next, calculate the variance-covariance matrix of the parameter estimates by:

```R
V <- as.vector(mse)*solve(t(X)%*%X)
V
sqrt(diag(V))
summary(lm(y~1+x1+x2))
```

* Here is our output:

```Rout
> V <- as.vector(mse)*solve(t(X)%*%X)
> V
           x0        x1         x2
x0 777.141461  9.997214 -42.263041
x1   9.997214  1.256680  -1.083797
x2 -42.263041 -1.083797   2.557858
> sqrt(diag(V))
       x0        x1        x2 
27.877257  1.121017  1.599331 
> summary(lm(y~1+x1+x2))

Call:
lm(formula = y ~ 1 + x1 + x2)

Residuals:
      1       2       3       4       5 
 1.6947 -1.0372  1.5253 -1.7036 -0.2468 
      6       7 
-0.8935  0.6611 

Coefficients:
            Estimate Std. Error t value
(Intercept) -24.6124    27.8773  -0.883
x1           -0.2923     1.1210  -0.261
x2            2.8985     1.5993   1.812
            Pr(>|t|)
(Intercept)    0.427
x1             0.807
x2             0.144

Residual standard error: 1.618 on 4 degrees of freedom
Multiple R-squared:  0.5228,	Adjusted R-squared:  0.2843 
F-statistic: 2.191 on 2 and 4 DF,  p-value: 0.2277

>
```

### Assignment #3 (Due on ELMS at 11:59pm on Thursday 4/24/25)

Instructions: please review the guidelines for assignments and submission of assignments in the syllabus above. You should not discuss this assignment with others; the work you submit should be your own work. If I receive questions related to the assignment that I judge to be of interest to the entire class, I will post them below with the answers. I will respond to all questions submitted by 11:59pm (ET) on Monday 4/21/25. I will not be able to respond to any questions received after that time (so that all students will have ample time to take such questions into consideration before the submission deadline). Each problem below is worth 5 points. Good luck!

Dataset #1:

```R
set.seed(847)
g <- c(rep(0,1800),rep(1,350))
y <- 12+1/3*g+rnorm(n=2150,mean=0,sd=1+2*g)
```

* 1.1: Estimate a linear regression model with *y* as the outcome variable and *g* as the independent variable.
* 1.2: Create a boxplot showing the distribution of *y* conditional on the 2 levels of *g*. Create a second boxplot in the same plotspace showing the conditional distribution of the square root of the absolute values of the standardized residuals from the regression for each level of *g*. Comment on the pattern you observe in these 2 boxplots.
* 1.3: Calculate a 95% confidence interval for the slope coefficient for this regression. Comment on whether this confidence interval includes zero.
* 1.4: Estimate a regression of the square root of the absolute values of the standardized residuals on the independent variable, *g*. Then, calculate a Breusch-Pagan test of homoscedasticity. What do these diagnostics tell you about whether the null hypothesis of homoscedasticity should be rejected?
* 1.5: Use White's heteroscedasticity consistent covariance matrix to create a new 95% confidence interval for the slope coefficient. Comment on whether this confidence interval includes zero.
* 1.6: Use the weighted least squares (approach #1) to estimate the linear regression adjusted for heteroscedasticity. Then create a new 95% confidence interval for the slope coefficient. Comment on whether this confidence interval includes zero.
* 1.7: Comment on the effect that heteroscedasticity has on our inference about the slope coefficient in this dataset.

Dataset #2: Read in our ih.csv dataset. Calculate the percent of the population that is considered to be undocumented immigrant status for the year 2022 (based on i22 and p22) for each state; then calculate the 2022 homicide rate for each state (based on h22 and p22). Let's call the independent variable *ip* and the outcome variable *hr*.

* 2.1: Estimate a linear regression where *ip* is the independent variable and *hr* is the outcome variable.
* 2.2: Create a 3-panel plot window with a scatterplot and regression line for the relationship between *ip* and *hr*; a scatterplot of the residuals against the independent variable; and a plot of the square root of the absolute values of the standardized residuals against the independent variable.
* 2.3: Create a scatterplot of the leverage statistics against the standardized residuals. Draw horizontal and vertical lines at the appropriate cutoff points. Identify states that have high leverage or high standardized residuals (outliers).
* 2.4: Indicate which, if any, states qualify as both high leverage and as outliers; if there are, explain what you would do next.
* 2.5: Using the same dataset, estimate linear and quadratic regression models for the relationship between *ip* and *hr*.
* 2.6: Create a scatterplot of the *ip* and *hr* datapoints. Add the regression line for the linear model and the appropriate nonlinear function for the quadratic model to the plotspace.
* 2.7: Calculate Δ = E(y|x=3)-E(y|x=2) for the linear model along with a 82% confidence interval for that estimate. Comment on whether the confidence interval includes zero.
* 2.8: Calculate Δ = E(y|x=3)-E(y|x=2) for the quadratic model along with a 82% confidence interval for that estimate. Comment on whether the confidence interval includes zero.
* 2.9: Write a statement where you intepret what you have learned from 2.7-2.8.
* 2.10: Create a $\bf{X}$ matrix using a column of 1's and the independent variable, *ip*; Create a $\bf{Y}$ vector using *hr*. With these in hand, use matrix arithmetic to estimate the linear regression intercept and slope estimates; confirm that you get the same results using the lm() function.
* 2.11: Use the hat matrix, $\bf{H}$, to estimate the R-squared, mean square error, and root mean square error for the linear regression; then, using the regression mean square error, the hat matrix, and the $\bf{X}$ matrix, calculate the variance-covariance matrix of the parameter estimates. Use this matrix to calculate the standard errors of the intercept and slope terms;  confirm that these standard errors match the standard errors from the lm() function.
* 2.12: Create a $\bf{X}$ matrix using a column of 1's, the independent variable, *ip*, and the squared *ip*; Create a $\bf{Y}$ vector using *hr*. With these in hand, use matrix arithmetic to estimate the quadratic regression intercept and slope estimates; confirm that you get the same results using the lm() function.
* 2.13: Use the hat matrix, $\bf{H}$, to estimate the R-squared, mean square error, and root mean square error for the quadratic regression; Then, using the regression mean square error, the hat matrix, and the $\bf{X}$ matrix, calculate the variance-covariance matrix of the parameter estimates. Use this matrix to calculate the standard errors of the intercept and slope terms; confirm that these standard errors match the standard errors from the lm() function.

#### Questions for Assignment #3

1. For question 2.5, concerning the estimation of the linear regression model, do you expect to use the lm() function again (which was already done in #2.1)? My response: Yes, the linear regression model will be the same; the quadratic regression will be new. 
2. For question 2.6, I know in class we discussed that there should be three lines (quadratic function, data point line, and regression line). Just to clarify, shouldn’t it be only two lines (regression line, quadratic function line)? My response: For this question, what I meant to say was that should be 3 things in the plotspace: the individual data point, the regression line and the quadratic function.

### Lesson 12 - Monday 4/21/25

* Today, we will be workin on topics 25 (1 continuous/1 binary independent variable).
* We begin by reading in our homicide dataset:

```R
d <- read.csv(file="ih.csv",sep=",",header=T)
head(d)
ncases <- nrow(d)
x0 <- rep(1,ncases)
y <- (d$h18/d$p18)*100000
ir <- (d$i18/d$p18)*100
```

---

```Rout
> d <- read.csv(file="ih.csv",sep=",",header=T)
> head(d)
       state  h18 u18      p18     i18 moe18  h19 u19
1    alabama  560  69  4887871   60000 10000  579  51
2     alaska   56  32   737438   10000  5000   76  27
3    arizona  411 150  7171646  275000 20000  412 149
4   arkansas  257  61  3013825   70000  5000  264  60
5 california 1848 234 39557045 1950000 70000 1766 222
6   colorado  269  53  5695564  170000 20000  247  53
       p19     i19 moe19  h21 u21      p21     i21 moe21
1  4903185   60000 10000  750  89  5039877   60000 10000
2   731545   10000  5000   48  31   732673    5000  5000
3  7278717  250000 25000  546 186  7276316  250000 20000
4  3017804   70000  5000  326  77  3025891   70000  5000
5 39512223 1900000 65000 2475 232 39237836 1850000 65000
6  5758736  170000 15000  374  76  5812069  160000 15000
   h22 u22      p22     i22 moe22
1  702  70  5074296   65000 10000
2   74  31   733583   10000  5000
3  625 162  7359197  250000 20000
4  322  72  3045637   70000 10000
5 2228 251 39029342 1800000 75000
6  412  68  5839926  170000 15000
> ncases <- nrow(d)
>
> x0 <- rep(1,ncases)
> y <- (d$h18/d$p18)*100000
> ir <- (d$i18/d$p18)*100
```

---

* Next, we create a binary/dummy variable (terms used interchangeably) to indicate whether each state is in the U.S. Census "South" region.

```R
rg <- rep(0,ncases)
rg[d$state=="alabama"] <- 1
rg[d$state=="arkansas"] <- 1
rg[d$state=="delaware"] <- 1
rg[d$state=="florida"] <- 1
rg[d$state=="georgia"] <- 1
rg[d$state=="kentucky"] <- 1
rg[d$state=="louisiana"] <- 1
rg[d$state=="maryland"] <- 1
rg[d$state=="mississippi"] <- 1
rg[d$state=="north carolina"] <- 1
rg[d$state=="oklahoma"] <- 1
rg[d$state=="south carolina"] <- 1
rg[d$state=="tennessee"] <- 1
rg[d$state=="texas"] <- 1
rg[d$state=="virginia"] <- 1
rg[d$state=="west virginia"] <- 1

data.frame(d$state,x0,y,ir,rg)[1:3,]
```

---

```Rout
> data.frame(d$state,x0,y,ir,rg)[1:3,]
  d.state x0         y       ir rg
1 alabama  1 11.456931 1.227528  1
2  alaska  1  7.593859 1.356046  0
3 arizona  1  5.730902 3.834545  0
>
```

---

* Next, we set up our matrix solution:

```R
# comparing matrix solution to output from lm()

X <- cbind(x0,ir,rg)
X
B <- solve(t(X)%*%X)%*%t(X)%*%y
B
H <- X%*%solve(t(X)%*%X)%*%t(X)
e <- y-H%*%y
ess <- t(e)%*%e
tss <- sum((y-mean(y))^2)
rsq <- 1-(ess/tss)
rsq
mse <- ess/(ncases-3)
mse
sqrt(mse)
V <- as.vector(mse)*solve(t(X)%*%X)
V
sqrt(diag(V))

# lm results

Mr <- lm(y~1+ir+rg)
summary(Mr)
B <- coef(Mr)
B
V <- vcov(Mr)
V
sqrt(diag(V))
```

---

```Rout
> # comparing matrix solution to output from lm()
> 
> X <- cbind(x0,ir,rg)
> X
      x0        ir rg
 [1,]  1 1.2275283  1
 [2,]  1 1.3560462  0
 [3,]  1 3.8345451  0
 [4,]  1 2.3226299  1
 [5,]  1 4.9295897  0
 [6,]  1 2.9847790  0
 [7,]  1 3.9186434  0
 [8,]  1 3.1018300  1
 [9,]  1 3.7559876  1
[10,]  1 3.5648167  1
[11,]  1 3.1679187  0
[12,]  1 2.2802313  0
[13,]  1 3.1394513  0
[14,]  1 1.6437837  0
[15,]  1 1.7426322  0
[16,]  1 2.5759873  0
[17,]  1 1.0070714  1
[18,]  1 1.5021530  1
[19,]  1 0.3735046  0
[20,]  1 4.5509322  1
[21,]  1 3.9842663  0
[22,]  1 1.2004904  0
[23,]  1 1.5148332  0
[24,]  1 0.8370919  1
[25,]  1 0.9793597  0
[26,]  1 0.4705805  0
[27,]  1 2.8508222  0
[28,]  1 6.9206615  0
[29,]  1 1.1058212  0
[30,]  1 4.7707139  0
[31,]  1 2.6247621  0
[32,]  1 3.0702773  0
[33,]  1 3.1299296  1
[34,]  1 0.6578281  0
[35,]  1 0.9410201  0
[36,]  1 2.2824803  1
[37,]  1 2.6248517  0
[38,]  1 1.4835567  0
[39,]  1 3.3102718  0
[40,]  1 1.7702154  1
[41,]  1 1.1334848  0
[42,]  1 1.9202335  1
[43,]  1 5.5745545  1
[44,]  1 3.1634508  0
[45,]  1 0.7981811  0
[46,]  1 3.5220838  1
[47,]  1 3.9811078  0
[48,]  1 0.2768253  1
[49,]  1 1.3760912  0
[50,]  1 0.8654457  0
> B <- solve(t(X)%*%X)%*%t(X)%*%y
> B
         [,1]
x0  4.7021615
ir -0.1901654
rg  3.6427028
> H <- X%*%solve(t(X)%*%X)%*%t(X)
> e <- y-H%*%y
> ess <- t(e)%*%e
> tss <- sum((y-mean(y))^2)
> rsq <- 1-(ess/tss)
> rsq
          [,1]
[1,] 0.3258868
> mse <- ess/(ncases-3)
> mse
        [,1]
[1,] 6.44657
> sqrt(mse)
        [,1]
[1,] 2.53901
> V <- as.vector(mse)*solve(t(X)%*%X)
> V
           x0           ir           rg
x0  0.5394380 -0.145451816 -0.172659734
ir -0.1454518  0.060475235 -0.007045421
rg -0.1726597 -0.007045421  0.593336443
> sqrt(diag(V))
       x0        ir        rg 
0.7344644 0.2459171 0.7702834 
> 
> # lm results
> 
> Mr <- lm(y~1+ir+rg)
> summary(Mr)

Call:
lm(formula = y ~ 1 + ir + rg)

Residuals:
   Min     1Q Median     3Q    Max 
-3.137 -1.966 -1.083  1.518  6.698 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   4.7022     0.7345   6.402 6.61e-08 ***
ir           -0.1902     0.2459  -0.773    0.443    
rg            3.6427     0.7703   4.729 2.09e-05 ***
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.539 on 47 degrees of freedom
Multiple R-squared:  0.3259,	Adjusted R-squared:  0.2972 
F-statistic: 11.36 on 2 and 47 DF,  p-value: 9.445e-05

> B <- coef(Mr)
> B
(Intercept)          ir          rg 
  4.7021615  -0.1901654   3.6427028 
> V <- vcov(Mr)
> V
            (Intercept)           ir           rg
(Intercept)   0.5394380 -0.145451816 -0.172659734
ir           -0.1454518  0.060475235 -0.007045421
rg           -0.1726597 -0.007045421  0.593336443
>
> sqrt(diag(V))
(Intercept)          ir          rg 
  0.7344644   0.2459171   0.7702834 
> 
```

---

* Now, we calculate the expected homicide rate (and 92% confidence interval for the expected rate) for southern states when the immigration rate is set to (held constant at) the sample median value.

```R
md.ir <- median(ir)
md.ir
ey.southern <- coef(Mr)[1]+coef(Mr)[2]*md.ir+coef(Mr)[3]*1
ey.southern
nd <- data.frame(ir=2.302555,rg=1)
predict(Mr,newdata=nd,interval="confidence",level=0.92)
```

---

```Rout
> md.ir <- median(ir)
> md.ir
[1] 2.302555
> ey.southern <- coef(Mr)[1]+coef(Mr)[2]*md.ir+coef(Mr)[3]*1
> ey.southern
(Intercept) 
   7.906998 
> nd <- data.frame(ir=2.302555,rg=1)
> predict(Mr,newdata=nd,interval="confidence",level=0.92)
       fit      lwr      upr
1 7.906998 6.767107 9.046889
>
```

---

* Next, we consider the expected homicide rate (and 92% confidence interval for the expected rate) for other states (again, with the immigration rate set to its sample median value:

```R
nd <- data.frame(ir=2.302555,rg=0)
predict(Mr,newdata=nd,interval="confidence",level=0.92)
```

---

```Rout
> nd <- data.frame(ir=2.302555,rg=0)
> predict(Mr,newdata=nd,interval="confidence",level=0.92)
       fit      lwr      upr
1 4.264295 3.483831 5.044759
>
```

* There is clearly no overlap in these confidence intervals which confirms the inference from the linear regression model where we observed a positive and statistically significant main effect for the region variable (rg).
* Our next task is to demonstrate that we can get similar results by drawing coefficients from a multivariate *t* distribution with degrees of freedom equal to the number of cases minus the number of regression coefficients estimated (including the intercept term).
* First, we estimate the 92% confidence interval for southern states:

```R
library(mvnfast)
D <- Mr$df.residual
sb <- rmvt(n=1e5,mu=B,sigma=V,df=D)
ey.sb.south <- sb[,1]+sb[,2]*md.ir+sb[,3]
quantile(ey.sb.south,0.04)
quantile(ey.sb.south,0.96)
```

---

```Rout
> library(mvnfast)
> D <- Mr$df.residual
> sb <- rmvt(n=1e5,mu=B,sigma=V,df=D)
> ey.sb.south <- sb[,1]+sb[,2]*md.ir+sb[,3]
> quantile(ey.sb.south,0.04)
      4% 
6.764685 
> quantile(ey.sb.south,0.96)
     96% 
9.048475 
>
```

---

* Then, we perform the same set of calculations for "non-south" region states:

```R
ey.sb.oth <- sb[,1]+sb[,2]*md.ir
quantile(ey.sb.oth,0.04)
quantile(ey.sb.oth,0.96)
```

---

```Rout
> ey.sb.oth <- sb[,1]+sb[,2]*md.ir
> quantile(ey.sb.oth,0.04)
      4% 
3.483547 
> quantile(ey.sb.oth,0.96)
     96% 
5.047166 
> 
```

* Note that this is just to confirm that we can get the same results as the predict() function using simulation.
* Now, we estimate the 92% confidence interval for the difference between the 2 expectations:

```R
delta <- ey.sb.south-ey.sb.oth
quantile(delta,0.04)
quantile(delta,0.96)
```

---

```Rout
> delta <- ey.sb.south-ey.sb.oth
> quantile(delta,0.04)
      4% 
2.262114 
> quantile(delta,0.96)
    96% 
5.02692 
>
```

* So, this is giving us an estimate of the 92% confidence interval for the difference between the expectation for the southern states and the other states when the immigration rate is held constant at the sample median. Since this confidence interval does not include zero, the null hypothesis (Ho) that delta = 0 must be rejected (at the 92% confidence level).

### Lesson 13 - Monday 4/28/25

* Today, we cover topics 26 (interaction effects) and 28 (likelihood ratio and F-tests)
* We begin with Topic 26
* So, now we have 2 models: 1 without an interaction term (the restricted model) and 1 with an interaction term (the unrestricted model).

#### Topic 26: Interaction Effects

* We begin this unit by elaborating the model in the previous section to include an interaction term.
* One way to think about the model we are about to estimate.
* Think about a regression coefficient that measures the amount of change we expect to see in the homicide rate for a 1-unit change (1 percentage point) in the percentage of the population that is an undocumented immigrant (again, these estimates are based on demographic research conducted by the Pew Center). Let's call that regression coefficient, θ.
* Now, let's think about a constrained (no interaction model), where our estimate of θr is assumed to apply to all the states (we will call this model, Mr).
* Next, let's think about an interaction model, Mi, where we relax the constraint that there is one θr and allow for the possibility that there are two different values of θ -- one for southern states, θs, and one for non-southern states, θns.
* We will estimate both models; then we will conduct a F-test ([link](https://sites.duke.edu/bossbackup/files/2013/02/FTestTutorial.pdf)) and a likelihood ratio test ([link; section 8](https://www.stat.cmu.edu/~larry/=stat705/Lecture16.pdf)) to adjudicate between them.
* The interaction model allows us to estimate these separate values of θ and also allows us to estimate the difference between them (along with a confidence interval -- we will use a 82% confidence interval -- for the difference).


```R
d <- read.csv(file="ih.csv",sep=",",header=T)
head(d)
y <- (d$h18/d$p18)*100000
ir <- (d$i18/d$p18)*100
rg <- rep(0,50)
rg[d$state=="alabama"] <- 1
rg[d$state=="arkansas"] <- 1
rg[d$state=="delaware"] <- 1
rg[d$state=="florida"] <- 1
rg[d$state=="georgia"] <- 1
rg[d$state=="kentucky"] <- 1
rg[d$state=="louisiana"] <- 1
rg[d$state=="maryland"] <- 1
rg[d$state=="mississippi"] <- 1
rg[d$state=="north carolina"] <- 1
rg[d$state=="oklahoma"] <- 1
rg[d$state=="south carolina"] <- 1
rg[d$state=="tennessee"] <- 1
rg[d$state=="texas"] <- 1
rg[d$state=="virginia"] <- 1
rg[d$state=="west virginia"] <- 1
Mr <- lm(y~1+ir+rg)
summary(Mr)
Mi <- lm(y~1+ir+rg+ir*rg)
summary(Mi)
```

---

```Rout
> d <- read.csv(file="ih.csv",sep=",",header=T)
> head(d)
       state  h18 u18      p18     i18 moe18  h19 u19
1    alabama  560  69  4887871   60000 10000  579  51
2     alaska   56  32   737438   10000  5000   76  27
3    arizona  411 150  7171646  275000 20000  412 149
4   arkansas  257  61  3013825   70000  5000  264  60
5 california 1848 234 39557045 1950000 70000 1766 222
6   colorado  269  53  5695564  170000 20000  247  53
       p19     i19 moe19  h21 u21      p21     i21 moe21
1  4903185   60000 10000  750  89  5039877   60000 10000
2   731545   10000  5000   48  31   732673    5000  5000
3  7278717  250000 25000  546 186  7276316  250000 20000
4  3017804   70000  5000  326  77  3025891   70000  5000
5 39512223 1900000 65000 2475 232 39237836 1850000 65000
6  5758736  170000 15000  374  76  5812069  160000 15000
   h22 u22      p22     i22 moe22
1  702  70  5074296   65000 10000
2   74  31   733583   10000  5000
3  625 162  7359197  250000 20000
4  322  72  3045637   70000 10000
5 2228 251 39029342 1800000 75000
6  412  68  5839926  170000 15000
> y <- (d$h18/d$p18)*100000
> ir <- (d$i18/d$p18)*100
> rg <- rep(0,50)
> rg[d$state=="alabama"] <- 1
> rg[d$state=="arkansas"] <- 1
> rg[d$state=="delaware"] <- 1
> rg[d$state=="florida"] <- 1
> rg[d$state=="georgia"] <- 1
> rg[d$state=="kentucky"] <- 1
> rg[d$state=="louisiana"] <- 1
> rg[d$state=="maryland"] <- 1
> rg[d$state=="mississippi"] <- 1
> rg[d$state=="north carolina"] <- 1
> rg[d$state=="oklahoma"] <- 1
> rg[d$state=="south carolina"] <- 1
> rg[d$state=="tennessee"] <- 1
> rg[d$state=="texas"] <- 1
> rg[d$state=="virginia"] <- 1
> rg[d$state=="west virginia"] <- 1
> Mr <- lm(y~1+ir+rg)
> summary(Mr)

Call:
lm(formula = y ~ 1 + ir + rg)

Residuals:
   Min     1Q Median     3Q    Max 
-3.137 -1.966 -1.083  1.518  6.698 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   4.7022     0.7345   6.402 6.61e-08 ***
ir           -0.1902     0.2459  -0.773    0.443    
rg            3.6427     0.7703   4.729 2.09e-05 ***
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.539 on 47 degrees of freedom
Multiple R-squared:  0.3259,	Adjusted R-squared:  0.2972 
F-statistic: 11.36 on 2 and 47 DF,  p-value: 9.445e-05

> Mi <- lm(y~1+ir+rg+ir*rg)
> summary(Mi)

Call:
lm(formula = y ~ 1 + ir + rg + ir * rg)

Residuals:
    Min      1Q  Median      3Q     Max 
-4.1453 -1.9231 -0.8155  1.7757  7.0562 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  4.09757    0.81564   5.024 8.12e-06 ***
ir           0.06121    0.28858   0.212 0.832958    
rg           5.74730    1.51933   3.783 0.000446 ***
ir:rg       -0.84623    0.52947  -1.598 0.116837    
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.498 on 46 degrees of freedom
Multiple R-squared:  0.3614,	Adjusted R-squared:  0.3197 
F-statistic: 8.676 on 3 and 46 DF,  p-value: 0.0001136

>
```

---

* So, now we have our 2 models, Mr and Mi.
* How do we decide which model is more consistent with the data?
* One way is to calculate a F-test.

```R
ssMr <- sum(residuals(Mr)^2)
ssMr
ssMi <- sum(residuals(Mi)^2)
ssMi
dfMr <- 50-3
dfMr
dfMi <- 50-4
dfMi
ts.num <- (ssMr-ssMi)/(dfMr-dfMi)
ts.den <- ssMi/dfMi
ts.ratio <- ts.num/ts.den
ts.ratio

# critical F value at the 82% confidence level

qf(p=0.82,df1=dfMr-dfMi,df2=dfMi)

# we can also use the anova() function to get a p-value

anova(Mr,Mi)
```

---

```Rout
> ssMr <- sum(residuals(Mr)^2)
> ssMr
[1] 302.9888
> ssMi <- sum(residuals(Mi)^2)
> ssMi
[1] 287.049
> dfMr <- 50-3
> dfMr
[1] 47
> dfMi <- 50-4
> dfMi
[1] 46
> ts.num <- (ssMr-ssMi)/(dfMr-dfMi)
> ts.den <- ssMi/dfMi
> ts.ratio <- ts.num/ts.den
> ts.ratio
[1] 2.554368
> 
> # critical F value at the 82% confidence level
> 
> qf(p=0.82,df1=dfMr-dfMi,df2=dfMi)
[1] 1.853574
> 
> # we can also use the anova() function to get a p-value
> 
> anova(Mr,Mi)
Analysis of Variance Table

Model 1: y ~ 1 + ir + rg
Model 2: y ~ 1 + ir + rg + ir * rg
  Res.Df    RSS Df Sum of Sq      F Pr(>F)
1     47 302.99                           
2     46 287.05  1     15.94 2.5544 0.1168
>
```

---

* Another approach is to use a likelihood ratio test:

```R
# extract log-likelihood values from model objects (Mr and Mi)

logLik(Mr)
logLik(Mi)

# test statistic is 2 x the difference between the two log-likelihood values
# degrees of freedom is the difference between the number of parameters estimated
# for each statistical model.

ts <- 2*(115.9887-114.6377)
ts
qchisq(p=0.82,df=5-4)
```

---

```Rout
> # extract log-likelihood values from model objects (Mr and Mi)
> 
> logLik(Mr)
'log Lik.' -115.9887 (df=4)
> logLik(Mi)
'log Lik.' -114.6377 (df=5)
> 
> # test statistic is 2 x the difference between the two log-likelihood values
> # degrees of freedom is the difference between the number of parameters estimated
> # for each statistical model.
> 
> ts <- 2*(115.9887-114.6377)
> ts
[1] 2.702
> qchisq(p=0.82,df=5-4)
[1] 1.797624
>
```

* Using both the F-test and the likelihood-ratio tests, we reject Ho and conclude that the interaction model is more consistent with the data (at the 82% confidence level).
* Now, that we have evidence in favor of the interaction model, we turn to the interpretation of the interaction effect.

---

* We begin by computing the expected outcomes for different levels of immigration and Census regions:

```R
irs <- 1:7
rgs <- 0:1
g <- expand.grid(irs=irs,rgs=rgs)
g$yhat <- coef(Mi)[1]+coef(Mi)[2]*g$irs+coef(Mi)[3]*g$rgs+coef(Mi)[4]*g$irs*g$rgs
g
```

---

```Rout
> irs <- 1:7
> rgs <- 0:1
> g <- expand.grid(irs=irs,rgs=rgs)
> g$yhat <- coef(Mi)[1]+coef(Mi)[2]*g$irs+coef(Mi)[3]*g$rgs+coef(Mi)[4]*g$irs*g$rgs
> g
   irs rgs     yhat
1    1   0 4.158776
2    2   0 4.219987
3    3   0 4.281197
4    4   0 4.342408
5    5   0 4.403618
6    6   0 4.464829
7    7   0 4.526039

8    1   1 9.059850
9    2   1 8.274835
10   3   1 7.489821
11   4   1 6.704806
12   5   1 5.919792
13   6   1 5.134777
14   7   1 4.349763
>
```

* Notice that for southern region states, θs appears to be negative (as immigration rates increase, homicide rates are expected to drop); for the other states, there appears to be a weak positive relationship (θns > 0, but just barely).
* Let's suppose we want to look at θs and θns when immigration goes from 2 to 3.
* We can calculate the point estimates of these 2 numbers: θs = 7.490-8.275 = -0.785 and θns = 4.281-4.220 = 0.061. We can also think about an estimate, Δ = θs - θns = -0.785-0.061 = -0.846.
* With this table, we have the expected homicide rates for different levels of immigration and the two regions but we do not have any measure of uncertainty for these estimates.


* We begin by collecting the parameter estimates and variance covariance matrices; then we simulate coefficients:

```R
Bi <- coef(Mi)
Bi
Vi <- vcov(Mi)
Vi
D <- Mi$df.residual
D

library(mvnfast)
sb <- rmvt(n=1e5,mu=Bi,sigma=Vi,df=D)
```

---

* Here is our output:

```Rout
> Bi <- coef(Mi)
> Bi
(Intercept)          ir          rg       ir:rg 
 4.09756549  0.06121054  5.74729876 -0.84622506 
> Vi <- vcov(Mi)
> Vi
            (Intercept)          ir         rg       ir:rg
(Intercept)   0.6652715 -0.20029392 -0.6652715  0.20029392
ir           -0.2002939  0.08327721  0.2002939 -0.08327721
rg           -0.6652715  0.20029392  2.3083617 -0.69722217
ir:rg         0.2002939 -0.08327721 -0.6972222  0.28034211
>
> D <- Mi$df.residual
> D
[1] 46
>
```

---

* Next, we calculate estimates of θs and θns when immigration goes from 2 to 3:

```R
ey.sb.s.i2 <- sb[,1]+sb[,2]*2+sb[,3]+sb[,4]*1*2
ey.sb.s.i3 <- sb[,1]+sb[,2]*3+sb[,3]+sb[,4]*1*3
theta.s <- ey.sb.s.i3-ey.sb.s.i2
mean(theta.s)

ey.sb.ns.i2 <- sb[,1]+sb[,2]*2
ey.sb.ns.i3 <- sb[,1]+sb[,2]*3
theta.ns <- ey.sb.ns.i3-ey.sb.ns.i2
mean(theta.ns)
```

---

```Rout
> ey.sb.s.i2 <- sb[,1]+sb[,2]*2+sb[,3]+sb[,4]*1*2
> ey.sb.s.i3 <- sb[,1]+sb[,2]*3+sb[,3]+sb[,4]*1*3
> theta.s <- ey.sb.s.i3-ey.sb.s.i2
> mean(theta.s)
[1] -0.7845834
> 
> ey.sb.ns.i2 <- sb[,1]+sb[,2]*2
> ey.sb.ns.i3 <- sb[,1]+sb[,2]*3
> theta.ns <- ey.sb.ns.i3-ey.sb.ns.i2
> mean(theta.ns)
[1] 0.06138246
>
```

* Notice these means coincide with the expected values we calculated earlier.
* Now, we calculate 82% confidence intervals for θs, θns, and Δ (all at the 82% confidence level).

```R
quantile(theta.s,c(0.09,0.91))
quantile(theta.ns,c(0.09,0.91))
quantile(theta.s-theta.ns,c(0.09,0.91))
```

* Here is our output:

```Rout
> quantile(theta.s,c(0.09,0.91))
       9%       91% 
-1.386030 -0.182235 
> quantile(theta.ns,c(0.09,0.91))
        9%        91% 
-0.3310341  0.4524287 
> quantile(theta.s-theta.ns,c(0.09,0.91))
        9%        91% 
-1.5637758 -0.1279633 
>
```

* Notice that the confidence interval for θs is strictly negative while the confidence interval for θns includes zero; the confidence interval for, Δ, the difference between θs and θns is strictly negative which leads to the conclusion that there is a significant difference between the two θ estimates at the 82% confidence level.
* An important assumption made by this model, Mi, is that the variance of the error term is constant (homoscedasticity). In other words, we have allowed the θ estimates to vary by region but we've constrained the error variances to be the same. One way to relax this assumption is to estimate separate models for each region.
* Let's do that now.

```R
dcombined <- data.frame(y,ir,rg)
dsouth <- subset(dcombined,rg==1)
dnonsouth <- subset(dcombined,rg==0)
Ms <- lm(y~1+ir,data=dsouth)
summary(Ms)
Mns <- lm(y~1+ir,data=dnonsouth)
summary(Mns)
```

* Here is our output (notice some familiar numbers for the slope coefficient for *ir* in each set of estimates):

```Rout
> dcombined <- data.frame(y,ir,rg)
> dsouth <- subset(dcombined,rg==1)
> dnonsouth <- subset(dcombined,rg==0)
> Mi <- lm(y~1+ir,data=dsouth)
> summary(Ms)

Call:
lm(formula = y ~ 1 + ir, data = dsouth)

Residuals:
   Min     1Q Median     3Q    Max 
-4.145 -1.539  0.140  1.276  4.231 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   9.8449     1.2571   7.831 1.75e-06 ***
ir           -0.7850     0.4354  -1.803   0.0929 .  
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.45 on 14 degrees of freedom
Multiple R-squared:  0.1885,	Adjusted R-squared:  0.1305 
F-statistic: 3.251 on 1 and 14 DF,  p-value: 0.09292

> Mns <- lm(y~1+ir,data=dnonsouth)
> summary(Mns)

Call:
lm(formula = y ~ 1 + ir, data = dnonsouth)

Residuals:
    Min      1Q  Median      3Q     Max 
-2.6261 -1.9876 -0.9868  1.7757  7.0562 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  4.09757    0.82243   4.982 2.09e-05 ***
ir           0.06121    0.29098   0.210    0.835    
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.519 on 32 degrees of freedom
Multiple R-squared:  0.001381,	Adjusted R-squared:  -0.02983 
F-statistic: 0.04425 on 1 and 32 DF,  p-value: 0.8347

>
```

* Here is our likelihood ratio test:

```R
logLik(Mi)
logLik(Ms)
logLik(Mns)
```

----

```Rout
> logLik(Mi)
'log Lik.' -114.6377 (df=5)
> logLik(Ms)
'log Lik.' -35.9712 (df=3)
> logLik(Mns)
'log Lik.' -78.62232 (df=3)
> 
```

* In this case, we have 5 parameters estimated in the Mi specification (the intercept, the main effect for immigration rate, the main effect for region, the interaction term between immigration and region, and the root mean square error term).
* Note that the expected value estimates are quite similar to what was estimated before: θs = -0.785 and θns = 0.061; so Δ = θs - θns = -0.785-0.061 = -0.846.
* Each of the 2 group-specific (rg=0, rg=1) regressions has 3 parameter estimates (the intercept, the main effect for immigration rate, and the root mean square error term).
* This means that our *unconstrained* model has a total log-likelihood value of -(35.9712+78.62232) = -114.5935 with 6 parameters estimated (the difference is that we now have 2 rmse parameter estimates instead of 1).
* Here is the likelihood ratio test with 1 degree of freedom:

```R
ts <- 2*(114.6377-114.5935)
ts
qchisq(p=0.82,df=1)
```

---

```Rout
> ts <- 2*(114.6377-114.5935)
> ts
[1] 0.0884
> qchisq(p=0.82,df=1)
[1] 1.797624
> 
```

* With this evidence in hand, it appears there is no significant difference between the Mi model and the (Ms+Mns) model (at the 82% confidence level).
* If the difference had been significant, then we could have explored the implications. For example, we could have calculated a 82% confidence interval for Δ (when the immigration rate goes from 2 to 3).

```R
Bs <- coef(Ms)
Vs <- vcov(Ms)
Ds <- Ms$df.residual
Ds
Bns <- coef(Mns)
Vns <- vcov(Mns)
Dns <- Mns$df.residual
Dns

library(mvnfast)
sbs <- rmvt(n=1e5,mu=Bs,sigma=Vs,df=Ds)
sbns <- rmvt(n=1e5,mu=Bns,sigma=Vns,df=Dns)

ey.sb.s.i2 <- sbs[,1]+sbs[,2]*2
ey.sb.s.i3 <- sbs[,1]+sbs[,2]*3
theta.s <- ey.sb.s.i3-ey.sb.s.i2
mean(theta.s)

ey.sb.ns.i2 <- sbns[,1]+sbns[,2]*2
ey.sb.ns.i3 <- sbns[,1]+sbns[,2]*3
theta.ns <- ey.sb.ns.i3-ey.sb.ns.i2
mean(theta.ns)

mean(theta.s-theta.ns)
quantile(theta.s-theta.ns,c(0.09,0.91))
```

* Here are the results:

```Rout
> Bs <- coef(Ms)
> Vs <- vcov(Ms)
> Ds <- Ms$df.residual
> Ds
[1] 14
> Bns <- coef(Mns)
> Vns <- vcov(Mns)
> Dns <- Mns$df.residual
> Dns
[1] 32
> 
> library(mvnfast)
> sbs <- rmvt(n=1e5,mu=Bs,sigma=Vs,df=Ds)
> sbns <- rmvt(n=1e5,mu=Bns,sigma=Vns,df=Dns)
> 
> ey.sb.s.i2 <- sbs[,1]+sbs[,2]*2
> ey.sb.s.i3 <- sbs[,1]+sbs[,2]*3
> theta.s <- ey.sb.s.i3-ey.sb.s.i2
> mean(theta.s)
[1] -0.7852218
> 
> ey.sb.ns.i2 <- sbns[,1]+sbns[,2]*2
> ey.sb.ns.i3 <- sbns[,1]+sbns[,2]*3
> theta.ns <- ey.sb.ns.i3-ey.sb.ns.i2
> mean(theta.ns)
[1] 0.06220472
> 
> mean(theta.s-theta.ns)
[1] -0.8474265
> quantile(theta.s-theta.ns,c(0.09,0.91))
        9%        91% 
-1.5857804 -0.1093654 
>
```

* Note that the confidence interval for delta (theta.s-theta.ns) is [-1.586,-0.109] which is a little wider than what was estimated before which was [-1.564,-0.128].

### Lesson 14 - Monday 5/5/25

* 4th Assignment will be distributed on Monday 5/12/25 after class is over and will be due on Monday evening 5/19/25 on ELMS.
* Tonight's topic will be statistical mediation (topic 27) and an introduction to the idea of clustering and hierarchical data (topic 29).
* Next week, we will discuss hierarchical data, the linear probability model and normal approximations to confidence intervals for proportions.

---

#### Topic 27: Statistical Mediation

* Related reading (MacKinnon et al., 2007; [link](https://pmc.ncbi.nlm.nih.gov/articles/PMC2819368/pdf/nihms173361.pdf)).
* Our discussion will involve 3 variables: (1) an antecedent variable, *x*; (2) an outcome variable *y*; and (3) a mediating variable *z*.

```R
set.seed(38)
x <- c(rep(0,350),rep(1,350))
z <- rbinom(n=700,size=1,p=x*1/3+(1-x)*2/3)
table(z,x)
y <- 10+z+rnorm(n=700,mean=0,sd=2)
Mr <- lm(y~1+x)
Mf <- lm(y~1+x+z)
summary(Mr)
summary(Mf)
coef(Mf)[2]-coef(Mr)[2]
```

---

```Rout
> set.seed (38)
> x <- c(rep(0,350),rep(1,350))
> z <- rbinom(n=700,size=1,p=x*1/3+(1-x)*2/3)
> table(z,x)
   x
z     0   1
  0 111 235
  1 239 115
> y <- 10+z+rnorm(n=700,mean=0,sd=2)
> Mr <- lm(y~1+x)
> Mf <- lm(y~1+x+z)
> summary(Mr)

Call:
lm(formula = y ~ 1 + x)

Residuals:
    Min      1Q  Median      3Q     Max 
-5.5429 -1.2916  0.0504  1.2648  5.6052 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  10.6080     0.1021 103.869   <2e-16 ***
x            -0.2957     0.1444  -2.047    0.041 *  
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.911 on 698 degrees of freedom
Multiple R-squared:  0.00597,	Adjusted R-squared:  0.004546 
F-statistic: 4.192 on 1 and 698 DF,  p-value: 0.04099

> summary(Mf)

Call:
lm(formula = y ~ 1 + x + z)

Residuals:
    Min      1Q  Median      3Q     Max 
-6.1273 -1.2205  0.0606  1.2313  5.0208 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 10.01359    0.14354  69.761  < 2e-16 ***
x            0.01268    0.15100   0.084    0.933    
z            0.87048    0.15101   5.764 1.23e-08 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.868 on 697 degrees of freedom
Multiple R-squared:  0.0512,	Adjusted R-squared:  0.04848 
F-statistic: 18.81 on 2 and 697 DF,  p-value: 1.11e-08

>
> coef(Mf)[2]-coef(Mr)[2]
        x 
0.3083992 
> 
```

* Test for mediation -- focus on coefficients from linear model:

```R
d <- data.frame(x,z,y)

library(boot)

db <- function(data,i){
  b <- data[i,]
  Mrb <- lm(y~1+x,data=b)
  Mfb <- lm(y~1+x+z,data=b)
  db <- coef(Mfb)[2]-coef(Mrb)[2]
  return(db)
  }

rb <- boot(data=d,statistic=db,R=1e5)
rb
boot.ci(rb,conf=0.92,type="bca",index=1)
```

---

```Rout
> d <- data.frame(x,z,y)
> 
> library(boot)
> 
> db <- function(data,i){
+   b <- data[i,]
+   Mrb <- lm(y~1+x,data=b)
+   Mfb <- lm(y~1+x+z,data=b)
+   db <- coef(Mfb)[2]-coef(Mrb)[2]
+   return(db)
+   }
> 
> rb <- boot(data=d,statistic=db,R=1e5)
> rb

ORDINARY NONPARAMETRIC BOOTSTRAP


Call:
boot(data = d, statistic = db, R = 1e+05)


Bootstrap Statistics :
     original       bias    std. error
t1* 0.3083992 -6.33051e-05  0.06228826
> boot.ci(rb,conf=0.92,type="bca",index=1)
BOOTSTRAP CONFIDENCE INTERVAL CALCULATIONS
Based on 100000 bootstrap replicates

CALL : 
boot.ci(boot.out = rb, conf = 0.92, type = "bca", index = 1)

Intervals : 
Level       BCa          
92%   ( 0.2093,  0.4283 )  
Calculations and Intervals on Original Scale
>
```

* Note that in this case, we reject Ho of no mediation (i.e., slope of *x* is the same in both models) because the 92% confidence interval does not include zero.

---

* Here is a different case:

```R
set.seed(730)
x <- c(rep(0,350),rep(1,350))
z <- rbinom(n=700,size=1,p=x*2/3+(1-x)*1/3)
table(z,x)
y <- 10+z+rnorm(n=700,mean=0,sd=2)
Mr <- lm(y~1+x)
Mf <- lm(y~1+x+z)
summary(Mr)
summary(Mf)
coef(Mf)[2]-coef(Mr)[2]
```

---

```Rout
> set.seed(730)
> x <- c(rep(0,350),rep(1,350))
> z <- rbinom(n=700,size=1,p=x*2/3+(1-x)*1/3)
> table(z,x)
   x
z     0   1
  0 230 116
  1 120 234
> y <- 10+z+rnorm(n=700,mean=0,sd=2)
> Mr <- lm(y~1+x)
> Mf <- lm(y~1+x+z)
> summary(Mr)

Call:
lm(formula = y ~ 1 + x)

Residuals:
    Min      1Q  Median      3Q     Max 
-7.3949 -1.3842 -0.0801  1.4725  6.1740 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  10.2041     0.1145  89.096   <2e-16 ***
x             0.3180     0.1620   1.963     0.05 *  
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.143 on 698 degrees of freedom
Multiple R-squared:  0.005493,	Adjusted R-squared:  0.004068 
F-statistic: 3.855 on 1 and 698 DF,  p-value: 0.04999

> summary(Mf)

Call:
lm(formula = y ~ 1 + x + z)

Residuals:
    Min      1Q  Median      3Q     Max 
-7.0273 -1.3641 -0.0193  1.4146  5.9533 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   9.8365     0.1251  78.604  < 2e-16 ***
x            -0.0312     0.1666  -0.187    0.851    
z             1.0722     0.1666   6.437 2.27e-10 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.083 on 697 degrees of freedom
Multiple R-squared:  0.06129,	Adjusted R-squared:  0.0586 
F-statistic: 22.76 on 2 and 697 DF,  p-value: 2.669e-10

> coef(Mf)[2]-coef(Mr)[2]
         x 
-0.3492228 
> 
```

---

* Now let's consider our bootstrap analysis:

```R
d <- data.frame(x,z,y)

library(boot)

db <- function(data,i){
  b <- data[i,]
  Mrb <- lm(y~1+x,data=b)
  Mfb <- lm(y~1+x+z,data=b)
  db <- coef(Mfb)[2]-coef(Mrb)[2]
  return(db)
  }

rb <- boot(data=d,statistic=db,R=1e5)
rb
boot.ci(rb,conf=0.95,type="bca",index=1)
```

---

```Rout
> d <- data.frame(x,z,y)
> 
> library(boot)
> 
> db <- function(data,i){
+   b <- data[i,]
+   Mrb <- lm(y~1+x,data=b)
+   Mfb <- lm(y~1+x+z,data=b)
+   db <- coef(Mfb)[2]-coef(Mrb)[2]
+   return(db)
+   }
> 
> rb <- boot(data=d,statistic=db,R=1e5)
> rb

ORDINARY NONPARAMETRIC BOOTSTRAP


Call:
boot(data = d, statistic = db, R = 1e+05)


Bootstrap Statistics :
      original       bias    std. error
t1* -0.3492228 0.0002293385  0.06597566
> boot.ci(rb,conf=0.95,type="bca",index=1)
BOOTSTRAP CONFIDENCE INTERVAL CALCULATIONS
Based on 100000 bootstrap replicates

CALL : 
boot.ci(boot.out = rb, conf = 0.95, type = "bca", index = 1)

Intervals : 
Level       BCa          
95%   (-0.4926, -0.2325 )  
Calculations and Intervals on Original Scale
>
```

---

* Next, we consider a case where there is no actual mediation:

```R
set.seed(105)
x <- c(rep(0,350),rep(1,350))
z <- rbinom(n=700,size=1,p=1/2)
table(z,x)
y <- 10+z+rnorm(n=700,mean=0,sd=2)
Mr <- lm(y~1+x)
Mf <- lm(y~1+x+z)
summary(Mr)
summary(Mf)
coef(Mf)[2]-coef(Mr)[2]
```

---

```Rout
> set.seed(105)
> x <- c(rep(0,350),rep(1,350))
> z <- rbinom(n=700,size=1,p=1/2)
> table(z,x)
   x
z     0   1
  0 171 172
  1 179 178
> y <- 10+z+rnorm(n=700,mean=0,sd=2)
> Mr <- lm(y~1+x)
> Mf <- lm(y~1+x+z)
> summary(Mr)

Call:
lm(formula = y ~ 1 + x)

Residuals:
    Min      1Q  Median      3Q     Max 
-6.1384 -1.4061 -0.0491  1.4501  5.7708 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  10.4638     0.1063  98.424   <2e-16 ***
x             0.0212     0.1504   0.141    0.888    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.989 on 698 degrees of freedom
Multiple R-squared:  2.85e-05,	Adjusted R-squared:  -0.001404 
F-statistic: 0.01989 on 1 and 698 DF,  p-value: 0.8879

> summary(Mf)

Call:
lm(formula = y ~ 1 + x + z)

Residuals:
    Min      1Q  Median      3Q     Max 
-6.5214 -1.3660 -0.0089  1.3708  5.3877 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 10.06514    0.12876  78.171  < 2e-16 ***
x            0.02343    0.14753   0.159    0.874    
z            0.77952    0.14756   5.283  1.7e-07 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 1.952 on 697 degrees of freedom
Multiple R-squared:  0.03852,	Adjusted R-squared:  0.03576 
F-statistic: 13.96 on 2 and 697 DF,  p-value: 1.133e-06

> coef(Mf)[2]-coef(Mr)[2]
          x 
0.002227203 
> 
```

* Here is our R code to test Ho of zero mediation:

```R
d <- data.frame(x,z,y)

library(boot)

db <- function(data,i){
  b <- data[i,]
  Mrb <- lm(y~1+x,data=b)
  Mfb <- lm(y~1+x+z,data=b)
  db <- coef(Mfb)[2]-coef(Mrb)[2]
  return(db)
  }

rb <- boot(data=d,statistic=db,R=1e5)
rb
boot.ci(rb,conf=0.95,type="bca",index=1)
```

---

```Rout
> d <- data.frame(x,z,y)
> 
> library(boot)
> 
> db <- function(data,i){
+   b <- data[i,]
+   Mrb <- lm(y~1+x,data=b)
+   Mfb <- lm(y~1+x+z,data=b)
+   db <- coef(Mfb)[2]-coef(Mrb)[2]
+   return(db)
+   }
> 
> rb <- boot(data=d,statistic=db,R=1e5)
> rb

ORDINARY NONPARAMETRIC BOOTSTRAP


Call:
boot(data = d, statistic = db, R = 1e+05)


Bootstrap Statistics :
       original       bias    std. error
t1* 0.002227203 -5.22697e-05  0.03003518
> boot.ci(rb,conf=0.95,type="bca",index=1)
BOOTSTRAP CONFIDENCE INTERVAL CALCULATIONS
Based on 100000 bootstrap replicates

CALL : 
boot.ci(boot.out = rb, conf = 0.95, type = "bca", index = 1)

Intervals : 
Level       BCa          
95%   (-0.0574,  0.0623 )  
Calculations and Intervals on Original Scale
>
```

---

* Now, we consider the issue of mediation when *x* has an effect on *y*:

```R
set.seed(389)
x <- c(rep(0,350),rep(1,350))
z <- rbinom(n=700,size=1,p=1/2)
table(z,x)
y <- 10+1/3*x+z+rnorm(n=700,mean=0,sd=2)
Mr <- lm(y~1+x)
Mf <- lm(y~1+x+z)
summary(Mr)
summary(Mf)
coef(Mf)[2]-coef(Mr)[2]
```

---

```Rout
> set.seed(389)
> x <- c(rep(0,350),rep(1,350))
> z <- rbinom(n=700,size=1,p=1/2)
> table(z,x)
   x
z     0   1
  0 167 164
  1 183 186
> y <- 10+1/3*x+z+rnorm(n=700,mean=0,sd=2)
> Mr <- lm(y~1+x)
> Mf <- lm(y~1+x+z)
> summary(Mr)

Call:
lm(formula = y ~ 1 + x)

Residuals:
    Min      1Q  Median      3Q     Max 
-6.9173 -1.4321  0.0112  1.3722  5.5795 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  10.6144     0.1118  94.938   <2e-16 ***
x             0.1575     0.1581   0.996     0.32    
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.092 on 698 degrees of freedom
Multiple R-squared:  0.001419,	Adjusted R-squared:  -1.171e-05 
F-statistic: 0.9918 on 1 and 698 DF,  p-value: 0.3196

> summary(Mf)

Call:
lm(formula = y ~ 1 + x + z)

Residuals:
    Min      1Q  Median      3Q     Max 
-7.3504 -1.4895 -0.0151  1.3324  5.7097 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  10.1398     0.1359  74.608  < 2e-16 ***
x             0.1497     0.1545   0.969    0.333    
z             0.9077     0.1547   5.868 6.83e-09 ***
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.043 on 697 degrees of freedom
Multiple R-squared:  0.04842,	Adjusted R-squared:  0.04569 
F-statistic: 17.73 on 2 and 697 DF,  p-value: 3.074e-08

> coef(Mf)[2]-coef(Mr)[2]
           x 
-0.007780114 
>
```

* Now, let's check on the confidence interval for the difference:

```R
d <- data.frame(x,z,y)

library(boot)

db <- function(data,i){
  b <- data[i,]
  Mrb <- lm(y~1+x,data=b)
  Mfb <- lm(y~1+x+z,data=b)
  db <- coef(Mfb)[2]-coef(Mrb)[2]
  return(db)
  }

rb <- boot(data=d,statistic=db,R=1e5)
rb
boot.ci(rb,conf=0.95,type="bca",index=1)
```

---

```Rout
> d <- data.frame(x,z,y)
> 
> library(boot)
> 
> db <- function(data,i){
+   b <- data[i,]
+   Mrb <- lm(y~1+x,data=b)
+   Mfb <- lm(y~1+x+z,data=b)
+   db <- coef(Mfb)[2]-coef(Mrb)[2]
+   return(db)
+   }
> 
> rb <- boot(data=d,statistic=db,R=1e5)
> rb

ORDINARY NONPARAMETRIC BOOTSTRAP


Call:
boot(data = d, statistic = db, R = 1e+05)


Bootstrap Statistics :
        original       bias    std. error
t1* -0.007780114 5.265146e-05  0.03484994
> boot.ci(rb,conf=0.95,type="bca",index=1)
BOOTSTRAP CONFIDENCE INTERVAL CALCULATIONS
Based on 100000 bootstrap replicates

CALL : 
boot.ci(boot.out = rb, conf = 0.95, type = "bca", index = 1)

Intervals : 
Level       BCa          
95%   (-0.0779,  0.0603 )  
Calculations and Intervals on Original Scale
>
```

* In this case, we fail to reject Ho of zero mediation
* Now, let's check on the case of partial mediation:

```R
set.seed(389)
x <- c(rep(0,350),rep(1,350))
z <- rbinom(n=700,size=1,p=x*1/2+(1-x)*1/3)
table(z,x)
y <- 10+1/3*x+z+rnorm(n=700,mean=0,sd=2)
Mr <- lm(y~1+x)
Mf <- lm(y~1+x+z)
summary(Mr)
summary(Mf)
coef(Mf)[2]-coef(Mr)[2]
```

---

```Rout
> set.seed(389)
> x <- c(rep(0,350),rep(1,350))
> z <- rbinom(n=700,size=1,p=x*1/2+(1-x)*1/3)
> table(z,x)
   x
z     0   1
  0 230 164
  1 120 186
> y <- 10+1/3*x+z+rnorm(n=700,mean=0,sd=2)
> Mr <- lm(y~1+x)
> Mf <- lm(y~1+x+z)
> summary(Mr)

Call:
lm(formula = y ~ 1 + x)

Residuals:
   Min     1Q Median     3Q    Max 
-6.737 -1.472 -0.019  1.417  5.580 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  10.4344     0.1119  93.241   <2e-16 ***
x             0.3375     0.1583   2.132   0.0333 *  
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.094 on 698 degrees of freedom
Multiple R-squared:  0.006472,	Adjusted R-squared:  0.005049 
F-statistic: 4.547 on 1 and 698 DF,  p-value: 0.03333

> summary(Mf)

Call:
lm(formula = y ~ 1 + x + z)

Residuals:
    Min      1Q  Median      3Q     Max 
-7.3586 -1.5003 -0.0114  1.3329  5.7393 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  10.1102     0.1220  82.853  < 2e-16 ***
x             0.1592     0.1574   1.012    0.312    
z             0.9455     0.1586   5.961 3.98e-09 ***
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 2.044 on 697 degrees of freedom
Multiple R-squared:  0.05467,	Adjusted R-squared:  0.05196 
F-statistic: 20.15 on 2 and 697 DF,  p-value: 3.098e-09

> coef(Mf)[2]-coef(Mr)[2]
         x 
-0.1782972 
>
```

---

* Here is the bootstrap analysis:

```R
d <- data.frame(x,z,y)

library(boot)

db <- function(data,i){
  b <- data[i,]
  Mrb <- lm(y~1+x,data=b)
  Mfb <- lm(y~1+x+z,data=b)
  db <- coef(Mfb)[2]-coef(Mrb)[2]
  return(db)
  }

rb <- boot(data=d,statistic=db,R=1e5)
rb
boot.ci(rb,conf=0.95,type="bca",index=1)
```

---

```Rout
> d <- data.frame(x,z,y)
> 
> library(boot)
> 
> db <- function(data,i){
+   b <- data[i,]
+   Mrb <- lm(y~1+x,data=b)
+   Mfb <- lm(y~1+x+z,data=b)
+   db <- coef(Mfb)[2]-coef(Mrb)[2]
+   return(db)
+   }
> 
> rb <- boot(data=d,statistic=db,R=1e5)
> rb

ORDINARY NONPARAMETRIC BOOTSTRAP


Call:
boot(data = d, statistic = db, R = 1e+05)


Bootstrap Statistics :
      original        bias    std. error
t1* -0.1782972 -9.515332e-05  0.04641128
> boot.ci(rb,conf=0.95,type="bca",index=1)
BOOTSTRAP CONFIDENCE INTERVAL CALCULATIONS
Based on 100000 bootstrap replicates

CALL : 
boot.ci(boot.out = rb, conf = 0.95, type = "bca", index = 1)

Intervals : 
Level       BCa          
95%   (-0.2834, -0.0999 )  
Calculations and Intervals on Original Scale
>
```

* There is a R utility for conducting mediation analysis based on the bootstrap:

```R
library(mediation)
model.M <- lm(z~1+x)
model.Y <- lm(y~1+x+z)
rs <- mediate(model.M, model.Y, treat='x', mediator='z',
                   boot=TRUE, sims=1e4)
summary(rs)
```

---

```Rout
> library(mediation)
Loading required package: MASS
Loading required package: Matrix
Loading required package: mvtnorm
Loading required package: sandwich
mediation: Causal Mediation Analysis
Version: 4.5.0

> 
> model.M <- lm(z~1+x)
> model.Y <- lm(y~1+x+z)
> rs <- mediate(model.M, model.Y, treat='x', mediator='z',
+                    boot=TRUE, sims=1e4)
Running nonparametric bootstrap

> summary(rs)

Causal Mediation Analysis 

Nonparametric Bootstrap Confidence Intervals with the Percentile Method

               Estimate 95% CI Lower 95% CI Upper p-value
ACME             0.1783       0.0965         0.28  <2e-16
ADE              0.1592      -0.1444         0.47   0.308
Total Effect     0.3375       0.0321         0.66   0.027
Prop. Mediated   0.5283       0.2008         2.86   0.027
                  
ACME           ***
ADE               
Total Effect   *  
Prop. Mediated *  
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Sample Size Used: 700 


Simulations: 10000 

>
```

---

* A helpful tutorial on the mediation library can be found [here](https://library.virginia.edu/data/articles/introduction-to-mediation-analysis).

---

### Lesson 15 - Monday 5/12/25

* 4th Assignment will be distributed tonight after class is over and will be due on Tuesday 5/20/25 by 12 noon on ELMS.
* Tonight's topic will be an introduction to the idea of clustering and hierarchical data (topic 29).
* We will then turn to the linear probability model and normal approximations to confidence intervals for proportions.

#### Topic 29: Introduction to Hierarchical Data

* We consider data from Stasny (1991; [link](https://www.jstor.org/stable/pdf/2290561.pdf)) examining victimization prevalence from the National Crime Survey.
* We start by reading in her dataset (from Table 1 of the paper).

```R
# NCS dataset

d1y  <- 156
d1n  <- 555
d2y  <- 95
d2n  <- 364
d3y  <- 162
d3n  <- 557
d4y  <- 72
d4n  <- 262
d5y  <- 92
d5n  <- 297
d6y  <- 15
d6n  <- 40
d7y  <- 11
d7n  <- 36
d8y  <- 10
d8n  <- 105
d9y  <- 35
d9n  <- 274
d10y <- 79
d10n <- 413
```

* A simple way to summarize victimization prevalence is to completely pool the data:

```R
# complete pooling

yes <- d1y+d2y+d3y+d4y+d5y+d6y+d7y+d8y+d9y+d10y
no  <- d1n+d2n+d3n+d4n+d5n+d6n+d7n+d8n+d9n+d10n
pooled.p <- yes/(yes+no)
pooled.p
```

* which gives us this result:

```Rout
> # complete pooling
> yes <- d1y+d2y+d3y+d4y+d5y+d6y+d7y+d8y+d9y+d10y
> no  <- d1n+d2n+d3n+d4n+d5n+d6n+d7n+d8n+d9n+d10n
> pooled.p <- yes/(yes+no)
> pooled.p
[1] 0.2002755
> qbeta(p=0.025,shape1=yes,shape2=1+no)
[1] 0.1873641
> qbeta(p=0.975,shape1=1+yes,shape2=no)
[1] 0.2136713
> 
```

* There are 2 problems with this approach: (1) it ignores the fact that observations are more likely to be similar within domains than across domains (i.e., lack of independence); and (2) domains with less evidence tend to generate more extreme results.
* Hierarchical models deal with both of these issues.
* Another extreme approach is to develop separate estimates, one for each domain.

```R
# separate estimates

p1  <- d1y/(d1y+d1n)
p2  <- d2y/(d2y+d2n)
p3  <- d3y/(d3y+d3n)
p4  <- d4y/(d4y+d4n)
p5  <- d5y/(d5y+d5n)
p6  <- d6y/(d6y+d6n)
p7  <- d7y/(d7y+d7n)
p8  <- d8y/(d8y+d8n)
p9  <- d9y/(d9y+d9n)
p10 <- d10y/(d10y+d10n)

dp <- c(p1,p2,p3,p4,p5,p6,p7,p8,p9,p10)
dp

# use p8 as an example
# calculate an exact 95% confidence interval
# around this estimate

dp[8]
qbeta(p=0.025,shape1=d8y,shape2=1+d8n)
qbeta(p=0.975,shape1=1+d8y,shape2=d8n)
```

* which gives us this result:

```Rout
> # separate estimates
> 
> p1  <- d1y/(d1y+d1n)
> p2  <- d2y/(d2y+d2n)
> p3  <- d3y/(d3y+d3n)
> p4  <- d4y/(d4y+d4n)
> p5  <- d5y/(d5y+d5n)
> p6  <- d6y/(d6y+d6n)
> p7  <- d7y/(d7y+d7n)
> p8  <- d8y/(d8y+d8n)
> p9  <- d9y/(d9y+d9n)
> p10 <- d10y/(d10y+d10n)
> 
> dp <- c(p1,p2,p3,p4,p5,p6,p7,p8,p9,p10)
> dp
 [1] 0.21940928 0.20697168 0.22531293 0.21556886 0.23650386
 [6] 0.27272727 0.23404255 0.08695652 0.11326861 0.16056911
> 
> # use p8 as an example
> # calculate an exact 95% confidence interval
> # around this estimate
> 
> dp[8]
[1] 0.08695652
> qbeta(p=0.025,shape1=d8y,shape2=1+d8n)
[1] 0.04248918
> qbeta(p=0.975,shape1=1+d8y,shape2=d8n)
[1] 0.1541052
>
```

* We can see that the inference in this domain comes nowhere close to the overall inference.
* Let's generate a histogram of the p's across all 10 of the domains.
* The victimization prevalence within each domain is separately estimated.

```R
# generate a histogram of the distribution of p

hist(dp)
```

<p align="center">
<img src="/gfiles/hp1z.png" width="600px">
</p>

* It looks like we have some variation in the p's.
* Yet the variation is within a range. This suggests some value in an approach called "partial pooling."
* Partial pooling allows for a balance of sharing information across domains ("borrowing strength") and allowing each domain to contribute information to the analysis.
* Such models have been demonstrated to have less prediction error than standard "fixed effects" approaches.
* These concepts are discussed in Sheather (chapter 10, section 10.1.1).
* Here we will use an approach called "empirical bayes" (Raudenbush, 1985; [link](https://journals.sagepub.com/doi/abs/10.3102/10769986010002075)).
* The first step is to build a model for the histogram above.
* We will use the [method of moments](https://stats.stackexchange.com/questions/12232/calculating-the-parameters-of-a-beta-distribution-using-the-mean-and-variance).

```R
# step 1: estimate a and b using method of moments

mean(dp)
var(dp)

eB <- function(mu,var) {
  alpha <- ((1-mu)/var-1/mu)*mu^2
  beta <- alpha*(1/mu-1)
  return(params=list(alpha=alpha,beta=beta))
  }

eB(0.1971331,0.003429212)

a <- 8.901334
b <- 36.2526

hist(dp,prob=T)
pd <- rbeta(n=1e7,shape1=a,shape2=b)
lines(density(pd),lty=1,lwd=3,col="darkred")
```

* which gives the following output:

```Rout
> mean(dp)
[1] 0.1971331
> var(dp)
[1] 0.003429212
> 
> eB <- function(mu,var) {
+   alpha <- ((1-mu)/var-1/mu)*mu^2
+   beta <- alpha*(1/mu-1)
+   return(params=list(alpha=alpha,beta=beta))
+   }
> 
> eB(0.1971331,0.003429212)
$alpha
[1] 8.901336

$beta
[1] 36.2526

> 
> a <- 8.901334
> b <- 36.2526
> 
> hist(dp,prob=T)
> pd <- rbeta(n=1e7,shape1=a,shape2=b)
> lines(density(pd),lty=1,lwd=3,col="darkred")
>
```

<p align="center">
<img src="/gfiles/hp2z.png" width="600px">
</p>

* Next, we consider the so-called posterior estimates from each domain:

```R
# step 2: posterior estimates

post1  <- rbeta(n=1e6,shape1=a+d1y,shape2=b+d1n)
post2  <- rbeta(n=1e6,shape1=a+d2y,shape2=b+d2n)
post3  <- rbeta(n=1e6,shape1=a+d3y,shape2=b+d3n)
post4  <- rbeta(n=1e6,shape1=a+d4y,shape2=b+d4n)
post5  <- rbeta(n=1e6,shape1=a+d5y,shape2=b+d5n)
post6  <- rbeta(n=1e6,shape1=a+d6y,shape2=b+d6n)
post7  <- rbeta(n=1e6,shape1=a+d7y,shape2=b+d7n)
post8  <- rbeta(n=1e6,shape1=a+d8y,shape2=b+d8n)
post9  <- rbeta(n=1e6,shape1=a+d9y,shape2=b+d9n)
post10 <- rbeta(n=1e6,shape1=a+d10y,shape2=b+d10n)

boxplot(post1,post2,post3,post4,post5,post6,
  post7,post8,post9,post10,ylim=c(0,0.6),
  names=c("d1","d2","d3","d4","d5","d6","d7",
    "d8","d9","d10"),
  ylab="Posterior Predictive Distribution")
```

<p align="center">
<img src="/gfiles/hp3z.png" width="600px">
</p>

* Now let's consider the inference about domain #8 again:

```R
# use p8 as an example
# calculate an exact 95% confidence interval
# around this estimate

# fixed-effect estimate

dp[8]
qbeta(p=0.025,shape1=d8y,shape2=1+d8n)
qbeta(p=0.975,shape1=1+d8y,shape2=d8n)

# random effect estimate

mean(post8)
quantile(post8,c(0.025,0.975))
```

* Here are the results:

```Rout
> # use p8 as an example
> # calculate an exact 95% confidence interval
> # around this estimate
> 
> # fixed-effect estimate
> 
> dp[8]
[1] 0.08695652
> qbeta(p=0.025,shape1=d8y,shape2=1+d8n)
[1] 0.04248918
> qbeta(p=0.975,shape1=1+d8y,shape2=d8n)
[1] 0.1541052
> 
> # random effect estimate
> 
> mean(post8)
[1] 0.1180318
> quantile(post8,c(0.025,0.975))
      2.5%      97.5% 
0.07288513 0.17222524 
>
```

* Notice that domain 8's inference has been "shrunk" toward the overall average.
* We can see how this plays out with all domains by generating a shrinkage plot:

```R
# generate a shrinkage plot

plot.new()
plot.window(xlim=c(0.4,2.5),ylim=c(-0.05,0.3))
segments(x0=0.5,x1=0.5,y0=0,y1=0.3,lty=1,lwd=2)
segments(x0=0.5,x1=2.5,y0=0,y1=0,lty=1,lwd=2)
segments(x0=1,x1=1,y0=-0.01,y1=0.01,lty=1,lwd=2)
segments(x0=2,x1=2,y0=-0.01,y1=0.01,lty=1,lwd=2)
text(x=1,y=-0.03,"Separate")
text(x=2,y=-0.03,"Partially Pooled")
points(x=rep(1,10),y=c(p1,p2,p3,p4,p5,p6,p7,p8,p9,p10),pch=19,cex=1.5)
points(x=rep(2,10),y=c(mean(post1),mean(post2),mean(post3),mean(post4),
  mean(post5),mean(post6),mean(post7),mean(post8),mean(post9),mean(post10)),
  pch=19,cex=1.5)
segments(x0=rep(1,10),x1=rep(2,10),
  y0=c(p1,p2,p3,p4,p5,p6,p7,p8,p9,p10),
  y1=c(mean(post1),mean(post2),mean(post3),mean(post4),
  mean(post5),mean(post6),mean(post7),mean(post8),
  mean(post9),mean(post10)))
segments(x0=0.47,x1=0.53,y0=0.05,y1=0.05,lty=1,lwd=2)
segments(x0=0.47,x1=0.53,y0=0.1,y1=0.1,lty=1,lwd=2)
segments(x0=0.47,x1=0.53,y0=0.15,y1=0.15,lty=1,lwd=2)
segments(x0=0.47,x1=0.53,y0=0.2,y1=0.2,lty=1,lwd=2)
segments(x0=0.47,x1=0.53,y0=0.25,y1=0.25,lty=1,lwd=2)
segments(x0=0.47,x1=0.53,y0=0.3,y1=0.3,lty=1,lwd=2)
text(x=0.41,y=0.05,"0.05",srt=90)
text(x=0.41,y=0.1,"0.10",srt=90)
text(x=0.41,y=0.15,"0.15",srt=90)
text(x=0.41,y=0.2,"0.20",srt=90)
text(x=0.41,y=0.25,"0.25",srt=90)
text(x=0.41,y=0.3,"0.30",srt=90)
segments(x0=0.7,x1=2.3,y0=pooled.p,y1=pooled.p,lty=2,lwd=2)
points(x=0.7,y=pooled.p,pch=19,cex=2,col="darkred")
points(x=2.3,y=pooled.p,pch=19,cex=2,col="darkred")
```

* Here is the plot:

<p align="center">
<img src="/gfiles/shrinkage.png" width="600px">
</p>

* Now, let's use the lme4 library and the lmer() function to estimate a normal linear random effects model.
* First, we have to get the data into the right form:

```R
library(lme4)

id1  <- rep(1,d1y+d1n)
id2  <- rep(2,d2y+d2n)
id3  <- rep(3,d3y+d3n)
id4  <- rep(4,d4y+d4n)
id5  <- rep(5,d5y+d5n)
id6  <- rep(6,d6y+d6n)
id7  <- rep(7,d7y+d7n)
id8  <- rep(8,d8y+d8n)
id9  <- rep(9,d9y+d9n)
id10 <- rep(10,d10y+d10n)

y1 <- c(rep(0,d1n),rep(1,d1y))
y2 <- c(rep(0,d2n),rep(1,d2y))
y3 <- c(rep(0,d3n),rep(1,d3y))
y4 <- c(rep(0,d4n),rep(1,d4y))
y5 <- c(rep(0,d5n),rep(1,d5y))
y6 <- c(rep(0,d6n),rep(1,d6y))
y7 <- c(rep(0,d7n),rep(1,d7y))
y8 <- c(rep(0,d8n),rep(1,d8y))
y9 <- c(rep(0,d9n),rep(1,d9y))
y10 <- c(rep(0,d10n),rep(1,d10y))

df1 <- cbind(id1,y1)
df2 <- cbind(id2,y2)
df3 <- cbind(id3,y3)
df4 <- cbind(id4,y4)
df5 <- cbind(id5,y5)
df6 <- cbind(id6,y6)
df7 <- cbind(id7,y7)
df8 <- cbind(id8,y8)
df9 <- cbind(id9,y9)
df10 <- cbind(id10,y10)

df <- rbind(df1,df2,df3,df4,df5,
  df6,df7,df8,df9,df10)
d <- as.data.frame(df)
names(d)[names(d)=="id1"] <- "id"
names(d)[names(d)=="y1"] <- "y"
head(d)
```

* Here is the output:

```Rout
> head(d)
  id y
1  1 0
2  1 0
3  1 0
4  1 0
5  1 0
6  1 0
>
```

* Now, we estimate the fully pooled model:

```R
M0 <- lm(y~1,data=d)
summary(M0)
```

* Here is the output:

```Rout
 M0 <- lm(y~1,data=d)
> summary(M0)

Call:
lm(formula = y ~ 1, data = d)

Residuals:
    Min      1Q  Median      3Q     Max 
-0.2003 -0.2003 -0.2003 -0.2003  0.7997 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 0.200275   0.006643   30.15   <2e-16 ***
---
Signif. codes:  
0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.4003 on 3629 degrees of freedom
>
```


* Then, here is the "separate estimates" fixed effects model:

```R
Mf <- lm(y~0+as.factor(id),data=d)
summary(Mf)

# separate estimates

p1  <- coef(Mf)[1]
p2  <- coef(Mf)[2]
p3  <- coef(Mf)[3]
p4  <- coef(Mf)[4]
p5  <- coef(Mf)[5]
p6  <- coef(Mf)[6]
p7  <- coef(Mf)[7]
p8  <- coef(Mf)[8]
p9  <- coef(Mf)[9]
p10 <- coef(Mf)[10]

dp <- c(p1,p2,p3,p4,p5,p6,p7,p8,p9,p10)
dp
```

* Here is the output:

```Rout
> # separate estimates
> 
> p1  <- coef(Mf)[1]
> p2  <- coef(Mf)[2]
> p3  <- coef(Mf)[3]
> p4  <- coef(Mf)[4]
> p5  <- coef(Mf)[5]
> p6  <- coef(Mf)[6]
> p7  <- coef(Mf)[7]
> p8  <- coef(Mf)[8]
> p9  <- coef(Mf)[9]
> p10 <- coef(Mf)[10]
> 
> dp <- c(p1,p2,p3,p4,p5,p6,p7,p8,p9,p10)
> dp
 as.factor(id)1  as.factor(id)2  as.factor(id)3 
     0.21940928      0.20697168      0.22531293 
 as.factor(id)4  as.factor(id)5  as.factor(id)6 
     0.21556886      0.23650386      0.27272727 
 as.factor(id)7  as.factor(id)8  as.factor(id)9 
     0.23404255      0.08695652      0.11326861 
as.factor(id)10 
     0.16056911 
>
```

* Then, we estimate the random effects model:

```R
Mr <- lmer(y~1+(1|id),data=d)
summary(Mr)
coef(Mr)

post1  <- coef(Mr)$id[1,1]
post2  <- coef(Mr)$id[2,1]
post3  <- coef(Mr)$id[3,1]
post4  <- coef(Mr)$id[4,1]
post5  <- coef(Mr)$id[5,1]
post6  <- coef(Mr)$id[6,1]
post7  <- coef(Mr)$id[7,1]
post8  <- coef(Mr)$id[8,1]
post9  <- coef(Mr)$id[9,1]
post10 <- coef(Mr)$id[10,1]
```

* Here is our output:

```Rout
> Mr <- lmer(y~1+(1|id),data=d)
> summary(Mr)
Linear mixed model fit by REML ['lmerMod']
Formula: y ~ 1 + (1 | id)
   Data: d

REML criterion at convergence: 3645.2

Scaled residuals: 
    Min      1Q  Median      3Q     Max 
-0.5757 -0.5443 -0.5147 -0.3255  2.1831 

Random effects:
 Groups   Name        Variance Std.Dev.
 id       (Intercept) 0.00203  0.04506 
 Residual             0.15891  0.39863 
Number of obs: 3630, groups:  id, 10

Fixed effects:
            Estimate Std. Error t value
(Intercept)  0.19477    0.01663   11.71
> coef(Mr)
$id
   (Intercept)
1    0.2169654
2    0.2051936
3    0.2223139
4    0.2116193
5    0.2295123
6    0.2269393
7    0.2095020
8    0.1306194
9    0.1297411
10   0.1652631
```

* Now, let's consider another shrinkage plot:

```R
plot.new()
plot.window(xlim=c(0.4,2.5),ylim=c(-0.05,0.3))
segments(x0=0.5,x1=0.5,y0=0,y1=0.3,lty=1,lwd=2)
segments(x0=0.5,x1=2.5,y0=0,y1=0,lty=1,lwd=2)
segments(x0=1,x1=1,y0=-0.01,y1=0.01,lty=1,lwd=2)
segments(x0=2,x1=2,y0=-0.01,y1=0.01,lty=1,lwd=2)
text(x=1,y=-0.03,"Separate")
text(x=2,y=-0.03,"Partially Pooled")
points(x=rep(1,10),y=c(p1,p2,p3,p4,p5,p6,p7,p8,p9,p10),pch=19,cex=1.5)
points(x=rep(2,10),y=c(post1,post2,post3,post4,
  post5,post6,post7,post8,post9,post10),
  pch=19,cex=1.5)
segments(x0=rep(1,10),x1=rep(2,10),
  y0=c(p1,p2,p3,p4,p5,p6,p7,p8,p9,p10),
  y1=c(mean(post1),mean(post2),mean(post3),mean(post4),
  mean(post5),mean(post6),mean(post7),mean(post8),
  mean(post9),mean(post10)))
segments(x0=0.47,x1=0.53,y0=0.05,y1=0.05,lty=1,lwd=2)
segments(x0=0.47,x1=0.53,y0=0.1,y1=0.1,lty=1,lwd=2)
segments(x0=0.47,x1=0.53,y0=0.15,y1=0.15,lty=1,lwd=2)
segments(x0=0.47,x1=0.53,y0=0.2,y1=0.2,lty=1,lwd=2)
segments(x0=0.47,x1=0.53,y0=0.25,y1=0.25,lty=1,lwd=2)
segments(x0=0.47,x1=0.53,y0=0.3,y1=0.3,lty=1,lwd=2)
text(x=0.41,y=0.05,"0.05",srt=90)
text(x=0.41,y=0.1,"0.10",srt=90)
text(x=0.41,y=0.15,"0.15",srt=90)
text(x=0.41,y=0.2,"0.20",srt=90)
text(x=0.41,y=0.25,"0.25",srt=90)
text(x=0.41,y=0.3,"0.30",srt=90)
segments(x0=0.7,x1=2.3,y0=coef(M0),y1=coef(M0),lty=2,lwd=2)
points(x=0.7,y=pooled.p,pch=19,cex=2,col="darkred")
points(x=2.3,y=pooled.p,pch=19,cex=2,col="darkred")
```

<p align="center">
<img src="/gfiles/shrinkage2.png" width="600px">
</p>

#### Topic 30: Binary Outcomes	

* We begin by reading in our Minneapolis dataset (emailed to you).

```r
df <- read.csv(file="minn.txt",sep=",",header=T)
head(df,n=10)
tail(df,n=10)
```

### Assignment #4 (Due on ELMS at noon on Tuesday 5/20/25)

Instructions: please review the guidelines for assignments and submission of assignments in the syllabus above. You should not discuss this assignment with others; the work you submit should be your own work. If I receive questions related to the assignment that I judge to be of interest to the entire class, I will post them below with the answers. I will respond to all questions submitted by Monday evening 5/19/25 at 9:00pm. I will not be able to respond to any questions received after that time (so that all students will have ample time to take such questions into consideration before the submission deadline). Each problem below is worth 10 points. Good luck!

1. Use the immigration/homicide dataset to estimate the linear relationship between the 2018 immigration rate and the 2019 homicide rate controlling for region (1=South, 0=Other). Report a summary of your regression results using the summary() function. Confirm (and report) your results using the matrix solution for both the coefficient estimates and the standard errors (via the variance-covariance matrix).

2. Holding the 2018 immigration rate constant at its *mean* value estimate and report the expected homicide rate for both the south region and non-south region using R's predict() function along with the 88% confidence intervals for each of the expected values. Report your results and comment on whether the confidence intervals overlap.

3. Use the simulation procedure discussed in Lesson 12 to form and report 88% confidence intervals for the south and non-south expected values (holding the 2018 immigration rate constant at its mean value) based on the multivariate t-distribution. Report your results and comment on the consistency of the simulation-based confidence intervals with the confidence intervals based on the predict() function.

4. Using your simulation framework from problem 3, develop a valid inference about the difference (Δ) between the south and non-south expectated homicide rates (holding the immigration rate constant at the sample mean). Report your results and comment on whether your confidence interval includes zero.

5. Estimate a new regression model for the 2019 homicide rate which allows for an interaction between the 2018 immigration rate and the south/non-south region. Use the anova() function to test Ho that the restricted model (no interaction) is equally consistent with the data. Then, use a log-likelihood ratio test to test the same hypothesis. Report your results and supporting detail; then, compare your conclusions between the 2 tests. Conduct your tests at the alpha = 0.10 significance level (or 90% confidence level).

6. Using the interaction model, calculate estimates of θs and θns when the immigration rate goes from 3 to 4. Using simulation and the simulated sampling distribution of the difference between θs and θns (Δ), test the Ho that θs = θns at the 85% confidence level. Report your detailed results and your conclusion.

7. Using the 2022 immigration and homicide data, investigate whether the 2022 immigration rate mediates the relationship between the south/non-south region variable and the 2022 homicide rate. Set up your test using the bootstrap and report your results. Conduct your test at a 95% confidence level.

8. Using the 2022 immigration ad homicide data, investigate the mediation question in problem 7 using the mediation() library. Report your results. Conduct your test at a 95% confidence level.

9. Considering the data in Table 2 of Stasny's article, calculate a fully pooled estimate of the victimization rate with a 92% confidence interval. Then, develop separate estimates for each domain. Estimate and report the 92% confidence interval for the 9th domain.

10. Considering the same data in problem 9, use the separate point estimates as the basis for a method of moments calculation of the shape parameters for the beta distribution. With these shape parameters as priors, estimate the mean posterior victimization rate for domain #8. Estimate and report the 92% credibility interval for the 9th domain. Compare your results to what you saw in problem 9. Do you see evidence of shrinkage?
