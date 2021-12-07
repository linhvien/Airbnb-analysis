# Airbnb-analysis
# Introduction
Airbnb which stands for "Air Bed and Breakfast" is a community platform for booking and renting rooms and apartments. Airbnb allows both private and commercial landlords to rent homes or parts of it through the platform. With the new exciting way in rental service, Airbnb has achieved many fruits since its launch in 2008 until now. According to the Airbnb Statistics (iProperty Management, 2021), more than 900 million overnight stays were booked through Airbnb. More than 5.6 million rental listings of Airbnb are existed in over 200,000 different cities and regions. Airbnb has cooperated with 4 million hosts. Since 2016, Airbnb has partnered with the property suppliers, two of Interplan's subsidiaries, Interhome and Inter Chalet, companies of the Migros. Migros quickly became the largest provider of apartments offered on Airbnb in Switzerland. Thus, the report will focus on the Airbnb activities in Switzerland, especially Zurich in order to make the study more insightful. 
Firstly, the report provides the overview about Airbnb property market in Zurich based on customer perspective. Then, the study digs deep about Airbnb activities in Zurich, Switzerland in term of property, host, and price. There is a detailed list of hypothesis questions for the study.
Regarding overview analysis,
-	What is the average rental price for listings in Zurich, Switzerland?
-	How many listings are there in Zurich, Switzerland?
-	How many room types are there in Zurich, Switzerland?
-	How proportional is review rating of listings in Zurich area?
-	What are the popular neighborhoods with the highest number of listings?
-	How many hosts are there on Zurich Airbnb? Who have the highest number of listings?

Regarding neighborhood/property analysis,
-	Where is top expensive neighborhood in Zurich area in term of Airbnb service?
-	How much is each room type?
-	What is the proportion of room type by property type with respect to the number of listings?
-	What is the proportion of room type by property type with respect to price?

Regarding host analysis,
-	How many new hosts are registered in every year?
-	How many hosts have a single listing or multiple listings?
-	How proportional is a verified host in Zurich, Switzerland?
-	How proportional is a super host in Zurich, Switzerland?
-	Who are top host earners?

Regarding price aspect,
-	What is price distribution?
-	Is there any relationship between earning and price?
-	Is there any relationship between high rating review and prices?
# Data used – source of data
The data file is provided over the official website of Airbnb. The data is downloaded directly from insideairbnb.com (Airbnb, 2021). In order to serve for the purpose of study, the data file comprises three datasets namely Listings, Calendar, and Reviews. Listings dataset had all the information regarding the listings. It had Host name, location, neighborhood, price, monthly price, review score and number of reviews. Calendar dataset had past booking data. Reviews dataset had information regarding the reviews with respect to listing ID. To facilitate the analysis, the study adopts Tableau Public, and joined the three tables together on the basis of Listing ID. The datasets include all needed information about hosts, property, price and income metrics to serve for the study purpose, and draw conclusions.
# Analysis
## Overview of Airbnb Zurich
The dashboard 1 provides overview analysis about Airbnb activities in Zurich, Switzerland. Based on the dashboard 1, the study clarifies the hypothesis questions regarding overview with detailed analysis.
-	What is the average rental price for listings in Zurich, Switzerland?
	The average rental price for listings in Zurich, Switzerland is 170.8 Swiss franc (CHF). That price in Zurich could be seen as one of the expensive prices for rental service.
-	How many listings are there in Zurich, Switzerland?
	There are 1824 listings in total until now in Zurich. Compare to other places, Zurich Airbnb has lower listing numbers.
-	How many room types are there in Zurich, Switzerland?
	There are four main room types of Airbnb in Zurich, namely Entire home, Private room, Shared room, and Hotel room. Entire home or entire apartment is the dominant room type in Zurich with 66.32% while private room accounts for 32.32%. Very few tourists choose Shared room, and Hotel room on Airbnb when visiting Zurich, Switzerland. This is also a common trend of guests using Airbnb because they often tend to want to experience a more private and comfortable space like Entire apartments or private rooms.
-	How proportional is review rating of listings in Zurich area?
	In general, more than 90% of guests at the hotel voted over 3 stars, which is equivalent to being okay to satisfied with the rental service at Airbnb. More specifically, nearly 70% have rated 5 stars with experiences at Airbnb listings in Zurich.
-	What are the popular neighborhoods with the highest number of listings?
	Altstetten and Langstrasse have the most Airbnb listings.
-	How many hosts are there on Zurich Airbnb? Who have the highest number of listings?
	There are 1067 active Airbnb hosts having listings in Zurich, Switzerland. Stephanie and Vision Zurich are the most active hosts of Airbnb in Zurich with 91 and 77 listing in respectively.

![image](https://user-images.githubusercontent.com/69800336/144982436-0ac6e9e6-d4ff-4490-b26f-383d189db229.png)

## Neighborhood/ Property analysis
The dashboard 2 starts with the map to visualize the geographical location with respect to price and listing numbers. The size of location is based on listing numbers, and the price is divided into color category. It is obvious that Altstetten and Langstrasse have the highest number of listings, some of them having higher price than the average price. Based on the dashboard 2, the study clarifies the hypothesis questions regarding property with detailed analysis.
-	Where is top expensive neighborhood in Zurich area in term of Airbnb service?
	City, Lindenhof, and Rathaus are considered the three most expensive places to rent in Zurich. The reason is because those are places located in the center and close to the coast in Zurich.
-	How much is each room type?
	The average price for Entire apartments, Hotel room, Private room, and Shared room is CHF 193, CHF 183, CHF 127, and CHF 108 in respectively. Entire apartments are the most popular room type and also have the highest average price.
-	What is the proportion of room type by property type with respect to the number of listings?
	Entire service apartments accounts for over 50% listings in Entire Home's services. For the Private room type, the private rooms in the villa are the commonly used listing types.
-	What is the proportion of room type by property type with respect to price?
	Renting a boat and a villa are the two most luxurious rental services in Zurich. The average price to rent a whole boat is more than 3050 CHF while the price of the whole villa is about 783 CHF.

![image](https://user-images.githubusercontent.com/69800336/144982470-e8832030-9d9f-4d3f-b8e7-a325347a73ea.png)

## Host analysis
Based on the dashboard 3, the study clarifies the hypothesis questions regarding host with detailed analysis.
-	How many new active hosts are registered in every year?
	There was a remarkable growth in the number of new active hosts in Zurich from 2010 to 2016. However, the number of new hosts has been on a decreasing trend since 2016. This can be explained by the fact that Airbnb cooperates with Migros as a largest rental supplier. The largest rental cooperation could impact smaller providers, leading to the decrease in host numbers.
-	How many hosts have a single listing or multiple listings?
	It is obvious that most hosts advertise only one listing on Airbnb at 878 hosts with 88% active hosts. Host with multiple listings accounts for only 12% active hosts, but own 52.2% listing numbers in Zurich.
-	How proportional is a verified host in Zurich, Switzerland?
	85.19% of hosts have been identified, ensuring credibility in the rental service. Verified hosts received a greater number of reviews and they tend to have higher price.
-	How proportional is a super host in Zurich, Switzerland?
	Only 19.49% are super hosts, while 80.41% are regular hosts. Super hosts are those that meet Airbnb's service standards are more likely to make it a business. Customers also prefer using Super host's service because the average price is cheaper and the service quality is guaranteed. Super hosts tend to get twice as many reviews as regular hosts. 
-	Who are top host earners?
	James, Stephanie, and Chris are top three host earners in Zurich Airbnb. Three of them are host with multiple listings.

![image](https://user-images.githubusercontent.com/69800336/144982498-318bb08c-e5fc-4329-b980-7b2b3f19315e.png)

## Price analysis
Based on the dashboard 4, the study clarifies the hypothesis questions regarding price with detailed analysis.
-	What is the price distribution?
	The distribution of rental price of Airbnb in Zurich is highly right skewed. Most listings have price lower than CHF 500. Extreme points of price distribution is due to the luxurious rental service such as boat or entire villa. 
-	Is there any relationship between earning and price?
	Rental price of Zurich is statistically positively associated with host income with p-value lower than 0.01. It means that the higher the rental price, the higher the income hosts could earn with the confidence level 99%. According to the trend line, if the price increase by CHF 1, the host earning could increase by CHF 13.55. However, it is noticeable that if the price of listing is too high more than CHF 500, the host earning is likely to go down in comparison to the price lower than CHF 500.
-	Is there any relationship between high rating review and prices?
	Rental price has insignificant impact on high rating reviews. This suggests that visitors evaluate and vote on rental services through experience, not through service price.

![image](https://user-images.githubusercontent.com/69800336/144982556-a3754007-1d8a-4867-8e84-e091c1afe70c.png)
 
# Overall findings
Some of overall finding are drew up from the analysis:
-	70% listings have a rating of 5.0
-	Entire home or entire apartment are dominant room types with the highest average price and listing numbers.
-	The number of new registered hosts has been on a decreasing trend since 2016.
-	Super host have higher number of booking and review with lower price.
-	Host with multiple listings earn better income from Airbnb.
-	Rental price positively affects host income. However, the host earning with price higher than CHF 500 seems lower than the ones with price lower than CHF 500.

# Recommendation
Based on analysis and findings, the study suggests some of recommendation to contribute the development of Airbnb activities in Zurich.
Regarding neighborhood aspects, Airbnb should expand the number of houses in the central area and close to the sea because that place often has many tourist destinations. Airbnb can provide financial support such as fee reduction or provide consultants for hosts with listings in this area. As the central area has more listings, rental prices in these areas will decrease and attract more visitors.
Regarding host aspects, Airbnb should encourage more hosts to become super hosts by meeting criteria to aim for better service quality. When compared to normal hosts, super hosts have lower pricing and much greater reviews about twice as many.
Regarding price and earning aspects, hosts of Airbnb could increase the rental price or diverse the listing portfolio to enhance the income.
Conclusion
The report is about to analyze the Airbnb activities in Zurich, Switzerland based on detailed list of hypothesis questions in term of overview analysis, property, host, and price.

 
# Reference
Airbnb. (2021). Inside Airbnb data. Airbnb. Retrieved from http://insideairbnb.com/get-the-data.html
iProperty Management. (2021). Airbnb Statistics. iProperty Management. Retrieved from https://ipropertymanagement.com/research/airbnb-statistics


### © 2021 linhvientran
