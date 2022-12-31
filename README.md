Hotel Booking Data Analysis

Objective:-

We are provided with a Hotel booking dataset.Our main objective is to perform EDA on the given dataset and draw useful conclusion about general trends in hotel booking.

Dataset:-

We are given a hotel booking dataset.This dataset contain booking information of City hotel and resort hotel.We have to perform some manipulation and functions to get some insight from the Dataset.

Variable Description:-

There are list of variables as shown as below:-

1) Hotel: Name of Hotel (City or Resort)

2) is_ cancelled: Number of cancelled booking

3) arrival_year: Guest arrival year

4) arrival_month: Guest arrival month

5) Adult:Number of adult arrived

6) Children:Number of children arrived

7) babies:Number of babies arrived

8) meal: Type of meal(FB,HB,BB)

9) Country: Name of country

10) is_repeated_guest:Number of repeated guest

11) previous_cancellation: Number of previous cancelled booking

12) reserved_room_type:Room type (AC, Normal)

13) booking_changes: Number of changes done in booking

14) deposit_type: Type of deposit (refund,no deposit)

15) customer_type:Type of customer (group or transient)

16) reservation_status: Reservation status (checked out or cancelled)

17) required_car_parking:Car parking required

18) Number_of_booking:Number of bookings


Data Cleaning and Feature engineering:-

1)Removing duplicate values:- All duplicate values were dropped.

2)Handling null and missing values:- I found some null and missing values in data in column is_cancelled,is_repeated_guest and previous_cancellation.I replace thàt null values with average of that column

3)Converting and updating format and datatype of columns:-I change datatype of some columns.

Mainly used libraries are matplotlib and seaborn and the following graphs and plots are:-

- Bar plot
- Histogram
- scatter plot
- Line chart
- Heatmap
- pair plot
- Box plot

Conclusion:-

- City hotel seems more prefered among customers

- Most Number of booking made in May month from Paris compared to India and USA

- Most preferred meal type is FB from group type customer.

- Most Number of booking is in year 2015 and 2017.

- Most number of booking changes placed in year 2019 that is 7 from group type of customer.

- May and Feb month have most number of booking.

- Most preferred room type is AC as compared to Normal room type.

- Maximum number of children arrival in in City hotel from Country Paris



