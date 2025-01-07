# AtliQ Grands Hospitality Analysis - Power BI Dashboard
### Introduction :
AtliQ Grands, a prominent chain of five-star hotels in India, has established itself as a leader in the hospitality industry over the last 20 years. Operating in major cities like Delhi, Mumbai, Bangalore, and Hyderabad, AtliQ Grands is renowned for its luxurious accommodations and exceptional service. This project aims to integrate Business and Data Intelligence into AtliQ Grands' operations to help regain market share and revenue lost to competitors and poor management decisions.

### Problem Statement :
Despite its strong market presence, AtliQ Grands has been experiencing a decline in both market share and revenue in the competitive luxury and business hotel segments. This project involves utilizing historical data analysis to derive actionable insights for strategic decision-making and operational improvements.

### Tools and Skills Used
- **Power BI:** Used for data visualization and dashboard creation.  
- **Power Query:** Employed for data importing and transformation.  
- **DAX:** Utilized for creating complex measures and calculations within the data model.  
- **Data Modeling:** Involved structuring data into a coherent framework for analysis.  
- **Conditional Formatting:** Applied to enhance visual appeal and readability of data points.
--- 

### Dataset Description

The project utilizes five datasets and a metadata file:

1. **`dim_date.csv`**:
   - Contains date dimensions like week numbers, day types (weekday/weekend), and date formats.
2. **`dim_hotels.csv`**:
   - Includes property details such as name, category (Luxury/Business), and city.
3. **`dim_rooms.csv`**:
   - Describes room types and classifications (Standard, Elite, Premium, Presidential).
4. **`fact_aggregated_bookings.csv`**:
   - Aggregates booking data, including room capacities and successful bookings.
5. **`fact_bookings.csv`**:
   - Detailed transactional data, including revenue, booking status, and ratings.
6. **`meta_data_hospitality.txt`**:
   - Documents column descriptions for all datasets.

---

## Data Model Overview
This section outlines the structure of the data model that supports the dashboard, showcasing the relationships between tables and highlighting the key measures used for analysis.  
![Screenshot 2025-01-07 153849](https://github.com/user-attachments/assets/046acd62-4112-4812-be37-31be0aafa0db)


## Dashboard Overview
This Power BI dashboard is designed to provide comprehensive insights into the performance and booking details of AtliQ Grands' properties. It consists of four main pages:

### Home Page!

A general overview and welcome page that guides users on how to navigate through the dashboard.  

![Screenshot 2025-01-06 152344](https://github.com/user-attachments/assets/be9973ac-da65-4ccf-93fd-13ac4ba4db75)

### Performance View
-  **Description:** This page provides a snapshot of the hotel's financial and operational performance, including key metrics such as revenue, RevPAR (Revenue Per Available Room), and occupancy rates.

-  **Features:** Filter options by city, room class, and month.Visualization of revenue trends and performance metrics  

![Screenshot 2025-01-06 152443](https://github.com/user-attachments/assets/e2b1f5bc-4bf5-4970-8bf4-1365f5572b18)  

### Bookings View
-  **Description:** Focuses on detailed booking statistics across different properties, highlighting successful stays, cancellations, and no-show rates.
-  **Features:** Analysis by booking channels and types of bookings.Comparison of weekday vs. weekend performance.

![Screenshot 2025-01-06 152506](https://github.com/user-attachments/assets/aea63864-6a5a-4561-aeca-52fd65620846)


### Info Page  

Provides additional information about the data sources, definitions of metrics used, and other relevant details that support the understanding of the dashboard.  
![Screenshot 2025-01-06 152530](https://github.com/user-attachments/assets/5fa5fcad-401e-469e-939e-1a86d548463a)  

## Insights
-  **Revenue Generation:** Mumbai leads with the highest revenue generation, followed by Bangalore and Hyderabad.  
-  **Booking Platforms:** 'Make Your Trip' emerges as the top booking platform.  
-  **Hotel Performance:** Atliq Exotica and Atliq Palace are leading in terms of capacity utilization.  
-  **Seasonal Trends:** May sees the highest booking rates.  
-  **Room Preferences:** Elite rooms are most favored but also have the highest cancellation rates.  
## Recommendations
-  **Revenue Optimization:** Enhance service offerings in Mumbai to leverage its strong revenue performance. Implement targeted marketing and service improvements in underperforming regions like Hyderabad. 
-  **Customer Experience:** Analyze customer feedback in Bangalore to address service gaps and elevate the overall guest experience.
-  **Strategic Promotions:** Launch special promotions and packages during peak seasons to maximize bookings.  
-  **Room Class Management:** Increase the availability of Elite rooms and revise booking policies to reduce cancellations.  
## Project Insights
-  **Data Insights:** Detailed analysis revealed key trends such as the highest revenue months and the performance metrics of different hotels within the chain.  
-  **Learning Outcomes:** The project facilitated learning in building new visuals like the Calendar visual and implementing bookmarks for dynamic page navigation within the dashboard.  
## Conclusion
This Power BI project not only underscores the critical areas needing attention but also highlights opportunities for AtliQ Grands to enhance their market position. By integrating refined data analysis techniques and business intelligence, AtliQ Grands can strategically navigate the competitive landscape of the luxury hotel industry.


