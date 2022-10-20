# # EDA_CHURN_ANALYSIS

# Introduction
Orange S.A., formerly France Télécom S.A., is a French multinational telecommunications corporation. The Orange Telecom's Churn Dataset, consists of cleaned customer activity data (features), along with a churn label specifying whether a customer canceled the subscription.


# What is Churn Prediction?
Churn prediction is analytical studies on the possibility of a customer abandoning a product or service. The goal is to understand and take steps to change it before the customer gives up the product or service.
# Problem Statement
Explore and analyze the data to discover key factors responsible for customer churn and come up with ways/recommendations to ensure customer retentio

# Conclusion

After analysing our customer churn dataset by eda and data visualization . We have observed many insights and come to following results on the basis of that :

* The minutes for day, evening ,night and international plan are perfectly correlated with their corresponding charges implying there is no dynamic pricing.
* The customer churning rate is low ie 14.5%. So better strategies are needed to further reduce it
* States like NewJersey(NJ), California(CA), TEXAS(TX), Mary Land(MD), South Carolina(SC) has higher churn rate than the other states so the company should focus there more and provide better facilities to reduce the churn rate.Also Hawaii(HI), Alaska(AK), Arizona(AZ),(Virginia)VA, (Iowa)IA has very low churn rate.Company can find what they are doing right in these states and try to implement it in states where there are high churn rate.
* The Account length for churned and non churned customers didnot show any specific behaviour implying length of service has no bearing in the churn.
* We have only 3 area codes and the churning of service across them is largely similar.
* There is a 42.4% churn of customers with international plan while only a 11.4% churn of customers without international plan.It could be because many of the plan might have been taken by tourists who churned once their tour is over.
* The customers who dont have a voice mail plan are more churned.ie(With voicemail plan there is a (16.7%) churn rate compared to people with no voice mail plan (8.67%). So introducing voicemail offers for customers with no voicemail plan can reduce churn by half.
* The customers who retained service most of them did about 0-20 voicemail messages after that the distribution of retained customers is less indicating some underlying issue.So setting a limit of 20 voice calls might help reduce churn rate.
* The majority of distribution of customers who got churned did 0 voicemail messages.
* Customers spending 220 minutes or more i.e. approx 4hrs tend to switch to other operator.ie when day minutes are more then more people are leaving .Since the minutes are highly correlated to charges implying when charges are high people are leaving.
* On an average a 100 day calls are made which is a good indication for the company.But we can also note that for the churn customer the median is slightly higher than 100 which indicates there are call drops as there are more calls in the morning.
* The Evening minutes across churned population is more than that of the non churned population.
* The Total evening call distribution is roughly same for churned and non churned population.
* The night minutes across churned population is more than that of the non churned population.
* The total night call distribution for churned and non churned population is roughly same.
* The total night call distribution is similar to total evening call distribution, also the night minutes and evening minutes follow a similar pattern(which can help us reduce feature by making a feature including evening and night time values).
* The international minutes across churned population is more than that of the non churned population.
* It is to benoted that whenever minutes or charges increases the churning rate is higher.So providing special plans for high frequency customers to make them feel valued and thereby preventing them from leaving the network.
* The distribution of total international calls is negatively skewed. But the most of values for churned is lower than the non churned
* People who retained the service is maximum when the customer service call is 1 for increase in calls the people retained the service reduces. While in case of churned we can see that it increases to maximum at 1 call then decreases and further increases when customer service calls are 4 then the customer churned decreases.
* When customer service calls are 4 or higher there is a higher churn rate implying a deficiency in service after which the customer leaves the network
