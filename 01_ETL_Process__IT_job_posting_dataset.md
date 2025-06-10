# ETL Process

## Introduction to the ETL Process
ETL (Extract, Transform, Load) is the process of collecting raw data, cleaning and structuring it, and then loading it into a system for analysis. It ensures data quality and enables the creation of accurate and meaningful visualizations.

## Etapes

The ETL process (Extract, Transform, Load) is fundamental in data management and consists of three main stages:

### 1. Extraction (Extract)

This stage involves obtaining data from one or more sources.<br>

**Goal**: Bring in raw data from its source to begin working with it.

- The sources for this project is a file in format CSV (Comma-Separated Values) and it will be loaded in Power BI.












![Extract_Process_CSV_File](https://github.com/user-attachments/assets/b475e800-d85b-43d2-bf47-72d7eb8326b4)













### 2. Transformation (Transform)

This is where the data is cleaned, structured, and modified to make it useful and consistent.<br>

**Goal**: Ensure that the data is in a suitable format for analysis or final loading.

Some common tasks include in this stage are:

- Removing duplicates

- Correcting formatting errors

- Standardizing units or date formats

- Creating new columns or calculations

- Filtering out unnecessary data

- Combining multiple sources (joins)



The following image shows the job postings dataset, including various columns with data—some of which are complete, while others contain blank cells.












![Loaded_data](https://github.com/user-attachments/assets/ea7d29ce-1cb4-4ced-a499-5998582d827a)










Next, some data was separated into individual columns, such as Month and Year. All of this was done within the Power Query environment, which is part of Power BI. Formulas were created using the DAX tool, and KPIs were calculated, including totals, averages, maximums, and minimums. Words like 'employees' were removed from the company size column to clean the dataset as much as possible, making it ready for transformation.




![PowerQuery_DaxFormula](https://github.com/user-attachments/assets/235343ec-448c-4350-9c35-844da8c00e18)







There were a large number of blank cells. In this case, the null fields were handled by replacing text fields with 'No data' and numeric fields with a value of zero (0).





![PowerQuery_DaxFormula02](https://github.com/user-attachments/assets/3f2584b3-e67c-4acd-96d0-4e65af025a3b)







The use of Power Query was essential, as it allowed raw data to be transformed into clean, structured, and analysis-ready information. It was a key tool for enabling efficient, repeatable processes within any Business Intelligence workflow





![PowerQuery_DaxFormula01](https://github.com/user-attachments/assets/fc1aba1d-00e1-408a-8de9-f230d4e947c0)
















### 3. Load 

Finally, the transformed data is loaded into its final destination.<br>

**Goal:** Make the data available for analysis, visualization, or operational use.

- In this case, the clean file will be loaded into a dashboard, such as Power BI.



  




![Starting_Visualizations](https://github.com/user-attachments/assets/7082e05f-feb8-454f-a33d-009e80814267)




For this section, the visualizations were created using the loaded and cleaned dataset of job postings related to careers in the field of Data Science.





































  







