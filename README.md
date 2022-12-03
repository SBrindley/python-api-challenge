# python-api-challenge
Week 6 Homework
Background
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

WEATHERPY


Latitude vs Temperature

![image](https://user-images.githubusercontent.com/113051302/205462157-f5f4287b-1859-4bc4-b022-cc9178ed68cc.png)

Latitude vs Humidity

![image](https://user-images.githubusercontent.com/113051302/205462172-6bbe3583-abb7-49a8-a904-2a018447009d.png)


Latitude vs Cloudiness

![image](https://user-images.githubusercontent.com/113051302/205462180-b7c59394-bdc0-42a8-9120-36173d84d64d.png)

Latitude vs Wind Speed

![image](https://user-images.githubusercontent.com/113051302/205462190-ff1d03c1-030d-4b09-8f3b-836ac7697353.png)


Temperature vs. Latitude Linear Regression Plots
Northern
![image](https://user-images.githubusercontent.com/113051302/205462203-f14342af-b3c7-4e95-b933-78a94631c0fa.png)

Southern
![image](https://user-images.githubusercontent.com/113051302/205462212-7221494c-4df6-4546-b996-bfb2f6ceb644.png)

Discussion about the linear relationship: The northern diagram shows us it has a good negative r value (-0.839), this shows us the further away the latitude is from 0, the colder the temperature which is what you would expect. The southern one has a positive r value (0.56) which shows the closer to the latitude being zero the higher the temperature. The results proving this are not as strong as the northern hemisphere which shows us in the r values


Humidity vs. Latitude Linear Regression Plot

Northern
![image](https://user-images.githubusercontent.com/113051302/205462223-9e325258-cd66-4656-b2e2-f94a8e30f5f6.png)

Southern
![image](https://user-images.githubusercontent.com/113051302/205462235-1473e495-ffde-4f7b-bf9f-0751f38ca601.png)

Discussion about the linear relationship: The r value for the Northern hemisphere (0.30) shows us that there is a slight pattern between the latitude and the humidity with it veering towards a higher humidity increasing with the latitude. However, I would not consider this a strong pattern. The r value for the Southern hemisphere (0.52) shows a stronger pattern than the Northern hemisphere with the humidity increasing as the latitude reaches zero, but still not a strong correlation.


Cloudiness vs. Latitude Linear Regression Plot

Northern
![image](https://user-images.githubusercontent.com/113051302/205462248-ebdf6e15-9ee8-4d3c-9231-3cc003ce0e58.png)


Southern
![image](https://user-images.githubusercontent.com/113051302/205462262-484cd093-6517-47f1-9a3f-0f03fa272b7a.png)

Discussion about the linear relationship: The r value for the northern hemisphere (0.18) shows little pattern in the wind sppeed and the Southern one is not much better at (0.23) I do not think there is a correlation between the Cloudiness and Latitude.

Wind Speed vs. Latitude Linear Regression Plot

Northern
![image](https://user-images.githubusercontent.com/113051302/205462281-a137f8bf-7488-427a-a438-591cb31327ad.png)


Southern
![image](https://user-images.githubusercontent.com/113051302/205462290-7a6deeb8-b4a4-49a0-ab7d-5cd4e8817e0b.png)

Discussion about the linear relationship: The Northern hemisphere has an extremely low r value showing little patterns between the wind speed and the latitude. The Southern Hemisphere shows a negative r value of 0.45 which is a stonger r value than the Northern graph so the Southern Hemisphere could possibly have more of a pattern.



VACATIONPY

Step 1: Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.


![image](https://user-images.githubusercontent.com/113051302/205462417-52208bab-3763-44a7-a7d9-3d2c367c85ac.png)

