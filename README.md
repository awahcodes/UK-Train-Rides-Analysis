# UK Train Rides Analysis

## Project Review

Mock train ticket data for National Rail in the UK, from Jan to Apr 2024, including details on the type of ticket, the date & time for each journey, the departure & arrival stations, the ticket price, and more.
Data was sourced from Maven Analytics dataset page. The dataset was extracted into power query for preparation and cleaning. Columns were added for Revenue, Route, Journey duration and Journey type. This was then loaded for analysis and visualisations were created in Power BI


## Data Sources

Data were sourced from Maven Analytics which was csv file. ETL was done in Power BI.

- File type: csv
- Number of rows: Over 31,500
- Number of fields: 18
- [Link to Data Source from Maven Analytics](https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=train)

## Tools

- Power Query: For data transformation and cleaning
- Power BI: For visualisation and generating insights

  
## Insights from each dashboard is as below:

### 1. Overview Dashboard:

  <img src ="https://github.com/user-attachments/assets/96b5ba09-b6b7-4398-955f-885cdddc52dd" alt ="Overview image" width= "600" height = "400">


   a. **High Overall Performance:**
   
   - A total of 31.65K trips were completed, generating a substantial £741.92K in revenue.
   - Average revenue per trip is  £23.44.
   - The data spans across 65 routes, showing an extensive coverage of train services.

   b. **Fluctuating Trips Over Time:**

   - The line chart indicates variability in the number of trips completed over time.
   - A significant dip occurred on every first day of the month, potentially signaling operational disruptions (e.g., service downtime or seasonal factors).

   c. **Consistent Route Utilization:**

   - The total routes covered (65) suggest a stable service offering with no major additions or reductions during the period.

  
### 2. Customer Buying Behaviour

   <img src="https://github.com/user-attachments/assets/0881e564-4b70-4c74-9bdb-d0c81ec25210" alt="Customer Buying Behaiour" width="600" height= "400">

   
   - **Purchase Type:** 59% of purchases are made at stations, while 41% are online. This suggests a significant number of customers prefer in-person transactions.

   - **Payment Methods:** 34% of customers use contactless payments, showing a strong preference for modern and convenient payment methods.

   - **Ticket Type:** Advance ticket purchases make up 55%, with anytime and off-peak at 28% and 17%, respectively. Customers value planning ahead to secure cheaper fares.

   - **Ticket Class:** 90% of tickets are for standard class, showing a clear preference for affordability over premium services.

   - **Refund Requests:** Only 4% of customers request refunds, indicating relatively high customer satisfaction with bookings.

   - **Railcard Type:** 15% of customers use Adult Railcards, followed by Disabled (10%), None (66%), and Senior (9%). This implies 34% of tickets sold were discounted.

   - **Journey Type:** There’s a near-even split between long-distance (54%) and short-distance (46%) travel, suggesting diverse use cases.
    

### 3. Service Delivery Level

   <img src="https://github.com/user-attachments/assets/9437224d-e11c-4ce5-a560-462b56f76f67" alt="Service Level Delivery" width="600" height="400">

   - Reliability Metrics: 87% of trips are on time, while 7% are delayed and 6% are cancelled. This reflects generally good service but indicates room for improvement.

   - Reasons for Delays: Weather (24%), signal failures (23%), and technical issues (17%) are the top contributors to delays. Staffing issues, including shortages, are also notable.

   - Travel Routes: There’s a wide distribution of routes (65), with many key inter-city routes like "London Euston to Manchester Piccadilly" and "Liverpool Lime Street to Birmingham New Street."


### 4. Trips and Route Metrics: 

  <img src="https://github.com/user-attachments/assets/c1fefd21-caab-44c9-ac7d-97c608c324c6" alt= "Trips & Route Metrics" width= "600" height= "400">
  <img src="https://github.com/user-attachments/assets/84843881-0a88-4ffb-874d-c131c5430fd3" alt= "Trips & Route Metrics" width= "600" height= "400">

   - London Kings Cross to York had the highest trip counts. However, Manchester Piccadilly to London Paddindton had the highest Average Revenue per trip.
     
   - Birmingham New Street to Wolverhampton had the least Average Revenue per trip. Depending on resources, we may look into rescheduling to meet demands for routes with higher profitability.


## Recommendations:

   - **Investigate March 2024 Dip:**

       - Identify the reasons for the drop in trips each first day of the month (e.g., maintenance issues, customer behavior, external events).

       - Implement contingency plans to minimize disruptions in similar situations in the future.

   - **Customer Behavior Analysis:**

       - Dig deeper into customer buying behavior and preferences across routes and time periods.

       - Use targeted marketing campaigns during low-demand periods to improve ridership.

   - **Operational Improvements:**

       - Analyze the performance and profitability of the 65 routes to identify underperforming ones.

       - Consider re-allocating resources from less profitable routes to high-demand ones.

   - **Revenue Optimization:**

       - Examine pricing strategies or promotions that could help boost revenue further.

       - Evaluate if specific routes contribute disproportionately to revenue and prioritize them in service improvements.

   - **Performance Monitoring:**

      - Include additional KPIs such as  customer satisfaction levels for a more granular understanding of business performance.

   - **Encourage Online Purchases:**

      - Promote online ticketing via discounts or loyalty programs to shift more transactions online, reducing station congestion and improving operational efficiency.

   - **Expand Contactless Payment Options:**
      
      - Continue optimizing contactless payment systems to accommodate growing demand and reduce transaction time at stations.

   - **Boost Advance Ticket Sales:**

      - Offer incentives for advance purchases, such as further discounts or bundled offers, to enhance revenue predictability and customer satisfaction.

   - **Improve Premium Ticket Sales:**

      - Develop targeted campaigns to promote first-class tickets, such as showcasing premium services or offering temporary upgrades.

   - **Optimize Service Reliability:**

      - Focus on mitigating weather-related disruptions by investing in weather-proof infrastructure and robust operational planning.

      - Collaborate with technical teams to address frequent signal failures.

   - **Enhance Customer Journey Support:**

      - Introduce features like real-time journey updates via apps or SMS to keep customers informed, especially during disruptions.

   - **Market to Railcard Holders:**

     - Depending on business goals on CSR, focus campaigns on railcard users, particularly Adult and Disabled categories, as they represent the minority of the customer base. This could also mean there are accessibility concerns and they chose to ride on competition

   - **Focus on Core Routes:**

     - Prioritize maintaining service reliability and marketing efforts on popular routes like Manchester Piccadilly to London Paddington to maximize customer retention.


