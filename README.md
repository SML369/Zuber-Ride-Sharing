# Zuber-Ride-Sharing

Project Description

Zuber is a new ride-sharing company launching in Chicago. As a data analyst, my goal is to identify patterns in the available data to better understand passenger preferences and the impact of external factors, such as weather, on ride frequency.

This project involves working with a database containing information on taxi trips in Chicago, analyzing competitor data, and testing a hypothesis regarding the effect of weather conditions on the number of rides.

# Data Description

The dataset consists of four tables:

1. Neighborhoods (City District Information)

neighborhood_id: Unique identifier for the neighborhood

name: Name of the neighborhood

2. Cabs (Taxi Information)

cab_id: Unique identifier for the vehicle

vehicle_id: Technical ID of the vehicle

company_name: Name of the company that owns the vehicle

3. Trips (Ride Data)

trip_id: Unique identifier for the trip

cab_id: Vehicle ID assigned to the trip

start_ts: Timestamp of trip start (rounded to the nearest hour)

end_ts: Timestamp of trip end (rounded to the nearest hour)

duration_seconds: Trip duration in seconds

distance_miles: Trip distance in miles

pickup_location_id: Neighborhood ID where the trip started

dropoff_location_id: Neighborhood ID where the trip ended

4. Weather Records (Weather Conditions During Trips)

record_id: Unique identifier for the weather record

ts: Timestamp when the weather data was recorded (rounded to the nearest hour)

temperature: Temperature at the time of the record

description: Short description of weather conditions (e.g., "light rain," "scattered clouds")

# Analysis Approach

# Data Cleaning & Preprocessing:

* Checked for missing or inconsistent values

* Merged datasets based on time and location

* Exploratory Data Analysis (EDA):

Identified ride trends by time of day, company, and neighborhood

Analyzed trip duration and distance distributions

* Hypothesis Testing:

Examined the impact of weather on ride demand using statistical analysis

Compared ride frequency on rainy vs. clear days

* Visualizations:

