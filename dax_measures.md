## Power BI Measures Summary

# Average Age

Definition: Calculates the average age of passangers.

DAX Example:

Average Age = AVERAGE(flight_bookings_sample[Passenger_Age])

Insight:

- Shows the typical age of travelers.

- Helps tailor marketing campaigns or offers: younger passengers may prefer budget flights, while older passengers may value comfort and flexibility.

# Average Ticket Price

Definition: Calculates the average price of tickets sold.

DAX Example:

Average Ticket Price = AVERAGE(flight_bookings_sample[Ticket_Price])

Insight:

- Tracks the typical cost of flights booked.

- Helps analyze pricing strategy and identify trends like seasonal price changes or popular routes.

# Number of Bookings

Definition: Counts the total number of flight bookings.

DAX Example:

Number Of Bookings = COUNT(flight_bookings_sample[Booking_ID])

Insight:

- Indicates flight demand and business activity.

- Can identify peak travel periods and inform staffing or promotions.

# Total Price of Tickets

Definition: Calculates the total revenue from all flight tickets.

DAX Example:

Total Price Of Tickets = 
SUM(flight_bookings_sample[Ticket_Price])

Insight:

- Shows overall revenue from bookings.

- Helps evaluate performance of routes, pricing, and marketing campaigns.




