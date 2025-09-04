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

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/f3830388-c59e-436d-a2eb-51c6b96bb566" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/d027e72f-c932-4db4-baff-2565034c5a7f" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/3c77f130-b898-4d9e-bb1a-b356bb4fe25a" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/a39dbae2-5bdb-442d-b6d9-2863ac34df47" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/58355349-21a5-418c-958e-f5cad2a3a28a" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/2bf3eada-ab8c-45cd-9543-0e216d8ed767" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/d463f286-0f6e-48f3-a6fb-9f6bcf6bdc1c" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/2186a351-acf5-4f1d-aa35-a3bec70bdf22" />







