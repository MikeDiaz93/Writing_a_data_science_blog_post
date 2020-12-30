# Writing_a_data_science_blog_post
Brief analysis, exploration, and modeling of an airbnb dataset from San Francisco (October 2020)



The libraries we used are : 
Matplotlib,
Seaborn, 
Pandas,
NumPy,
SciPy,
Sklearn, 
Xgboost.



The motivation for the project was:
The motivation was because I wanted to put in practice my knowledge that I've learned during the Data Science Nano Degree program. I mean
curiosity and passion were my drivers to work with data and explore them and propose insights of my findings. 



The files in the repository are:

Lisitngs file, where the information with information about hosts, neighborhood, availability per room, characteristics of rooms, 
ids, description of rentals, reviews among others. With 74 variables and 7087 observations. 



Summary of the results of the analysis:
 
In this exercise we explore the variables, in this case the price variable. 
For example, the most common words a host post or promotes are: private rooms, studios, bedrooms, room apartments, modernity, gardens, spacious spaces,
rooms in hotel, views, condos, or charming rooms.

We couldn't worked with the neighborhood  variable, because it could bias our results. 

The variable price and month availability seem to has not correlation, but the revenue per available room and month availability has negative correlation.
The average monthly revenue for a San Francisco host is 4870.32 dollars, and the median monthly revenue is 2016 dollars. 

Our accuracy score says that we tend to predict with 84% of the cases (as True), if hosts could receive much money than the average by amennity offered or characteristic of the room offering their rooms rentals or houses. 

According to the Feature importance type "Gain", the top 10 amenities, caracteristics or 
features that describe our classification model are: gym, bedrooms, air conditioning, wifi, room_type_hotel_room,building staff, roop_type_entire_home,Essentials, Elevator, kitchen.

Super hosts tend to earn a little bit more than false hosts. 

Entire houses or condos tend to be the most expensive rentals.

As the number of bedrooms increases, the price also increases. 

The variables with the high correlations with price are: bedrooms, accomodates, and number of beds. 

The r2 score and RMSE for the Test say us that as they are higher than the r2 score and RMSE of Train,  we need more data in order to model the price of the rentals.

The top 10 most important vairbales, for explianing the regression models are: reviews_per_month, availability_365, number_of_reviews, review_scores_rating,
maximum_nights, availability_90, bedrooms, availability_30, availability_60, maximum_maximum_nights



Necessary acknowledgements:

It's important to consider many datasets or resources in order to extract valuble information. With a dataset with this proportions (7087,74) sometimes 
it's difficult to get a deep insight of a complex world. 
