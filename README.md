# Flight-price-prediction

In this project, I'm going to analyse and explore a dataset obtained from “Ease My Trip” website to conduct various statistical hypothesis tests in order to get meaningful information from it.

“Ease My Trip” is an internet platform for booking flight tickets, and hence a platform that potential passengers use to buy tickets. A thorough study of the data will aid in the discovery of valuable insights that will be of enormous value to passengers.

The data will be used to make an accurate salary predictor to understand what influences prices.

# The aim of our study is to answer the below research questions:

1)How does the ticket price vary between Economy and Business class?

2)Does price vary with Airlines?

3)How is the price affected when tickets are bought in just 1 or 2 days before departure?

4)Does ticket price change based on the departure time and arrival time?

5)Does the number of stops influences the price?

6)What variables influence most the price?


# Features
The various features of the cleaned dataset are explained below:

Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.

Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.

Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.

Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.

Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.

Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.

Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.

Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.

Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours. 10.Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.

Price: Target variable stores information of the ticket price.
