## EPL 448 Data Mining 
 Epl448_Project

Mining Massive Datasets

### Flight Price Prediction

## Team Members
- Sotiris Meletiou
- Charalampos Papadimos
- Panayiotis Liotatis

# Website
[https://machinehack.com/hackathons](https://www.kaggle.com/)
# Dataset
[Dataset] [(https://machinehack.com/hackathons/iiit_nr_taxi_trip_fare_prediction_challenge/overview)](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction/data)


# Dataset Info
|File    | Number of Rows|Number of Columns|
|--------|---------------|-----------------|
|Economy | 206774        | 11              |
|Business| 93487         | 11              |
|Clean   |    ?          | ?               |

#### Columns of Business and Economy
| Column Name | Description                                     |
|-------------|-------------------------------------------------|
| date        | Date of the flight                              |
| airline     | Airline company                                 |
| ch_code     | Flight code (character)                         |
| num_code    | Flight code (numeric)                           |
| dep_time    | Departure time                                  |
| from        | Departure city                                  |
| time_taken  | Duration of the flight                          |
| stop        | Number of stops                                 |
| arr_time    | Arrival time                                    |
| to          | Destination city                                |
| price       | Price of the ticket                             |

| Feature          | Description                                                                                            | Unique Values                              |
|------------------|--------------------------------------------------------------------------------------------------------|--------------------------------------------|
| Airline          | Name of the airline company                                                                            | 6                                          |
| Flight           | Information regarding the plane's flight code                                                          | -                                          |
| Source City      | City from which the flight takes off                                                                   | 6                                          |
| Departure Time   | Categorical feature obtained by grouping time periods into bins                                        | 6                                          |
| Stops            | Number of stops between the source and destination cities                                              | 3                                          |
| Arrival Time     | Categorical feature created by grouping time intervals into bins                                       | 6                                          |
| Destination City | City where the flight will land                                                                        | 6                                          |
| Class            | Information on seat class                                                                              | 2 (Business, Economy)                      |
| Duration         | Overall amount of time it takes to travel between cities in hours                                      | Continuous                                 |
| Days Left        | Derived characteristic calculated by subtracting the trip date by the booking date                     | Continuous                                 |
| Price            | Target variable storing the ticket price                                                               | Continuous                                 |

The Dates for the business and economy flights starts from 11/2/2022. So we will assume that the info we have are from the 10/2/2022.
So with that in mind we will attempt to create our own Clean file and not use the one that is available from the website.

The column flight is the concatanation of  ch_code + num_code
The Departure time and Arrival Time will be translated to Early_Morning Morning Evening Afternoon Night Late_Night
The stops will be translated to writen numbers one two two_or_more
Duration will be found by arr_time - dep_time
Days left will be calculated by Date - 10/2/2022


Research Questions that the description in the website give
The aim of our study is to answer the below research questions:
a) Does price vary with Airlines?
b) How is the price affected when tickets are bought in just 1 or 2 days before departure?
c) Does ticket price change based on the departure time and arrival time?
d) How the price changes with change in Source and Destination?
e) How does the ticket price vary between Economy and Business class?
