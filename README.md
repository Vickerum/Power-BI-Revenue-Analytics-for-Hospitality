# Power-BI-Revenue-Analytics-for-Hospitality
Developed and implemented a revenue insights project using Power BI for the hospitality industry

This project aims to provide revenue insights in the hospitality domain using Power BI. It analyzes key metrics such as RevPar, Average Daily Rate, and Daily Sellable Room Nights to uncover revenue trends and opportunities. 

The project also covers No Show and Cancellation metrics (BRN, URN) for better understanding. Additionally, the distinction between weekdays and weekends in the hotel industry is explored.

# Steps
1] Data Loading and Transformation: The project involves loading the entire data folder and transforming the data using Power Query.

2] Date Modifications: The project adjusts the weekend definition in the tables from Saturday-Sunday to Friday-Saturday.
3] DAX Calculations: Calculated columns and measures using DAX are created to generate new columns like WeekNumber and Weekend.
4] Revenue measure is calculated using the formula: Revenue = SUM(fact_bookings[revenue_realized])

Other measures include total bookings, total capacity, and successful bookings.

The purpose of this project is to provide valuable insights into revenue performance within the hospitality industry, leveraging Power BI's analytical capabilities.
