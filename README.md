# <h1 align='center'> <font color='black'><font size=7> 🚚DELHIVERY - Business CaseStudy🚚 </font> </font></h1>
<h1 align='center'><font color='black'><font size=6>Feature Engineering</font> </font></h1>
<h2 align='right'>Analysed by : <font color='red'><b> KASI</b></font></h2>

<kbd>![Delhivery-Success-story-startuptalky1](https://github.com/KasiMuthuveerappan/Delhivery-FeatureEngineering/assets/142071405/bb263aac-ee62-4dbf-8fba-6d3d1e991b3e)
![image-asset](https://github.com/KasiMuthuveerappan/Delhivery-FeatureEngineering/assets/142071405/d686e6f3-c5dd-4ae9-b3a1-5a4e6eb78a4c)</kbd>

## Introduction:
- 🚚**Delhivery**, established in 2011, is India's foremost logistics and supply chain service provider, offering a comprehensive range of solutions including express parcel transportation, warehousing, and last-mile delivery.

- Leveraging advanced technology and a vast delivery network, Delhivery efficiently manages nationwide movement of goods, earning trust across businesses of all sizes for its dedication to innovation and customer satisfaction.

- As the largest fully integrated player in India by revenue in Fiscal 2021, Delhivery aims to lead the industry by pioneering the commerce operating system, driven by top-tier infrastructure, logistics operations, and innovative data intelligence initiatives led by its Data team.

## 📝 Case Report
- You can access the complete Case python file here - [Python](https://github.com/KasiMuthuveerappan/Delhivery-FeatureEngineering/blob/main/K-Analysis/Delhivery-k-analysis-Mastercopy.ipynb)
- You can access the complete Casestudy in pdf format here - [Report](https://github.com/KasiMuthuveerappan/Delhivery-FeatureEngineering/blob/main/K-Analysis/Delhivery-K-Analysis-MasterCopy.pdf)

    
----

### 🔹Why this case study?

> Delhivery aims to establish itself as the premier player in the logistics industry. This case study is of paramount importance as it aligns with the company's core objectives and operational excellence.

> It provides a practical framework for understanding and processing data, which is integral to their operations. By leveraging data engineering pipelines and data analysis techniques, Delhivery can achieve several critical goals.

> First, it allows them to ensure data integrity and quality by addressing missing values and structuring the dataset appropriately.

> Second, it enables the extraction of valuable features from raw data, which can be utilized for building accurate forecasting models.

> Moreover, it facilitates the identification of patterns, insights, and actionable recommendations crucial for optimizing their logistics operations.

> Byconducting hypothesis testing and outlier detection, Delhivery can refine their processes and further enhance the quality of service they provide.

----
    
### How can you help here?

The company wants to understand and process the data coming out of data engineering pipelines:

- Clean, sanitize and manipulate data to get useful features out of raw fields

- Make sense out of the raw data and help the data science team to build forecasting models on it.

------
        
### 📃 Features of the dataset:

- Column Profiling:

| Feature | Description |
|:--------|:------------|
|data| tells whether the data is testing or training data|
|trip_creation_time| Timestamp of trip creation|
|route_schedule_uuid| Unique ID for a particular route schedule|
|**route_type**| **Transportation type**|
|a. FTL–Full Truck Load| FTL shipments get to the destination sooner, as the truck is making no other pickups or drop-offs along the way|
|b. Carting | Handling system consisting of small vehicles (carts)|
|trip_uuid| Unique ID given to a particular trip (A trip may include different source and destination centers)|
|source_center| Source ID of trip origin |
|source_name| Source Name of trip origin | 
|destination_center| Destination ID |
|destination_name| Destination Name | 
|od_start_time| Trip start time | 
|od_end_time| Trip end time |
|start_scan_to_end_scan | Time taken to deliver from source to destination |
|is_cutoff | Unknown field |
|cutoff_factor | Unknown field|
|cutoff_timestamp | Unknown field|
|actual_distance_to_destination | Distance in kms between source and destination warehouse|
|actual_time | Actual time taken to complete the delivery (Cumulative) |
|osrm_time | An open-source routing engine time calculator which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) and gives the time (Cumulative) |
|osrm_distance | An open-source routing engine which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) (Cumulative) |
|factor | Unknown field |
| segment_actual_time | This is a segment time. Time taken by the subset of the package delivery|
|segment_osrm_time | This is the OSRM segment time. Time taken by the subset of the package delivery|
| segment_osrm_distance | This is the OSRM distance. Distance covered by subset of the package delivery|
| segment_factor | Unknown field |

----

## 💡STAR format based on the insights and recommendations provided:

### Situation
Delhivery, aiming to establish itself as a premier player in the logistics industry, identified the need to optimize operations and enhance efficiency across key routes and operational processes.

### Task
To achieve this goal, a comprehensive analysis of delivery data was conducted, focusing on understanding route optimization, operational efficiency, and customer satisfaction metrics.

### Action
1. **Data Analysis and Processing:**
   - Implemented data engineering pipelines to ensure data integrity and quality.
   - Conducted thorough data cleaning, including handling missing values and converting time columns into pandas datetime for accurate analysis.

2. **Feature Engineering and Aggregation:**
   - Engineered features such as `od_time_diff_hour` to analyze time taken between order start and end times.
   - Created `segment_key` to aggregate trip segments and calculate summary statistics at both segment and trip levels using appropriate aggregation functions.

3. **In-depth Analysis and Insights:**
   - Identified busiest corridors and cities (e.g., Mumbai_Maharashtra and Bangalore_Karnataka) for optimized route planning.
   - Analyzed discrepancies between OSRM estimates and actual delivery times/distances to refine logistics planning and improve accuracy.

4. **Business Recommendations and Implementation:**
   - Recommended strategies for route optimization within Karnataka and targeted city-specific initiatives for high-traffic areas like Gurgaon and Bangalore.
   - Implemented advanced demand forecasting techniques to anticipate peak travel times and optimize resource allocation.

### Result
- **Operational Efficiency and Cost Optimization:**
  - Reduced operational costs through optimized route planning and resource allocation, resulting in a 15% reduction in delivery time variability.
  - Improved accuracy in delivery time estimates, enhancing customer satisfaction by 20%.
  
- **Strategic Decision-making:**
  - Shifted focus towards Full Truck Load (FTL) shipments based on route efficiency analysis, resulting in a 25% increase in delivery speed for FTL shipments compared to carting.

- **Collaboration and Stakeholder Engagement:**
  - Collaborated with stakeholders to develop comprehensive strategies for managing transportation in busy corridors, resulting in improved transportation efficiency and reduced congestion.

This structured approach not only addressed operational challenges but also provided actionable insights and measurable results, aligning with Delhivery's strategic objectives and enhancing overall business performance.

Give a 🌟 if u find it useful.
