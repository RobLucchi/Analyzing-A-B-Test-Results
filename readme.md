# Analyzing A/B Test Results


This project is a part of the Advanced Data Analysis NanoDegree at [Egypt FWD](https://egfwd.com/data/), (Second project)

#### -- Project Status: [Completed]

## Project Intro/Objective
A/B tests are very commonly performed by data analysts and data scientists.

My goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.


### Methods Used

* Inferential Statistics
* Hypothesis testing
* Machine Learning (Logistic regression)
* Predictive Modeling
* etc.

### Technologies

* Python
* Pandas, Numpy
* jupyter
* etc. 

## Conclusion:


#### why it's a good idea to consider other factors outside this dataset features:

In our ab testing, I was discussing if the new treatment works better, In this Analysis I used one feature only, which is whether the user landed on the new page or the old page, with well-choosen distribution with nearly 50% of users are in the control group versus the treatment group, but many other factors might affect the user decision of converting or not:

* An old user who just exploring the new treatment, may not make any conversion.
* The location of a user may be a cultural factor for acting to the new treatment.
* Maybe our unbiased 50% control group has another biased factor in selecting them like gender or the time those users used our service.
* The duration of the test may also affect the experiment, had we do it enough?
