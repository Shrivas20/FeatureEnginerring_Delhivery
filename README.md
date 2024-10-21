# Delhivery Business Case Study Feature Engineering

## Key Insights

### Data Summary
- **Dataset Period:** The dataset covers the period from **2018-09-12 00:00:16** to **2018-10-08 03:00:24**. The majority of the data is for testing rather than training.

### Route Types
- The most common route type is **Carting**, followed by **FTL (Full Truck Load)**.

### Origin and Destination States
- The maximum number of orders originate from the states of **Maharashtra**, **Karnataka**, **Haryana**, **Tamil Nadu**, and **Telangana**.
- The maximum number of orders are delivered to **Maharashtra**, **Karnataka**, **Haryana**, **Tamil Nadu**, and **Uttar Pradesh**.

### Origin and Destination Cities
- The maximum number of trips originate from cities like **Mumbai**, **Gurgaon**, **Delhi**, **Bengaluru**, and **Bhiwandi**.
- The maximum number of trips end in cities like **Mumbai**, **Bengaluru**, **Gurgaon**, **Delhi**, and **Chennai**.

### Statistical Analysis
- The **actual_time** and **osrm_time** (model-predicted time) are statistically different, indicating the need to improve the OSRM (Open Source Routing Machine) trip planning system.
- The **osrm_distance** (predicted distance) and **actual_distance** covered by delivery personnel are also statistically different, suggesting the need to address discrepancies in the routing system.
- The **segment_actual_time** and **segment_osrm_time** are not statistically different, implying a focus on improving overall trip planning rather than just segment-level predictions.

## Recommendations

1. **Improving OSRM Accuracy:** 
   - Address discrepancies in the OSRM trip planning system to provide more accurate delivery predictions and enhance transporter efficiency. Reconfigure the routing engine to deliver optimal results while factoring in real-world constraints and deviations.

2. **Minimizing Time Discrepancies:** 
   - Reduce the difference between the **osrm_time** (model-predicted time) and the **actual_time** taken for deliveries to ensure reliable delivery time predictions, thereby enhancing the customer experience.

3. **Addressing Distance Mismatches:** 
   - Resolve inconsistencies between the **osrm_distance** (predicted distance) and the **actual_distance** covered by delivery personnel. This could involve addressing factors such as drivers not following predefined routes or the OSRM failing to account for real-time conditions like traffic, road closures, or terrain issues.

4. **Focusing on Key States:** 
   - Enhance delivery corridors in key states like **Maharashtra**, **Karnataka**, **Haryana**, **Tamil Nadu**, and **Uttar Pradesh** to streamline operations and improve logistics in high-demand areas.

5. **Incorporating Traffic and Terrain Considerations:** 
   - Identify significant traffic congestion or challenging terrain conditions that impact delivery times, especially during peak periods. Adjust routing strategies to better manage demand during high-traffic times, thereby improving overall performance.

## Conclusion

By addressing these key areas, Delhivery can enhance the accuracy and efficiency of its delivery operations, leading to a better customer experience and increased business growth.
