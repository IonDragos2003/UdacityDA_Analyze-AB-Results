"#UdacityDA_Analyze-AB-Results"

## The second out of 4 projects for Udacity's Data Analyst Nanodegree

### Dataset:
* AB test results on a webpage

### Scope of the project

For this project, the scope is to understand the results of an A/B test run by an e-commerce website.

### Steps:

* Part I - Probability
* Part II - A/B Test
* Part III - Regression

### Preliminary conclusions:

* Firstly, the control group at an initial glance has a higher conversion rate than the treatment group, implying that when a group is presented with the new landing page, the conversion rate actually goes down. However, we cannot conclude just based on this and have to investigate further.

* The p-value is equal to around 0.906. This is a very high value considering we are using Type I error rate of 5%. In this case, we fail to reject the null, meaning that there isn't a statistically significant indication that the new page has higher conversion rates than the old page. This is line with what has been found using a bootstrap approach

* Once again, the independent variables have high p-values associated with them. Additionally, an interaction between the user's country and the type of page they would receive proves unhelpful too, as their associated p-values are too high given a 5% Type I error rate.
Based on this, we fail to reject the null once again, ultimately concluding that there is no statistically significant reason to adopt the new_page as it does not lead to better conversion rates than what we currently use.
