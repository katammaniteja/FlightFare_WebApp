# FlightFare-Prediction
Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable. As data scientists, we are gonna prove that given the right data anything can be predicted. Here you will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities. <br>


### Features
The train dataset contains 11 features and 10684 Records
- Airline: The name of the airline
- Date of Journey: The date of journey
- Source: The source from which the service begins
- Destination: The destination where the service ends
- Route: The route taken taken by the flight to reach the destination
- Dep_Time: The time when the journey starts from the source
- Arrival_Time: Time of arrival at the destination
- Duration: Total duration of flight
- Total_Stops: Total stops between the source and destination
- Additional_Info: Additional Information about the flight
- Price: The price of the ticket

### Random Forest
I have implemented Random Forest Algorithm and got an accuracy of 81.4%. After performing Hyperparameter tuning my accuracy was increased to 83.5%.
#### Performance Metrics:
![image](https://user-images.githubusercontent.com/78750315/123424331-532f5900-d5de-11eb-8738-849dca8b03db.png) <br>
