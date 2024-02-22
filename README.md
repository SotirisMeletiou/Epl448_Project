## EPL 448 Data Mining 
 Epl448_Project

Mining Massive Datasets

### Prediction Analysis on Taxi Trip Fares

## Team Members
- Sotiris Meletiou
- Charalampos Papadimos
- Panayiotis Liotatis

# Website
https://machinehack.com/hackathons
# Dataset
[Dataset] (https://machinehack.com/hackathons/iiit_nr_taxi_trip_fare_prediction_challenge/overview)


# Dataset Info
| Number of Rows|Number of Columns|
|---------------|-----------------|
| 3500          | 20              |

| Column Name             | Description                 |
|-------------------------|-----------------------------|
| trip_distance           | The elapsed trip distance in miles reported by the taximeter.        |
| rate_code               | The final rate code is in effect at the end of the trip. 1= Standard rate,2=JFK,3=Newark, 4=Nassau or Westchester, 5=Negotiated fare,6=Group ride |
| store_and_fwd_flag      | This flag indicates whether the trip record was held in vehicle memory before sending it to the vendor and determines if the trip was stored in the server and forwarded to the vendor. Y= store and forward trip N= not a store and forward trip |
| payment_type            | A numeric code signifying how the passenger paid for the trip. 1= Credit card,2= Cash, 3= No charge, 4= Dispute, 5= Unknown, 6= Voided trip |
| fare_amount             |The time-and-distance fare calculated by the meter     |
| extra                   |Miscellaneous extras and surcharges  |
| mta_tax                 |$0.50 MTA tax that is automatically triggered based on the metered rate in use. |
| tip_amount              | Tip amount credited to the driver for credit card transactions. |
| tolls_amount            | Total amount of all tolls paid in the trip. |
| imp_surcharge           |  $0.30 extra charges added automatically to all rides |
| total_amount            |  The total amount charged to passengers. Does not include cash tips |
| pickup_location_id      | TLC Taxi Zone in which the taximeter was engaged |
| dropoff_location_id     |TLC Taxi Zone in which the taximeter was disengaged |
| year                    |The year in which the taxi trip was taken. |
| month                   |  The month on which the taxi trip was taken. |
| day                     | The day on which the taxi trip was taken. |
| day_of_week             | The day of the week on which the taxi trip was taken |
| hour_of_day             | Used to determine the hour of the day in 24 hours format |
| trip_duration           | The total duration of the trip in seconds |
| calculated_total_amount | The total amount the customer has to pay for the taxi. |

