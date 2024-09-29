
# Project ReadMe: Healthcare Analysis Dashboard

## Overview

This project presents a **Healthcare Analysis Dashboard** that visualizes patient data related to various medical specialties, waiting times, and case types (Outpatient, Inpatient, Day Case). The data spans a range of categories such as age profiles, specialties, and time bands to enable a deep dive into trends, performance, and backlogs in patient care over time.

## Dashboard Components

The project consists of three key visual dashboards, each serving a specific purpose in analyzing the healthcare data:

### 1. **Detailed View Dashboard **
   - **Purpose**: Allows for a granular breakdown of medical case types by specialty, inpatient and outpatient volume, time bands, and age profiles. This view provides a holistic look at case details over a customizable time range.
   - **Key Features**:
     - **Filters**: Time range, case type, specialty, time bands, and age profiles to allow precise drilling down into specific data segments.
     - **Data breakdown**: Total numbers of day cases, inpatients, and outpatients by medical specialties like Clinical Genetics, General Surgery, Anaesthetics, etc.
     - **Age profiles**: Allows breakdown into age groups such as 0-15 months, 3-6 months, etc.
   - **Interactivity**: Users can adjust slicers (filters) to explore specific data sets of interest, which dynamically updates the data view.
   - ![Details_dashboard](https://github.com/user-attachments/assets/5995247b-a6cf-4dd7-ad33-910f36f584e0)


### 2. **Drill Down Dashboard**
   - **Purpose**: Visualizes the sum of totals across different medical areas. The drill-down view helps users see which medical domains (e.g., bones, ENT, skin) contribute the most to overall patient cases.
   - **Key Features**:
     - **Bar Chart**: Summarizes medical domains by total case numbers, providing a quick insight into areas with the highest patient volumes.
     - **Top Medical Areas**:
       - **Bones**: 3.9M cases
       - **General**: 3.5M cases
       - **ENT (Ear, Nose, Throat)**: 3.2M cases
       - Other areas include eyes, skin, heart, urine, and respiratory issues.
   - **Visual Representation**: Utilizes a horizontal bar chart for easy comparison across various domains, with a total case count of **25M**.
   - ![Drilldown](https://github.com/user-attachments/assets/3dcf8a0c-d944-49a5-bee5-4afc873cfea5)


### 3. **Summary Dashboard **
   - **Purpose**: Provides a summarized view of the overall trends in healthcare data, including current and past waiting lists, case type distribution, and monthly trends.
   - **Key Features**:
     - **KPIs**: Key metrics include:
       - **Current Month Waiting List**: 709K
       - **Previous Year Same Month**: 640K
     - **Case Type Distribution**: A breakdown of outpatient, day case, and inpatient cases represented in a pie chart.
     - **Age Profile Distribution**: Shows age profiles of patients (0-15 years, 16-64 years, and 65+ years).
     - **Monthly Trend Analysis**:
       - Line chart showing the trends of outpatient, inpatient, and day case types over time, illustrating patient volumes and case trends.
       - Comparative analysis over a range of months from 2018 to 2021.
     - **Specialty-Specific Information**: Average/median time for specific specialties such as Pediatric Dermatology, ENT, and Orthopedic cases.
   - **Interactive Elements**: Slicers to adjust case types, specialties, and date ranges for personalized insights.
   - ![Main_dashboard](https://github.com/user-attachments/assets/87c474f9-15a5-416e-802d-e742be57d424)


## Data Overview

The dashboards collectively analyze patient data across multiple medical fields, providing insights on:
- **Patient counts by medical specialties**: Visualized by total numbers of cases.
- **Time distribution**: Allows analysis of patient wait times, categorized into various months' time bands (0-3 months, 3-6 months, etc.).
- **Case types**: Split into Outpatient, Day Case, and Inpatient, with key data points on their respective trends and volumes.
- **Age profiles**: Enables analysis by age groups to understand how patient demographics impact case trends.

## Insights & Use Cases

- **Performance Monitoring**: Users can monitor how patient case volumes have changed over time, particularly in high-priority areas like Bones, ENT, and General Surgery.
- **Trend Analysis**: The dashboard tracks month-on-month trends in outpatient and inpatient care to help administrators understand capacity and performance fluctuations.
- **Waiting List Insights**: The Summary Dashboard provides a clear snapshot of the current patient backlog and how it compares to previous months, aiding resource allocation.
- **Specialty Prioritization**: By understanding which specialties see the highest volumes, healthcare providers can prioritize areas with the most demand and longest wait times.
  
## Technologies & Tools

- **Data Visualization Tool**: Power BI for dashboard creation and interaction.
- **Data Source**: Medical case data covering a wide range of specialties and age profiles.

## Usage Instructions

1. **Filtering**: Use the left-hand filters (slicers) in each dashboard to customize the view based on case type, specialty, time bands, and age profile.
2. **Drill-Down Capabilities**: In the "Drill Down Dashboard," hover over specific medical fields to view the case volume breakdown.
3. **Trend Analysis**: Use the "Summary Dashboard" to identify historical trends in case volumes, waiting lists, and distribution of outpatient vs. inpatient care.

## Conclusion

This Healthcare Analysis Dashboard project is a powerful tool for monitoring patient case volumes, understanding trends, and improving the allocation of medical resources. With its interactive features and multiple visualizations, users can dive deep into specific specialties or analyze overall healthcare performance.
