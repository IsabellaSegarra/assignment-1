# Homework 1 Task 3

---

Answer the following questions based on exercises from *An Introduction to Statistical Learning with Applications in Python*.

## Chapter 2.4 Exercises

---

### Exercise 1 (ISLP exercise 2)

Explain whether each scenario is a **classification or regression** problem, and indicate whether we are most interested in **inference or prediction**. Finally, provide **n** (size of observation dataset) and **p** (number of predictors).

**(a)**  We collect data on 200 protected marine reserves worldwide. For each reserve we record species richness, reserve size, years since establishment, enforcement budget, and proximity to human settlements. We are interested in understanding which factors affect species richness.

> This model is a regression and inference problem. It is a is a regression problem because we are modeling species richness which is a continous variable and it is inference because we want to know what factors (reserve size, years since establishment, enforcement budjet, and proximity to human settlements) influence species richness. We are modeling with a sample size of 200 and four predictors (reserve size, years since establishment, enforcement budjet, and proximity to human settlements). 

---

**(b)** A conservation agency wants to know whether a proposed habitat corridor will successfully support wildlife movement or fail to do so. They collect data on 30 previously established corridors. For each corridor they have recorded whether wildlife movement was successful or unsuccessful, corridor width, length, surrounding land use type, and eight other variables.

> This model is a classification, prediction problem. It is a classification problem because we are trying to determine if a probposed habitat corridor will do one of two things: improve wildlife movement or not. We are modeling with a sample size of 30 with 11 variables for predictors. 

---

**(c)** We are interested in predicting weekly average ground-level ozone concentration in a coastal city. We collect weekly data for all of 2019. For each week we record average ozone concentration, sea surface temperature, wind speed, solar radiation, and atmospheric

> This model is regression, prediction problem. It is regression because we are interested in average ozone concentration from five variables or predictors. We are modeling with 52 samples and five predictors. 

---

### Exercise 2 (ISLP exercise 5)

What are the advantages and disadvantages of a very flexible (versus a a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

>  A more flexible model has higher variance because it tries to fit more complex patterns in the data, which can lead to capturing noise rather than the actual relationship you are trying to model. A less flexible model assumes a simpler relationship, leading to higher bias but lower variance. A less flexible model is preferred when the sample size of the data is small or the model is already linear. 
---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

> A parametric model uses training data to fit a model, this model *assumes* the function of the model. It is useful for smaller datasets, however it can end up not capturing the true model form. This is useful for regression models because the assumptions are built into the model formula. A non-parametric model makes no assumptions about the functional form of the model, is more flexible to complex relationships, however it needs more data to reduce noise. 