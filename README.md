java c
Replication Exercise: Angrist and Krueger (1991)
Econ 5554: Data Analysis (Fall 2024)
In this homework, you are asked to replicate the results in Angrist and Kruger (1991); to extend them in a simple way, using a health measure (rather than income) as an outcome; and to think critically about ways that the IV approach can fail. You will be using the 1980 US census data for this problem set (from IPUMS USA), the same data Angrist and Krueger use. (They also use 1970 Census in some regressions; you only need to download 1980 data and replicate results using that data.).
Please read Angrist and Kruger (1991), “Does Compulsory School Attendance Affect Schooling and Earnings), henceforth AK91, for their instrumental variables approach to solving the omitted variables problem in their estimation of wage returns to education. You would like to use the same IV approach to study a related question: the causal effect of a year of education on health outcomes.
Due dates:
Nov. 8: Questions 1-5, 7
November 15: The entire HW is due
Part I
1.   There is a systematic relationship in the data between health outcomes using a variety of measures (life
expectancy, BMI, rates of various conditions like cancer, heart conditions, etc.) and years of education.
Through what channels could education affect these health variables causally? Alternatively, why might it simply be correlated with health, without affecting it causally?
2.    Consider the following regression:
Healthi  = β0  + β1Educi  + Xiβ2  + ui
where Xi is a vector of individual characteristics (age, race, gender, etc.), and ui  is a classical error term.
Suppose you have a reliable measure of health. What are the assumptions needed for β1  to be a consistent estimate of the causal effect of education on health? Describe why these assumptions are not likely to be satisfied in an analysis using survey data, like the Census. In which direction do you expect β1 to be biased?
3.   Would the assumptions be satisfied if you were using data from a randomized controlled trial? Which variable(s) would have to be randomly allocated?
4.   The 1980 census has two health variables: work and transportation disabilities. Discuss the interpretation of a coefficient on education when health is measured as either work or transportation disabilities. Also, comment on the mechanisms through which education might affect these specific health variables causally, and again the reasons why it might simply correlated with those variables, without affecting them causally.
5.    Specify a model in which an instrument, Zi, is used to overcome the problems above. What are the
necessary assumptions for your instrumental variables strategy to yield consistent estimates for the health returns to education?
Part II
6.   AK91 uses quarter of birth as an instrument for education. Explain the idea behind this instrument. What evidence/arguments do AK91 provide that this is a valid instrument?
7.    Figures I, II and III in AK91 give a visual justification for quarter of birth being correlated with years of completed education
Replicate figures I, II, and III from AK91 using the 19代 写Econ 5554: Data Analysis (Fall 2024)Statistics
代做程序编程语言80 census data. Do your figures reveal a 1st quarter effect of lower education relative to subsequent quarters within the same year?
8.   What is the differences-in-differences model that the authors are estimating in Table II? Write it down    (but you do not need to actually replicate it). What is the purpose of this set of regressions in their paper (i.e., why is it important/useful for their analysis?) Would these regressions similarly be useful in your analysis of health (rather than income)?
9.    How is the Wald estimator defined? Group the data using quarter of birth and replicate Panel B in Table III. First, use AK91’s outcome measure. Then, do so again using your health measures.
10.  Replicate Table V (specifications 1 and 2 only), using AK91’s outcome measure. Create also a table that   shows the results of the corresponding first-stage regression. In light of your discussion in Part I, are you surprised that the IV estimates are larger than the OLS estimates in AK91’s paper? Why or why not?
Now use your health measure as the outcome. How the do the OLS and IV estimates compare?
11. What is the first-stage F-test? Since AK91 was published, a number of researchers have identified
problems with weak instruments in finite samples, especially when there is even a small correlation between the instrument and the outcome variable. In particular, first-stage regressions with a relatively large number of instruments should have an F-statistic of at least 10 to be reliable. Based on the first-  stage regression, do you believe that AK91 may have a weak instruments problem? Explain.
12.  Suppose there is a weak instruments problem. One way to address it is to reduce the number of
instruments. Can you think of a way to obtain IV results using a smaller number of instruments?
Implement your strategy, and comment the strength of the first-stage F-test. Did the second-stage results change at all?
13.  Replicate the results in question 12, but using health outcomes as your measure.
14.  Read and look at the pictures in the following paper by Buckles and Hungerman 2009
(http://www.nber.org/papers/w14573.pdf). For the analysis in AK91 (and your analysis of health outcomes), what are possible reasons quarter of birth may fail to serve as an instrument?
15.  Interpret your IV estimate in the face of heterogeneous treatment effects. In particular, whose return
does the IV estimate capture? Considering this, would you expect the IV estimates to be larger or smaller than OLS estimates for health returns to education?
16.  Is there a relationship between education and health? What does your analysis tell us about the
importance of education for future health? Finally, are you convinced by your analysis? Why or why not?
Bonus: Suppose you wanted to check whether the socioeconomic characteristics of mothers differ for children born in different quarters. Propose a way to test this using IPUMS data (possibly from a different Census year) and implement your suggestion. (Note – this is something AK91 could have and should have done!) What are your findings?





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
