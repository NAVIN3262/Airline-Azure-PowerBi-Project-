# Airline-Azure-PowerBi-Project-

This project focuses on a data visualization solution for airline flight data using Microsoft Azure and Power BI.

The business problem is to analyze a dataset about flights in the United States, which includes information on delays, cancellations, and on-time performance. The data is reported for individual months at every major airport for every carrier.

Solution Architecture
The proposed solution uses a data pipeline built with Azure services.

The raw 

Airlines.csv file is stored in an Azure Blob Storage.



An 

Azure Data Factory is used to create a pipeline.




The pipeline uses a 

Copy Activity to move data from the Blob Storage (Source) to an Azure SQL Database (Sink).




Linked Services define the connection information between the Data Factory and the source/destination data stores.


The 

airlines table is created in the SQL database to hold the data.

Analysis and Insights
After the data is loaded into the SQL database, various SQL queries are run to analyze the data.

Queries are used to find the total number of delayed, cancelled, and on-time flights, grouped by year, month, and time label.



A view named 

Average is created to calculate the average departure delay based on different delay types.


The final part of the project involves using 

Power BI to create visualizations and gain insights. The visualizations include:


Line and bar charts showing the total number of delayed, cancelled, and on-time flights over time.

Pie charts and bar charts to visualize flights delayed by different reasons, such as Carrier, Late Aircraft, and National Aviation System.


Bar charts showing the number of delayed and cancelled flights by airport name.


Line charts illustrating trends in delayed flights and minutes delayed due to different reasons over time.


<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/2081e2fd-0782-435b-837c-d9003860663e" />
