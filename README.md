Dataset
Please refer to newcar.dat file. Alternatively, you can download the data from here
http://www.itl.nist.gov/div898/education/anova/newcar.dat\

Data description:
This is Dataplot data file     NEWCAR.DAT
New Car Interest rates
Source--Hoaglin, D., Mosteller, F., and Tukey, J. (1991).
        Fundamentals of Exploratory Analysis of Variance.
        Wiley, New York, page 71.
Response Variable                  = interest rate
Number of observations             = 54 (= 9 x 6 cities)
Number of variables per line image = 2
Order of variables per line image--
   Response variable = interest rate (%)
   Factor 1          = city (6 levels: 1 to 6)
Statistical areas--Multifactor
Design type      --Randomized Block
To read this file into Dataplot--
      SKIP 25
      READ NEWCAR.DAT Y X

Question: 
Carryout statistical test to determine whether there is any significant difference in the interest rate among the cities. 

Optional: determine which group has same mean and which group has different mean

Assumptions: Please check the assumptions for linear models
