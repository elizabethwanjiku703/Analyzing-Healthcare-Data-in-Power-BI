# HealthStat Analysis 
### Table of Content
- [Project Overview](https://github.com/elizabethwanjiku703/Analyzing-Healthcare-Data-in-Power-BI/edit/main/README.md#project-overview)
- [Key Features](https://github.com/elizabethwanjiku703/Analyzing-Healthcare-Data-in-Power-BI/edit/main/README.md#key-features)
- [Highlights](https://github.com/elizabethwanjiku703/Analyzing-Healthcare-Data-in-Power-BI/edit/main/README.md#highlights)
- [Insights](https://github.com/elizabethwanjiku703/Analyzing-Healthcare-Data-in-Power-BI/edit/main/README.md#insights)
- [Conclusion](https://github.com/elizabethwanjiku703/Analyzing-Healthcare-Data-in-Power-BI/edit/main/README.md#conclusion)
## Project Overview
- This project involves a comprehensive analysis of hospital discharge data from New York State over one year. As part of an intermediate course on [DataCamp](https://app.datacamp.com/learn/courses/case-study-analyzing-healthcare-data-in-power-bi), I was tasked on HealthStat, a fictional consulting firm, to identify insights related to hospital efficiency, specifically focusing on patients who underwent hip replacement surgery.
- The dataset consists of a single table with 30 columns, where each row corresponds to an individual inpatient stay, detailing the patient's journey from admission to discharge. Importantly, the health information contained within this dataset is anonymized and does not allow for individual identification.

**Check out my interactive Power BI dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiOTRlODZjMzEtNjU2Ni00ODc0LWI3MGMtNDkwNmYyNjM2YjFlIiwidCI6ImJmZmI5NzQ4LTRhNTEtNDRjOC05MjBmLTkzOGFjNDc5NzFlNSJ9) to explore the insights in detail!**

## Key Features
1. **Data Loading:** I imported the data as a CSV file into Power BI, setting the stage for analysis.
2. **Data Cleaning:** I cleaned the data by removing duplicates, fixing errors, and handling missing values to ensure accuracy.
3. **Data Transformation:** I transformed the data to make it more useful for analysis, which included reshaping and organizing it effectively.
4. **DAX (Data Analysis Expressions):** I used DAX to create calculated columns and measures that provide deeper insights into the data.
5. **Visualization:** I created interactive visualizations to present the findings clearly and effectively.

## Highlights
- **LOS Comparison** - Summarize the patient discharges to gain insights into the patient profiles within the dataset. Additionally, explore how the average length of stay differs among various hospitals and how it correlates with the number of practicing surgeons.
- **Cost Comparison** - Identify hospitals that stand out in terms of performance and uncover the key factors that most significantly impact both the length of stay and the cost per patient discharge.
- **Hospital Profile** - This section provides a deep dive into the profile of each hospital, offering a comprehensive view of their performance metrics, and operational efficiencies.

## Insights
|Length of Stay Comparison  |  Cost Comparison  |
|-------------------------  |-------------------|
|![LOS Comparison](https://github.com/elizabethwanjiku703/Analyzing-Healthcare-Data-in-Power-BI/blob/main/LOS%20Comparison.jpg)|![Cost Comparison](https://github.com/elizabethwanjiku703/Analyzing-Healthcare-Data-in-Power-BI/blob/main/Cost%20Comparison.jpg)
|The average length of stay (LOS) for hip replacement surgery is 2.65 days, costing $21,000 per discharge. The Hospital for Special Surgery recorded the highest total discharges while maintaining a lower LOS. In contrast, Staten Island University Hospital-North had the longest LOS despite having only five surgeons on staff.|New York hospitals have the highest cost per discharge in the nation. Within New York City, five hospitals reported an average cost per discharge that exceeded the 90th percentile compared to other facilities in the area. The Key Influencer on discharge cost was impacted by extreme mortality and where the service area was located on NYC. |  

| Hospital Profile|
|-----------------|
|![Hospital Profile](https://github.com/elizabethwanjiku703/Analyzing-Healthcare-Data-in-Power-BI/blob/main/Hospital%20Profile.jpg) |
|Patients with moderate illness had the highest discharge rates compared to those with more severe conditions. Most of these discharged patients were referred to home health services, with osteoarthritis being the primary diagnosis. Additionally, the majority of these patients experienced only minor mortality rates.|

## Conclusion
This analysis identified factors that greatly influence costs and average length of stay (LOS). Patients with severe illnesses and high mortality risks were the most significant contributors to reduced efficiency. We also noticed that hospitals in New York City typically had higher costs and longer LOS. Furthermore, the length of stay was affected by whether patients were transferred to skilled nursing homes. These findings will be beneficial for HealthStat in shaping improvement strategies for their clients to boost the hospital's efficiency and enhance the patient experience.
