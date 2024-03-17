The data we obtained was a part of data from the Dallas animal shelter data. The data given included 1678 observations including the variables with 6 category variables and 1 numerical variable.
Our research question is, "Which factors influence the number of days an animal spends in the shelter before their final outcome is decided?"

We first conducted an exploratory data analysis (EDA) to examine the distribution of the data and the relationships between variables.

In the formal analysis, we employed three different generalized linear regression models to regress the explanatory variables on the response variable. 
These models are the generalized linear model with a negative binomial distribution, the zero-inflated negative binomial model, and the hurdle model. 
We used the Bayesian Information Criterion (BIC) as our criterion statistic and conducted residual diagnostics for each of the three models.

The conclusion is that among the three models, only the generalized linear model with a negative binomial distribution passed the residual diagnostics. 
This model included intake_type and outcome_type as explanatory variables. 
These two variables contain more information compared to other variables and are more likely to influence time_at_shelter.
