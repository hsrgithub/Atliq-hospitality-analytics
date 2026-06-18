AtliQ Hospitality Analytics — Power BI Dashboard

 1.Project Overview

   AtliQ Grands is a fictional five-star hotel chain operating across multiple cities in India. Due to increasing competition and poor management decisions, the company has been losing market share and revenue. 
   This project analyzes their hospitality data to uncover key business insights and help the revenue management team make data-driven decisions.
   This project was built as part of the Codebasics Resume Project Challenge.

2. Objective

   To build an end-to-end hospitality analytics dashboard using Power BI that helps stakeholders:

    Monitor revenue performance across properties and cities
    Track key hospitality KPIs week over week
    Identify underperforming hotels and booking platforms
    Support strategic decisions around pricing and occupancy

3. Key Metrics (KPIs) Tracked

   Revenue : Total revenue realized from bookings
   
   RevPAR  : Revenue Per Available Room
   
   ADR     : Average Daily Rate
   
   DSRN    : Daily Sellable Room Nights
   
   Occupancy %: Percentage of rooms occupied
   
   Realization Rate: Percentage of successful checkouts vs bookings
   
   WoW % Change: Week-over-Week performance change for all KPIs

5. Tools Used

   Microsoft Excel — Data exploration and initial cleaning
   Power BI — Data modeling, DAX measures, and dashboard development

5. Data Model

   Built using a star schema with the following tables

   dim_hotels: Hotel properties and categories
   dim_rooms : Room types
   dim_date : Date table for time intelligence
   fact_bookings: Booking-level transactional data
   fact_aggregated_bookings: Aggregated room availability and bookings

6. Key Insights

   Mumbai generated the highest revenue among all cities.
   
   Atliq exotica was the top performing property overall.
   
   Weekday vs weekend analysis revealed the pricing optimization oppurtunities.
   
   Direct offline bookings had the highest realisation rate compared to other platforms.
   
   Several properties showed consistently low occupacy% indicating demand issues
   
   <img width="1111" height="686" alt="final dashboard" src="https://github.com/user-attachments/assets/8e01f1a3-11c1-4a0f-b447-11982a3bfe9e" />
