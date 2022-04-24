# Amazon_Vine_Analysis
**Module 16 Challenge: Amazon Vine Analysis: (Colab / Pyspark)**

## Overview:
The purpose of this analysis is to analyze Amazon reviews written by members for paid Amazon Vine Program and compare those to non-paid public review submitted. The objective is to determine if there is a bias from the Vine members as they submit reviews of products. My review used the luggage category from the Amazon data base and utilizing Google Colab and Pyspark to perform the ETL from AWS webserver.

## Analysis Results:
### *Total Qualified Luggage Reviews Vine (paid) vs. non-Vine (unpaid):*

   #### •	There was a total of 6,711 luggage review after applying the following filters:

        •		Total votes were greater than or equal to 20

        •		Helpful votes were more than or equal to 50% of total votes

   #### •	6,690 reviews from non-Vine while only 21 reviews were from Vine members

   #### •	Almost 99% of the Luggage reviews in the filtered data set came from non-Vine users
    
![image](https://user-images.githubusercontent.com/95320265/164950465-09900cd4-bb4a-4bbe-a0d8-7b1f55be2c5d.png)

![image](https://user-images.githubusercontent.com/95320265/164950468-55e8c22a-7eda-4738-b650-7e6d6a977f8a.png)

![image](https://user-images.githubusercontent.com/95320265/164950471-308e389d-64ae-4738-b411-4c9bceb3a483.png)

  
 
### *Five-star reviews Vine (paid) Reviews vs Non-Vine (unpaid):*

   #### •	Total five-star reviews from the filtered data were 3,458, which is 51% of all the luggage reviews.

   #### •	3,448 of the five-star reviews were from non-Vine users, while only 10 were from Vine members.
    
![image](https://user-images.githubusercontent.com/95320265/164950480-fca7c16b-b935-422e-8186-9e6077642c2d.png)

![image](https://user-images.githubusercontent.com/95320265/164950485-779417e3-ec43-436c-aaaa-b5b3fb192bf6.png)

![image](https://user-images.githubusercontent.com/95320265/164950486-ef8fe054-ad17-4acc-aaff-518f8f769d4f.png)



### *Percentage of five-star reviews for Vine (paid) vs non-Vine (unpaid):*

   #### •	47.6% of the Vine reviews were five-star

  ####  •	51.3% of the non-Vine reviews were five-star
    
![image](https://user-images.githubusercontent.com/95320265/164950493-9dcc2e99-2317-4c75-ae21-15759d7c336d.png)

![image](https://user-images.githubusercontent.com/95320265/164950500-b949d842-2af1-45a2-91a1-d6a6259b5f99.png)


  
## Summary:
There is not a positive bias for Vine (paid) reviews verses non-Vine (unpaid) reviews in Amazon’s Luggage category. In fact, a great percentage of the unpaid review were listed as five-star reviews. This dataset had an insignificant number of paid reviews with over 99% of the luggage reviews coming from unpaid users.
