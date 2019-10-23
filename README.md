# Business impact: Churn analysis

In this project I took customer data from a company and attempted to predict whether each customer would churn or not.

As we all know, getting new customers is way more expensive than trying to retain the ones a business already has. The algorithm in this project will tell you which customers should be invested in in attempt to retain them and which customers would retain anyway and need no financial investment in them.

Our first algorithm had accuracy of __86.9%__ which is really good when talking about human behaviour as it can be bit unpredictable at times.

# Now what do we do with the information of people that might churn?

Let's assume here that getting a new costumer costs 300$ for the business. What if we could spend just a fraction of that to retain our customers or not spend a dime on those customers that we know wouldnt leave the business? That means a lot of savings.

# 65000$ savings on just 7000 customers

In the churn.rmd file I go through on how we got into this number but simply put we build a classifier that will predict if a customer would leave or not and after that we find the sweetspot on how much to spend per customer to get the most out of our classifier. __Cost per customer was reduced to 37$ when a simple classifier would set the price to 47$.__

# Next steps: Improving the model

While this is all good and savings are already made we can always make our model even more accurate. With slight tweaks the accuracy is already raised to __87.4%__. Improvements on the model are made in the file named churnvol2.rmd.
