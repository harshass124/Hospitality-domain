# AtliQ Grand Hospitality  

## Overview  
This project involves analyzing and gaining insights from **hotel booking data** through SQL queries and creating **visualizations** to assist AtliQ Grand Hospitality in optimizing their hotel operations, improving customer experience, and scaling their business.  

##### [Live Dashboard](https://app.powerbi.com/groups/me/reports/c0632ab0-a2cd-490a-83d1-b22913466ce2/5acd52a7a57d8c5376eb?experience=power-bi)
##### [LinkedIn Post](https://www.linkedin.com/posts/harshass_hospitalityinsights-datadashboard-businessintelligence-activity-7263097941492408321-TrMz?utm_source=share&utm_medium=member_desktop)
## Objective  
To provide the management team with data-driven insights into hotel performance, customer trends, room utilization, and revenue generation, helping them make informed business decisions.  

## Dataset Description  
The analysis is based on the following datasets:  
1. **`dim_date`**: Date-related data (e.g., dates, months, weeks, and day types).  
2. **`dim_hotels`**: Hotel-related data (e.g., hotel properties, categories, and locations).  
3. **`dim_rooms`**: Room-related data (e.g., room types, room classes).  
4. **`fact_aggregated_bookings`**: Aggregated booking data (e.g., successful bookings, room categories, and capacities).  
5. **`fact_bookings`**: Booking transaction data (e.g., customer bookings, check-ins, check-outs, and revenue).  

### Key Fields in the Dataset  
Refer to the **Dataset Description** section above for detailed explanations of columns.

## SQL Questions Addressed  
### The following business questions were answered using SQL queries:  

1. **Hotel Performance by Revenue**:  
   Identify the hotels with the highest revenue generated in the last quarter, with fields:  
   - `property_name`  
   - `revenue_generated`  
   - `revenue_realized`  

2. **Room Occupancy Rates**:  
   Calculate the occupancy rates for each room category in each hotel, with fields:  
   - `property_name`  
   - `room_category`  
   - `occupancy_rate`  

3. **Booking Cancellation Analysis**:  
   Determine the number of cancellations per hotel and the revenue impact, with fields:  
   - `property_name`  
   - `cancelled_bookings`  
   - `revenue_loss_due_to_cancellations`  

4. **Customer Preferences**:  
   Identify the most popular room type across all hotels, with fields:  
   - `room_category`  
   - `total_bookings`  

5. **Booking Trends by Week**:  
   Analyze the weekly booking trends over a three-month period (May–July), with fields:  
   - `week_no`  
   - `successful_bookings`  

6. **Hotel Category-wise Performance**:  
   Compare the performance of Luxury vs. Business hotels in terms of revenue, with fields:  
   - `hotel_category`  
   - `total_revenue_generated`  

7. **Room Category Growth**:  
   Calculate the growth in bookings for each room category from month to month, with fields:  
   - `room_category`  
   - `month`  
   - `bookings_growth_percentage`  

8. **Check-in and Check-out Trends**:  
   Track the check-in and check-out trends to understand peak periods for hotel stays, with fields:  
   - `check_in_month`  
   - `check_out_month`  
   - `total_bookings`  

9. **Booking Platform Contribution**:  
   Identify the booking platforms that contribute the most to the total number of bookings, with fields:  
   - `booking_platform`  
   - `total_bookings`  
   - `percentage_contribution`  

10. **Revenue per Room Type**:  
    Calculate the total revenue generated by each room type (RT1, RT2, etc.) across all hotels, with fields:  
    - `room_category`  
    - `total_revenue_generated`  

## Tools and Technologies  
- **SQL**: For data extraction, transformation, and analysis.  
- **Power BI**: For visualizing insights and creating dashboards.  
- **Power Query**: For data manipulation and advanced analytics.  

## Acknowledgements  
This project was inspired by the case studies provided by **Codebasics**. Special thanks to **Dhaval Patel** Sir and **Hemanand Vadivel** Sir.  
THANK YOU ♥️
