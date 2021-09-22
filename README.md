#HOTEL BOOKING ANALYSIS
---
---
##**KPIS for Hotel Industry**

---
1.   Occupancy

>Occupancy rate refers to the number of available rooms in a hotel that are occupied at any given time. It can be used to assess how efficient a hotel is at making use of the space available and can be used on conjunction with other metrics to maximise revenue. The occupancy rate is expressed as a percentage and calculated by dividing the number of occupied rooms by the total number of rooms.


2.   ADR

> The Average Daily Rate or ADR is a popular KPI for hotel industry. The ADR is the average rate at which each room at the hotel was sold on a given day. It is calculated by taking the Average room revenue and dividing it by the total number of rooms sold.
This, however, does not include rooms that are occupied by staff, under maintenance of the ones that are

3.   RevPAR

>RevPAR or Revenue per available room is another metric to measure the performance of the property in the hotel business which is very popular. The RevPAR metric helps in evaluating the hotel’s operational performance. This measure can further be used as a coach to make good future investment resolutions and meet the targets set. By finding out the RevPAR, the answer devised could act as a productivity indicator for a hotel investor. This also reflects how much a hotel can charge for its rooms and how successful it is at selling the inventory which is available

4. Average Length of Stay or ALOS

>The Average Length Of Stay is a kpi for hospitality industry metric which helps in making it easy to find out the length of stay of guests which are booked at your hotel. The ALOS metric is calculated by dividing the occupied rooms by a number of bookings. So if the number is high it means greater profit with requirements of very less labor. While if the number of the computed ALOS is low, it obviously results in lesser profit.

5. Total Available Rooms

>Total Available Rooms are the number of rooms which are readily there to be booked in the hotel. In order to compute the Total Available Rooms, you need to sum up the Available Rooms and also the number of Occupied Rooms.
This metric in kpi hospitality needs to be monitored as it is essential for the proper planning of your inventory which would further lead to proper number of room bookings.

## **Colums and their meaning**
---
0. hotel 
>Hotel (H1 = Resort Hotel or H2 = City Hotel)

1. is_canceled
>Value indicating if the booking was canceled (1) or not (0)

2. lead_time
>Number of days that elapsed between the entering date of the booking into the PMS and the arrival date

3. arrival_date_year
>Year of arrival date

4. arrival_date_month
>Month of arrival date

5. arrival_date_week_number
>Week number of year for arrival date

6. arrival_date_day_of_month
>Day of arrival date

7. stays_in_weekend_nights
>Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel

8. stays_in_week_nights
>Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel

9. adults
>Number of adults

10. children
>Number of children

11. babies
>Number of babies

12. meal
>Type of meal booked. Categories are presented in standard hospitality meal packages: Undefined/SC – no meal package; BB – Bed & Breakfast; HB – Half board (breakfast and one other meal – usually dinner); FB – Full board (breakfast, lunch and dinner)

13. country
>Country of origin. Categories are represented in the ISO 3155–3:2013 format

14. market_segment
>Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”

15. distribution_channel
>Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”

16. is_repeated_guest
>Value indicating if the booking name was from a repeated guest (1) or not (0)

17. previous_cancellations
>Number of previous bookings that were cancelled by the customer prior to the current booking

18. previous_bookings_not_canceled
>Number of previous bookings not cancelled by the customer prior to the current booking

19. reserved_room_type
>Code of room type reserved. Code is presented instead of designation for anonymity reasons.

20. assigned_room_type
>Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons.

21. booking_changes
>Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation

22. deposit_type
>Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.

23. agent
>ID of the travel agency that made the booking

24. company
>ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons

25. days_in_waiting_list
>Number of days the booking was in the waiting list before it was confirmed to the customer

26. customer_type
>Type of booking, assuming one of four categories: Contract - when the booking has an allotment or other type of contract associated to it; Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking

27. adr
>Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

28. required_car_parking_spaces
>Number of car parking spaces required by the customer

29. total_of_special_requests
>Number of special requests made by the customer (e.g. twin bed or high floor)

30. reservation_status
>Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer; Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why

31. reservation_status_date
>Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the
