# Hotel Bookings Analysis

# Project Background

This data set pertains to two types of hotels: resort and city hotel and the demands of each type. It includes information about bookings, guests, parking spaces, etc. 

Insights and recommendations are provided on the following key areas:

- **Hotel Operations** 
- **Booking and Cancellation trends** 
- **Customer Demographics and Behavior**
- **Revenue and Occupancy**

The SQL queries used to inspect and clean the data for this analysis can be found here [here](https://github.com/crisaliscarrion/HotelBookings/blob/main/hotel%20bookings%20queries.txt).


# Data Structure & Tools

This data set was retrieved from Kaggle(See Reference). 

The dataset contains 119,390 entries and 32 columns, providing details about hotel bookings. The columns include data types such as STRINGS, FLOAT, DATE and INTEGERS.

The tools used in this project were SQL to clean and analyze the data and RStudio for additional analysis and creation of the plots. 


# Executive Summary

### Overview of Findings

Various trends and patterns were identified, and attributes were quantified to analyze the previously listed key areas. The biggest customer type that made the most bookings and the highest revenue is Transient. This customer type tends to book via a travel agency or tour operator and prefers the City Hotel over the Resort Hotel. The months with the highest number of bookings are August and July, but these are also the months with the highest number of cancellations.

# Insights Deep Dive

### Hotel Operations:

* **Special Requests** Around 58.9% of the bookings did not include a special request. However, 38.69% involved one or two special requests. The maximum number of special requests made was five, representing only 0.05% of the total bookings. When considering the type of hotel and customer, the Transient customer type made the most one or two special requests, primarily for the City Hotel. Specifically, 19.98% of Transient customers staying in the City Hotel made one or two special requests, compared to 16.56% at the Resort Hotel.

* **Parking Space** The data showed that 93.79% of bookings did not require a parking space. Among those that did, the Transient customer type accounted for the majority, with 48.35% requesting parking at the City Hotel and 21.33% at the Resort Hotel.


![operation analysis](https://github.com/user-attachments/assets/dd01c69e-76c2-4587-a333-9f735896f14b)

![parking space](https://github.com/user-attachments/assets/3bce3f7f-d80d-4845-9bb4-3dc584de7265)
---

### Booking and Cancellation trends:

* **Cancellation Percentage** The data showed an overall cancellation rate of 37.07%. Among these, 27.74% came from City Hotels, compared to 9.32% from Resort Hotels. Transient customers had the highest cancellation rate at 30.6%.
  
* **Monthly Cancellation Percentage** The top three months with the highest cancellation rates were August, July, and May, while the months with the lowest rates were January, December, and November. The Transient customer type had the highest cancellation rate during the peak months, with 8.76% in August, 8.23% in July, and 7.60% in May. For hotels, the City Hotel had the highest cancellation rates during these months (e.g., 7.53% in August, 6.90% in May, and 6.78% in July).

* **Busiest Months**  The months with the most bookings were August and July, following a similar pattern to cancellations.
  
![cancellations by customer type and hotel](https://github.com/user-attachments/assets/3941a4d0-e1fe-4068-a4de-c233ac1119dd)

![cancellations by month](https://github.com/user-attachments/assets/af38ec1a-282d-4edf-9350-f3b9b11eaeb6)

![bookings by month](https://github.com/user-attachments/assets/139e0b0a-5922-4498-b810-f89ccc7d1e1a)
---

### Customer Demographics and Behavior:

* **Booking Behavior** Out of the 119,390 bookings, 25,124 belonged to the Transient-Party customer type, 89,613 to the Transient type, 4,076 to the Contract type, and 577 to the Group type. This data shows that the largest customer base is Transient and Transient-Party. Both customer types preferred City Hotels over Resort Hotels, with the Transient type having 17,333 bookings at City Hotels compared to 30,209 at Resort Hotels. Similarly, the Transient-Party type had 17,333 bookings at City Hotels and 7,791 at Resort Hotels.
  
* **Distribution Channels** The Transient and Transient-Party customers primarily booked through Travel Agents or Tour Operators (TA/TO). However, the second most popular distribution channel varied: the Transient type favored direct booking, while the Transient-Party type preferred corporate booking.
  
* **Customers with Children and Babies** Out of 119,390 bookings, only 9,332 included children or babies. The Transient customer type accounted for the majority (8,459), with 4,918 bookings at City Hotels and 3,541 at Resort Hotels.

![bookings by customer type and channel](https://github.com/user-attachments/assets/60faec14-c7ff-4a19-8f66-728862a4e848)

![bookings w_wo children or babies](https://github.com/user-attachments/assets/f87a62f8-5345-472f-8b61-8ca76ade3513)

![bookings w babies or children by customer type](https://github.com/user-attachments/assets/8e0a4db7-b5c0-44da-b809-e51af46b8ce9)
---

### Revenue and Occupancy:

* **Room Type** The room type generating the most revenue was "A," with a total of $14,512,788.87, while the "L" room type brought in the least revenue, at $754.00.

* **Weekday vs Weekend Booking**  72.62% of bookings were for weekday stays, while 27.37% were for weekends

* **Revenue by Hotel Type** The City Hotel generated the most revenue, approximately $25,279,470, compared to $17,444,028 for the Resort Hotel. In both hotel types, the Transient customer type brought the most revenue, accounting for 80.64% of profits at the City Hotel and 79.17% at the Resort Hotel.
  
![room type revenue](https://github.com/user-attachments/assets/7a94fe7a-1cc2-4d0a-a5b1-89d662c0fa86)

![total bookings weekdays vs weekends](https://github.com/user-attachments/assets/35f04a02-0946-41a7-a964-da80d5bbf92c)

![revenue by customer type and hotel type](https://github.com/user-attachments/assets/058b4f35-124e-4662-8b90-79703c88ccf4)



# Recommendations:

Based on the insights and findings above, we would recommend to consider the following: 

* Collaborate with travel agencies and tour operators to create marketing campaigns. Offer booking discounts through other channels to increase bookings.
  
* Introduce a cancellation charge and require a deposit for all bookings.
  
* Offer discounts or create special offers for months with low booking rates, such as November and December.

* Capitalize on the diversity of room types and diversity the stream of revenune since most of it comes from the 'A' type. 
  

# References 

Mostipak, J. (2020). Hotel booking demand. Retrieved from https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
  

  



