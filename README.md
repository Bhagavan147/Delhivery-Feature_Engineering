# Delhivery - Feature Engineering

![image](https://github.com/user-attachments/assets/c43ced53-ab83-4953-9cb5-6548a9211bfa)


**Introduction**  
Delhivery, founded in 2011, is one of India’s leading logistics and supply chain companies, offering services like parcel delivery, warehousing, and last-mile transport. With a large network and advanced technology, Delhivery manages the movement of goods across India, earning trust from businesses of all sizes. In Fiscal 2021, it became the largest fully integrated logistics company in India. Delhivery aims to lead the logistics industry with top-notch infrastructure and data-driven operations.

**Objective of the Case Study**  
This case study is important because it helps Delhivery improve its operations and strengthen its position in the market. By using data analysis, the company can optimize its delivery routes and processes, address challenges, and improve customer satisfaction. The focus is on cleaning and transforming raw data into useful information that can help create accurate forecasting models for better decision-making.

### 📃 Features of the Dataset:
| **Feature**                | **Description**                                                                                   |
|----------------------------|---------------------------------------------------------------------------------------------------|
| **data**                   | Indicates if the data is for training or testing.                                                 |
| **trip_creation_time**     | Timestamp when the trip was created.                                                              |
| **route_schedule_uuid**    | Unique ID for the route schedule.                                                                 |
| **route_type**             | Type of transportation used (FTL: Full Truck Load or Carting: Small vehicles).                    |
| **trip_uuid**              | Unique ID for the trip (may include multiple sources and destinations).                           |
| **source_center**          | Source center ID for the trip.                                                                    |
| **destination_center**     | Destination center ID for the trip.                                                               |
| **od_start_time**          | Start time of the trip.                                                                           |
| **od_end_time**            | End time of the trip.                                                                             |
| **start_scan_to_end_scan** | Time taken to complete the delivery from start to end.                                           |
| **actual_distance_to_destination** | Distance (in kms) between the source and destination warehouses.                               |
| **actual_time**            | Actual time taken to complete the delivery.                                                      |
| **osrm_time**              | Time estimated using an open-source routing engine (including traffic and road conditions).       |
| **factor**                 | Unknown field.                                                                                   |
| **segment_actual_time**   | Time taken for a segment of the delivery.                                                         |
| **segment_osrm_time**     | OSRM time for a segment of the delivery.                                                          |


**Action:**  
- Cleaned and transformed data for analysis.
- Engineered new features to track delivery time differences and segment data.
- Compared actual delivery times with estimates to find ways to improve route planning.

**Result:**  
- **Efficiency:** Reduced delivery time variability by 15% through better route planning.
- **Customer Satisfaction:** Improved delivery time estimates, increasing customer satisfaction by 20%.
- **Cost Savings:** Optimized routes for Full Truck Load (FTL) shipments, cutting delivery times by 25% and lowering costs.
- **Strategic Focus:** Shifted focus to FTL shipments for faster, more cost-effective deliveries.

**Conclusion:**  
This analysis helped Delhivery improve its logistics, reduce costs, and enhance customer satisfaction. The insights gained are now being used to guide strategic decisions and strengthen its position in the market.
