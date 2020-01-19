# StateBuses-EDA
Performed EDA on sample data provided by a bus aggregator active in USA. The task is to identify patterns in booking and travel on a particular route_no.

# Problem Statement:
Try to answer the following questions with data and visualizations using any tool: 

1. How many days before the travel date do passengers book their tickets?
2. How does above distribution vary across routes and departure times?
3. Does day of the week for travel date influence occupancy for different routes?

Any other interesting patterns that you can find. Use your imagination.

# Data Description: 

Attached is sample bookings dataset for a small bus provider. 
Given below are the fields and the description

1. Order_date – date of booking
2. Route_no - defines the route taken, sample pick and drop stop can have multiple route_nos depending on the departure time
3. From_stop – the id for the pickup stop
4. To_stop – the id for the drop-off stop
5. Departure_time – time of bus departure in HH:MM:SS
6. Travel_date – Date of travel
7. Passengers_booked_index – Indicator indicating no. of total passengers booked for the particular route_no on the date of booking. Cumulative sum of index for a particular route_no, travel_date group should not exceed 36. 36 indicates 100% occupancy for the particular route_no for a particular travel date 
A combination of pick and drop stop is identified as the route for a particular route_no 
