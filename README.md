# Investigate Business Hotel Using Data Visualization

## Overview
Investigating business performance is crucial for any company. In this project, we delve into the hospitality industry, aiming to understand customer behavior in hotel bookings and its correlation with cancellation rates. We present our insights through data visualization for better comprehension and persuasive presentation.

- Dataset provides information about hotel reservations, including guest details, booking times, and preferences.
- The dataset consists of 119,390 entries with 29 features.
- There are 20 numeric features and 9 categorical features.
- Data types in the dataset include object, float64, and int64.

## Data Preprocessing
For detailed preprocessing steps, refer to the accompanying Jupyter notebook.

1. **Handling Missing Values**
   - Out of 29 features, 4 features have missing values: company, agent, city, and children.
   - Company feature will be dropped due to 94% missing values.
   - Agent has 14% missing values, while city and children have minimal missing values.
   - City will be filled with "undefined", while agent and children will be filled with 0.

2. **Handling Inconsistent Values**
   - Converted data type of the children feature from float to integer as it represents the number of children in the accommodation room.
   - Merged "undefined" category in the meal feature with "No Meal".
   - Removed 180 transactions with 0 guests.

## Monthly Hotel Booking Analysis Based on Hotel Type
- Hotel bookings increase in May, September, and October coinciding with Eid holidays, the end of the academic year, and New Year celebrations.
- Accommodation demand rises as people utilize holidays for vacations, family gatherings, or attending special events.
- The hospitality industry needs to prepare by providing additional services and ensuring sufficient room availability during these holidays.

## Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rates
- Longer stays tend to have higher cancellation rates for both City Hotels and Resort Hotels.
- Resort Hotels have a cancellation rate of only around 28% for stays longer than 4 weeks, possibly due to longer-term bookings having higher commitment and strict cancellation policies from the hotel.
- Specialized booking management strategies and promotions can help City Hotels improve customer retention, while Resort Hotels can consider marketing emphasizing unique vacation experiences to minimize cancellation rates.

## Impact Analysis of Lead Time on Hotel Bookings Cancellation Rate
- Lower cancellation rates in Resort Hotels across all booking lead time categories compared to City Hotels are due to customers planning trips well in advance and stricter cancellation policies.
- Cancellation rates tend to increase with increasing lead time, especially in City Hotels, reaching a peak in the "12 months" category with an 82% cancellation rate, possibly due to uncertainty in long-term planning and potential changes in customer plans.
- To reduce high cancellation rates, companies need to implement more flexible cancellation policies and improve proactive communication with customers to maintain reservations.

**For a comprehensive understanding of the project, refer to the Jupyter notebook included.**
