# Ecommerce-Purchase-Analysis-with-pandas
A dataset has been taken on ecommerce purchase data. We have tried to analyze the datasets and bring out essential insights.


Due to privacy issues, I have taken a fake dataset here with 30K entries. 
The situation is, customers are providing some personal information while purchasing stuff on-line or in-store. For some reasons, the clients want to know the answer to some of the questions from the dataset.

# Importing the necessary Librarires
We have imported pandas into the jupyter notebook for the analysis of the data.


jupyter notebook is light-weight and powerful. There are other options. But we are going with this due to the easier and intuitive interface


# Getting a overlook of the dataset 

We checked the dataset after loading it into a dataframe.
we used the .head() and .info() method mainly to get a overview of what sort of data we are dealing with.
Here we also checked if we have any anomaly in the dataset, which might require cleaning and preprocessing.

1. We have found duplicates. We picked out the duplicates with the .duplicated() method . Two customer had the same phone number. What we can infer from is that, either they have made a mistake or there is two customer from the same household. The later seems to be more likely. this gives an insight that this household is interested in the products from this store.

2. Later we found that the two duplicated phone number is from different provinces. so the same household theory doesnt hold. And so we have to deal with the duplicate phone number when we need to send texts or call for further promotions.

# Customer informations 

1. We have done some queries to understand the age limit of the customers.

2. Found the top 3 customers that have made purchases

3. Found customers based on professions and gender. This will help in marketing geared towards the  specific customer segmentation.

4. Payment method : This is an important aspect that we have found out from the dataset. This can indicate the purchase power of the customer. People with credit card payments sometimes lean towards buying products since they dont have to pay right away. So making marketing with this information in mind, we can make personalized advertisement and check how much they are willing to pay and push products to them within that comfortable range that they are willing to pay.

5. Lastly we have made a segmentation of the day of the week when the sale is the highest where we find that Saturday has the highest number of sales. So, the customers are more willing to buy around that certain day of the week, considering it's holiday the next day and people would want to finish their tasks before the holiday.
We can make this conclusion because we see that sunday has the 2nd last sale. so people would buy less on sunday, and most on saturday.







