# Global air quality

## Table of Contents

 - [Dashboard](#Dashboard)
 - [Project Overview](#Project-Overview)  
 - [Problem Statement](#Problem-Statement)
 - [Data Source](#Data-Source)
 - [Tools](#Tools)
 - [Data Cleaning](#Data-Cleaning)
 - [Data Analysis](#Data-Analysis)
 - [Result and Finding](#Result-and-Finding) 
 - [Limitations](#Limitations)
 - [References](#References)

### Dashboard: 
![dashboard](https://github.com/user-attachments/assets/ad116166-774e-4e56-835d-599adc3fcb6e)

### Project Overview:
This project aims to analyze global air quality data from 2023, focusing on pollution levels across various countries and key environmental factors such as humidity, wind speed, and temperature. Insights from this analysis help identify regions with the highest pollution levels, compare air quality between countries, and uncover patterns that may inform environmental policies and actions.

### Data Source:
Global Air Quality Dataset (Kaggle)
### Tools:
Microsoft Excel
### Data Cleaning:
#### Steps followed for cleaning and preparing the data:

 - Downloaded the dataset from Kaggle and saved it in an Excel workbook for easier manipulation.
 - Changed date type by using format cells to ensure consistency in date fields.
 - Renamed columns with units (e.g., "Concentration (µg/m³)") for clarity and accurate interpretation.
 - Performed a duplicate check and used filters to identify missing values.
 - Used Power Query to unpivot pollutants (PM2.5, PM10, NO₂, SO₂, O₃) into one column, and their values into a "Concentration" column, making it easier to work with data for analysis and visualization.
 Before 
 ![before Untitleunpivot data](https://github.com/user-attachments/assets/60e5dc4d-1bc1-4452-b3a9-761411cb9f74) 

 After
 ![Untitleunpivot data](https://github.com/user-attachments/assets/54835d0b-6e74-4369-b729-0504e8c2dc9f)

 - Converted data range into a table for structured manipulation and easier creation of pivot tables and charts.
 - Pivot tables and charts were created to facilitate a deep dive into pollutant concentration trends.
### Data Analysis:
This analysis was driven by several key questions:

 - What is the air quality in different countries in 2023?
    - Explored and visualized pollutant concentrations like PM2.5, PM10, and NO₂ across multiple regions.
 - Which countries are more polluted compared to others? (Pollutant comparison)
    - Used bar and line charts to compare pollution levels across countries.
 - What is the global view of factors like humidity, wind speed, and temperature?
   - Created visualizations to study the relationship between these factors and pollution levels.
Additional Analysis Steps :
 - Unpivoting Data: Used Power Query to restructure pollutant data for easier analysis.
 - Pivot Tables and Charts: Created pivot tables to summarize data by country, pollutant type, and other relevant variables.
 - Visual Filters and Slicers: Used slicers and filters to enable easy comparison by pollutant type and country, improving the interactivity of the report.

### Results and Findings:
The dashboard presents a clear overview of global air quality, helping answer critical questions related to pollution:

 - Comparison of air quality across different countries using visualizations such as bar charts and line graphs.
 - Trends in pollutant levels for PM2.5, PM10, and other major pollutants over the year 2023.
 - Humidity, Wind Speed, and Temperature analysis across different regions, providing a deeper understanding of environmental factors influencing air quality.

 ![humidity](https://github.com/user-attachments/assets/9d82ecc0-9617-4557-accf-7c7cd384d301)


 ![winds](https://github.com/user-attachments/assets/5e7e46e0-4619-4dc2-9dff-8c73abf64af6)


 ![temp](https://github.com/user-attachments/assets/e69303ee-34f6-4de4-b545-b5ffeac42baf)
 

### Visualizations Include:
- Bar and Line Charts for comparing pollutant concentrations across countries.
- Conditional Formatting to highlight regions with critically high pollution levels.
- Dynamic Slicers for filtering data by country, pollutant type, and other variables.
- These visualizations provide insights that could guide policymakers and environmental organizations in addressing global air quality issues.

### Limitations:
- Mapping Issues: Unable to implement field map visualizations to display geographic data effectively, limiting the ability to see pollution distribution on a global scale.


![concentration snap](https://github.com/user-attachments/assets/6ea39e3c-58bf-42e4-a29c-59e05a0c4eab)

- Slicer and Timeline Options for Maps: These were not available for better interaction with geographic data.
Despite these limitations, the project provides a comprehensive view of air quality data using available Excel functionalities.

### References:
- Kaggle: Global Air Quality Dataset
- YouTube channels
- ChatGPT for project guidance
