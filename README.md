# Power BI Revenue Analytics for Hospitality
# Overview
This project provides in-depth insights into hotel sales data using Power BI. It covers key metrics such as RevPar (Revenue Per Available Room), Realization %, Occupancy %, Average Daily Rate (ADR), and more to evaluate the hotel's performance and identify trends.

# Key Metrics
RevPar (Revenue Per Available Room): The average revenue generated per available room. It assesses overall revenue performance.
Realization %: Measures the hotel's success in turning available rooms into bookings.
Occupancy %: Represents the percentage of occupied rooms during a specific period.
Average Daily Rate (ADR): The average rate at which rooms are sold.
Daily Sellable Room Nights: Calculated as the number of available rooms minus out-of-order rooms.
Cancellation Rate: The percentage of canceled bookings out of total bookings.
Approach
# Data Filtering
Key metrics can be filtered by cities, room class, and months to focus on specific data subsets.
The super key metrics, RevPar, and Realization % are calculated based on occupancy and ADR.
# Insights
RevPar fluctuates while ADR remains stable, suggesting an opportunity for dynamic pricing.
Correlation observed between ratings and occupancy, with lower ratings associated with higher cancellation rates.
Focus on underperforming hotels, such as the Bangalore hotel, and analyze factors like location, type, ratings, and amenities for pricing strategies.
Consider reading customer feedback for insights into service improvements.
Evaluate pricing strategies, especially on peak days.
Explore ways to encourage bookings through the hotel's own website to reduce commission costs.
# Steps Taken
Loaded and transformed data using Power Query.
Adjusted dates to consider weekends as Friday-Saturday.
Created DAX calculated columns for week numbers and weekends.
Created measures for revenue, total bookings, total capacity, and successful bookings.
# Visualizations
Visualizations include charts for ADR and realization across different platforms.
Insights gained from visualizations inform pricing strategies, occupancy rates, and customer feedback analysis.
# Conclusion
This project highlights the importance of analyzing key metrics in the hotel industry, including RevPar, Realization %, and ADR. By understanding these metrics, businesses can make data-driven decisions to improve revenue and customer satisfaction.
