An issue might occur when trying to view the jupyter notebook , check this link to view the notebook(https://nbviewer.org/github/AbdulRasheed6/Sapa_Dataset/blob/main/main.ipynb) 

# Sapa_Dataset
An in depth analysis of the dataset Sapa , for the purpose of deriving meaningful insights and creating a model for predicting future responses of customers


####  Sapa.com is one of the leading eCommerce platforms in Nigeria with millions of daily complete transactions. The goods and services on sapa.com cater for both the elite and the masses which makes it the first choice for almost everybody in Nigeria. 
####  Due to the COVID-19 pandemic that struck the entire world in all areas of living, the companies' daily complete transactions have dropped drastically to thousands.

####  The CEO, Mr Echoke in his recent actions to put the platform back to the top of the eCommerce platforms chain in the country has approved the use of Artificial intelligence in User Personality Analysis. 
####  The company has contracted your team consisting of AI professionals with a special focus on recommender system development to build a robust intelligent model capable of recommending products and services to Users based on their activities on sapa.com.

####   Your team lead has assigned you to the building of a model capable of predicting users’ responses to marketing campaigns based on the features in the provided dataset by the sapa.com data engineer. 
####   The next phase of the project is highly dependent on the accuracy of your model as this is the foundation of what will constitute the features of the proposed recommender system development. Good luck!



### Buisness Analysis & Recommendation



#####   We have been able to build a predictive model:

#####   a) that the company can deploy to identify customers who will be interested in purchasing products from both its online and offline stores, through its new marketing campaign.

#####   b) that the company can use to find the key factors that will have an impact on a customer accept the  product or not.

#####   Most important features that had an impact on Product taken by the customers: Cmp5Accepted,  Recency, Education_Level, Marital_Status and duration_days 
#####   Customers with PhD's,  Master degrees should be the target customers for the company .Customers who registered in 2012-2103 should be targetted for the marketing campaign, also customers who last purchases was between 7-100 are likely to accept the marketing campaign.


#####  Based on EDA ,Factors that affected customer decision negatively  are:
#####  Customers who visited the web more than 20 times did not accept the new marketing campaign and this might be due to so many factors that needs to be thoroughly investigated.
#####  Customers who bought more than 20 goods from the catalog , did not accept the marketing campaign
#####  Customers who spent more than a 1000 on meat did not buy into the new campaign.
#####   From the data given  i noticed that customers who spent more on one of the company's product , did not really buy into the new marketing campaign 

##### Recommendations :-
##### more data is needed for better prediction
##### an extra field should be created to take customer's feedback
##### the  companies products should be improved to a high standard 
#####  Marital_status should be grouped into single or relationship
##### while Education_status should grouped into undergraduate or graduate
#### Customer segmentation should be carried out using an unsupervised technique like Kmeans clustering algorithm
