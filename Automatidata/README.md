# Automatidata TLC Project

Welcome to your new role at Automatidata! This project involves collaborating with the New York City Taxi and Limousine Commission (TLC) to develop a regression model for estimating taxi fares before the ride.

## Project Goal

Automatidata aims to create a regression model that helps estimate taxi fares in advance, leveraging data from the New York City TLC.

## Project Background

Automatidata is in the initial stages of the TLC project. Key tasks include:

- Creating a project proposal with organized milestones.
- Classifying tasks using the PACE workflow.
- Identifying relevant stakeholders.

## Team Members at Automatidata and the New York City TLC

### Automatidata Team Members
- Udo Bankole, Director of Data Analysis
- Deshawn Washington, Data Analysis Manager
- Luana Rodriquez, Senior Data Analyst
- Uli King, Senior Project Manager

*Note: Keep summaries and messages to Automatidata team members concise.*

### New York City TLC Team Members
- Juliana Soto, Finance and Administration Department Head
- Titus Nelson, Operations Manager

*Note: Adjust language and explanations for non-technical roles.*

## Meeting Notes

### Uli King (Senior Project Manager)
- The data team needs a global-level project document outlining goals and milestones.
- Collaboration with Titus Nelson at TLC for visuals.

### Luana Rodriquez (Senior Data Analyst)
- Inspection of TLC dataset before analysis.
- Determining information through EDA.
- Testing model consistency.

### Udo Bankole (Director of Data Analysis)
- Ensuring the model meets project requirements.
- Main talking points for TLC presentation.

### Deshawn Washington's Thoughts and Concerns
- Suggests using Python for the project.
- Emphasizes establishing relationships between variables.
- Recommends A/B testing for analyzing variable relationships.

## Data Dictionary

This project uses a dataset called 2017_Yellow_Taxi_Trip_Data.csv. It data gathered by the New York City Taxi & Limousine Commission and published by the city of New York as part of their NYC Open Data program. In order to improve the learning experience and shorten runtimes, a sample was drawn from the 113 million rows in the 2017 Yellow Taxi Trip Data table.

The dataset contains:

408,294 rows – each row represents a different trip

| Column name             | Description                                                                                             |
|-------------------------|---------------------------------------------------------------------------------------------------------|
| ID                      | Trip identification number                                                                              |
| VendorID                | A code indicating the TPEP provider that provided the record. 1=Creative Mobile Technologies, LLC; 2=VeriFone Inc. |
| tpep_pickup_datetime    | The date and time when the meter was engaged.                                                           |
| tpep_dropoff_datetime   | The date and time when the meter was disengaged.                                                        |
| Passenger_count         | The number of passengers in the vehicle. This is a driver-entered value.                                |
| Trip_distance           | The elapsed trip distance in miles reported by the taximeter.                                           |
| PULocationID            | TLC Taxi Zone in which the taximeter was engaged.                                                        |
| DOLocationID            | TLC Taxi Zone in which the taximeter was disengaged.                                                     |
| RateCodeID              | The final rate code in effect at the end of the trip. 1=Standard rate, 2=JFK, 3=Newark, 4=Nassau or Westchester, 5=Negotiated fare, 6=Group ride |
| Store_and_fwd_flag      | This flag indicates whether the trip record was held in vehicle memory before being sent to the vendor, aka “store and forward,” because the vehicle did not have a connection to the server. Y=store and forward trip, N=not a store and forward trip |
| Payment_type            | A numeric code signifying how the passenger paid for the trip. 1=Credit card, 2=Cash, 3=No charge, 4=Dispute, 5=Unknown, 6=Voided trip |
| Fare_amount             | The time-and-distance fare calculated by the meter.                                                     |
| Extra                   | Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges. |
| MTA_tax                 | $0.50 MTA tax that is automatically triggered based on the metered rate in use.                          |
| Improvement_surcharge   | $0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015. |
| Tip_amount              | Tip amount – This field is automatically populated for credit card tips. Cash tips are not included.    |
| Tolls_amount            | Total amount of all tolls paid in trip.                                                                 |
| Total_amount            | The total amount charged to passengers. Does not include cash tips.                                      |
