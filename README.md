# capstone_hotel
[diff]@@jihiyhbhh@@
#### here two colabs are present one is mine (indivisually, in which i have done my part) and other is of my team including me, both are of same project i.e. 'hotel booking analysis'.

## let's have a look, what we have done here.

Here the data-set given, was containing 119390 entries (rows) for two types of respective hotels for three years (2015-17), and each entry containing 32 categorical features which were especially helpful during complete analysis.
## Data-set
#### data-set given (contains the columns) can be discribed as:

'hotel': hotels were of two types city and resort hotel

'is_canceled': binary valued data-set gives discription of whether room cancelled or not

'lead_time': gives the discription of the time duration between booking date and check-in date

'arrival_date_year': discribes the year of arrival of customer

'arrival_date_month': discribes the month of arrival of customer

'arrival_date_week_number':discribes the no. of week in that year

'arrival_date_day_of_month':discribes the date of arrival of customer

'stays_in_weekend_nights': discribes that how many days in a week the customer stayed

'stays_in_week_nights': discribes that how many weekends the customer stayed

'adults': gives no. of adult customers

'children': gives no. of child customers

'babies': gives no. of baby customers

'meal': discribes the different types of meals

'country': countries from where the guests/customers come to stay

'distribution_channel': mode of booking/favourable partners who sends customes

'is_repeated_guest': discribes the guest's retention

'previous_cancellations': discribes that how many previous bookings cancelled

'previous_bookings_not_canceled': discribes that how many previous bookings aren't cancelled

'reserved_room_type':reserved room type ['C', 'A', 'D', 'E', 'G', 'F', 'I', 'B', 'H', 'P', 'L', 'K'] (A=AAA discount available; B=Complimentary breakfast; 
C=Complimentary coffee; D=Complimentary evening cocktail; E=European style hotel; F=Free local phone calls; G=Parking available; H= Complimentary use of health facilities L=Complimentary local transportation shuttle; P=Indoor Pool; K=Kitchen facilities )

'assigned_room_type': assigned room type ['C', 'A', 'D', 'E', 'G', 'F', 'I', 'B', 'H', 'P', 'L', 'K'] (A=AAA discount available; B=Complimentary breakfast; C=Complimentary coffee; D=Complimentary evening cocktail; E=European style hotel; F=Free local phone calls; G=Parking available; H= Complimentary use of health facilities L=Complimentary local transportation shuttle; P=Indoor Pool; K=Kitchen facilities )

'booking_changes': gived no. of changed bookings

'deposit_type':gives deposit type ['No Deposit', 'Refundable', 'Non Refund']

'agent': represented by agent id

'company': represented by company id

'days_in_waiting_list': no of days on waiting list

'customer_type': type of customer ['Transient', 'Contract', 'Transient-Party', 'Group']

'adr':average daily rate

'required_car_parking_spaces' : no of required car parking spaces

'total_of_special_requests' : total no of special request

'reservation_status' : reservation status

'reservation_status_date' : reservation status date
       
# EDA and data cleaning

here the EDA was done by cleaning data, like replacing null values with satisfactory values, deleting duplicate rows, changing data-set to relevent data type which were not in relevent form.

### Now finally we tried to extract maximum possible legal questions from given data-set and tried to solve them to extract pattern and hidden analysis behind it, the questions are like,

Q1. Which hotel type is preferred the most?

Q2. which hotel has a higher booking cancellation?

Q3. How long do people prefer to stay in both hotels?

Q4. Which hotel require more car parking spaces?

Q5. Which hotel generates the most revenue?

Q6. Which are the busiest months for hotel?

Q7. Which hotel has the highest lead time?

Q8. Was a hotel likely to receive a disproportionately high number of special requests?

Q9. Visualization of monthly bookings and monthly cancellations.

Q10. Relationship between lead time and cancellation.

Q11. Which type of customers book hotels the most?

Q12. Which type of customers make the special requests?

Q13. Which customer type has the highest cancellation of bookings?

Q14. When the best time of year to book a hotel room is?

Q15. Relationship between ADR and the total number of stays.

Q16. Which hotel generates the highest revenue i.e. Average Daily Rate Per Person?

Q17. Which distribution channel is mostly used?

Q18. Which distribution channel generates the most revenue for hotels?

Q19. analyzing which deposit type is preferred most?

Q20. Which type of meal is most and least preferred by the customers?

Q21. Analyzing customer retention on customer type.

Q22. Which room type is in most demand and which room type generates the highest average daily rate?

Q23.Which country has the greatest number of guests?

### Now briefly, concluded as;

1.City Hotels are more popular and generate more revenue compared to Resort Hotels. 

2.Duration of stays and ADR are negatively correlated.

3.The busiest months for hotels are July and August for both types of hotels.

4.Higher lead time leads to higher booking cancellations and vice-versa.

5.The most demanding room type is A (room with a discount available).

6.Room type H (room with complementary health facilities) generates more revenue for hotels as compare to other room types.

7.The popular meal type is BB (Bed and Breakfast).

8.Southern Europe (group countries) is the best contributor.

So, at the end of our analysis we can say things like business partners, customer satisfaction, choices available for the customers, services provided by hotels play a major role in hotel’s establishment and sustainability.

Therefore for a good start the things appeared, finally after this entire analysis, should be taken into consideration.
