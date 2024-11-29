# Hotel Bookings Analysis

# Project Background

This data set pertains to two types of hotels: resort and city hotel and the demands of each type. It includes information about bookings, guests, parking spaces, etc. 

Insights and recommendations are provided on the following key areas:

- **Hotel Operations** 
- **Booking and Cancellation trends** 
- **Customer Demographics and Behavior**
- **Revenue and Occupancy**

The SQL queries used to inspect and clean the data for this analysis can be found here [link].


# Data Structure & Tools

This data set was retrived from Kaggle(See Reference). 

The dataset contains 119,390 entries and 32 columns, providing details about hotel bookings. The columns includes data types such as STRINGS, FLOAT, DATE and INTEGERS.

The tools used in this project were SQL to clean and analysis the data and RStudio for additional analysis and generation the plots. 


# Executive Summary

### Overview of Findings

A variety of trends and patterns were identified and attributes were quantified to analyze the previous key areas listed. The biggest customer type that make the most bookings and the most revenue is the Transiet. This customer type tends to do their bookings via a Travel Agency or a Tour Operators. Additionally, this customer tends to prefer the City Hotel over the Resort Hotel. The months with the hightest number of bookings are August and July but these are also the months with the hightest number of cancellations. 


# Insights Deep Dive

### Hotel Operations:

* **Special Requests** More than half of the bookings didn't order a special requests that being 58.9%. In the other hand, the data showed that 38.69% ordered 1 or 2 special requests. The maxium number of special requests made was 5 consisting of only 0.05% of the total bookings. When taking in consideration the type of hotel and customer, the data shows the the Transient customer as the type making 1 or 2 special requests and mainly on the City Hotel. 19.98 % of transicient customers staying in City Hotels made 1 or 2 special requests while 16.56 % made 1 or 2 requests in the Resort Hotel.
  
* **Parking Space** The data showed 93.79% of the bookings didn't requiere any parkings. The ones that did resquested 1 or more space, belonged to the the Transient customer type and 48.35% that requiered parking did it for the City Hotel while 21.33% requested it for the Resort Hotel.


![operation analysis](https://github.com/user-attachments/assets/dd01c69e-76c2-4587-a333-9f735896f14b)

![parking space](https://github.com/user-attachments/assets/3bce3f7f-d80d-4845-9bb4-3dc584de7265)
---

### Booking and Cancellation trends:

* **Cancellation Percentage** The data showed that in all bookings there is a cancellation percentage of 37.07 % Moreover, an 27.74% of the cancellations came from City Hotels in comparasion of the 9.32% from the Resorts Hotels. Out of all the customer types(Group, Contract, Transient-Part, and Transient, the last one had the biggest cancellation percentage with 30.6 %. 
  
* **Monthly Cancellatoion Percentage** The top 3 months the hightests cancellations rate are August, July and May respectivaly while the months with the least cancellations rate are January, December and November respectively. Similarly, the customer type with the hightest cancellation rate during the hightests months are the Transient type with a 8.76% in August, 8.23% in July and 7.60% in May. In relation to the type of hotels, the City Hotel had the higests cancellation rates for the peak 3 months  with 7.53 % in August, 6.90%in May, and 6.78% in July.
  
* **Busiest Months** Similarly the patterns follows and shows the the months with the most bookings are August, and July respectively.
  
![cancellations by customer type and hotel](https://github.com/user-attachments/assets/3941a4d0-e1fe-4068-a4de-c233ac1119dd)

![cancellations by month](https://github.com/user-attachments/assets/af38ec1a-282d-4edf-9350-f3b9b11eaeb6)

![bookings by month](https://github.com/user-attachments/assets/139e0b0a-5922-4498-b810-f89ccc7d1e1a)
---

### Customer Demographics and Behavior:

* **Booking Behavior**  Out of the 119,390 bookings, 25,124 belong to the Transient-Party customer type, 89613 belong to the Transient type, , 4076 belong to the Contract, and 577 to the Group type. This data shows  that the  biggest customer base belong to the Transient-Party and Transient. Moreover, both of this customer types tend to book in the City Hotels in comparasion to the Resorts Hotels. The data showed that the Transient had a total 17,333 bookings in the City Hotel while it only had 30,209 in the Resort Hotel. Similarly, the Transeint-Party type had a total of 17,333 bookings in the City Hotel and 7,791 in the Resort Hotel.
  
* **Distribution Channels** The data showd that the Transient and Transient-Party primaly favored booking throught Travel Agents or Tour Operators(TA/TO). However, the behavior diffirienciated in the second most popular distrubition channels. While the Transient type showed the direct booking channel was the second most popular in their customer type, the Transient-Party type showed preferenced towards the corporate booking option as their second most popular.
  
* **Customers with Children and Babies** Out of the  119,390, only 9,332 were bookings with children or babies. The group with the most amount of these bookings were the Transient Type with a total of 8,459. Additionally, this group favored the City Hotel with 4,918 bookings while the Resort had a total of 3,541.

  

![bookings by customer type and channel](https://github.com/user-attachments/assets/60faec14-c7ff-4a19-8f66-728862a4e848)

![bookings w_wo children or babies](https://github.com/user-attachments/assets/f87a62f8-5345-472f-8b61-8ca76ade3513)

![bookings w babies or children by customer type](https://github.com/user-attachments/assets/8e0a4db7-b5c0-44da-b809-e51af46b8ce9)
---

### Revenue and Occupancy:

* **Room Type** The room type with the most revenue was the A with a total of $14512788.869999 while the L room type made the less revene bringing only $754.0.

* **Weekday vs Weekend Booking** The data showed that 72.62% of the bookings were made for a stay in the week while 27.37% were made for a stay in the weekend. 

* **Revenue by Hotel Type** The City Hotel made the most revenue bringing approximately $25,279,470 while the Resort Hotel brought approximately $17,444,028. In both hotel types the Transient customer type brought the most revenue consisting 80.64%  of the profits for the City Hotel and consisting 79.17% of the profits for the Resort Hotel.
  
![room type revenue](https://github.com/user-attachments/assets/7a94fe7a-1cc2-4d0a-a5b1-89d662c0fa86)

![total bookings weekdays vs weekends](https://github.com/user-attachments/assets/35f04a02-0946-41a7-a964-da80d5bbf92c)

![revenue by customer type and hotel type](https://github.com/user-attachments/assets/058b4f35-124e-4662-8b90-79703c88ccf4)



# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**

# References 

Mostipak, J. (2020). Hotel booking demand. Retrieved from https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  



