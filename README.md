 # Problem Statement 
 In modern data-driven organizations, large volumes of raw data are generated and stored in different formats such as CSV files. Manually processing this data for analytics and reporting is inefficient, error-prone, and does not scale well as data volume grows. Traditional on-premise ETL solutions also require high infrastructure maintenance and lack flexibility.

There is a need for a scalable, automated, and cost-effective cloud-based data pipeline that can:

Automatically ingest raw data from cloud storage

Transform the data into a structured and analytics-ready format

Execute without manual intervention

Scale dynamically based on data size

Provide monitoring and logging for reliability

This project addresses these challenges by building a serverless cloud data pipeline on AWS that automates the end-to-end ETL process using cloud-native services.


## architecture 
<img width="956" height="457" alt="image" src="https://github.com/user-attachments/assets/30a20eeb-8bfc-4ab2-b309-6e25ae0d3534" />

## aws billing 
<img width="933" height="593" alt="image" src="https://github.com/user-attachments/assets/2b484cc6-0ea8-443a-9de6-828dc1cc35e0" />


## s3 bucket creation 
<img width="1905" height="617" alt="image" src="https://github.com/user-attachments/assets/9dd7ad22-2fbb-4afb-936a-dddf82c54c22" />

## glue job creation 
<img width="1905" height="851" alt="image" src="https://github.com/user-attachments/assets/12581802-70ff-4b56-a072-962baf89cf5b" />

##lambda fn 
<img width="1886" height="875" alt="image" src="https://github.com/user-attachments/assets/e988acd9-a028-494a-804c-bf11a404ebfc" />
<img width="1895" height="865" alt="image" src="https://github.com/user-attachments/assets/1bcf92d2-a520-4e92-b5b3-2837e981b8b7" />

input file (CSV FORMAT)
<img width="561" height="452" alt="image" src="https://github.com/user-attachments/assets/8d978471-34c3-4717-923f-fc8d686f2fef" />


csv file upload in input bucket 
<img width="1886" height="845" alt="image" src="https://github.com/user-attachments/assets/90e41195-c554-43dc-90ca-26be9d0ffc03" />



cloudwatch logs 
<img width="1902" height="723" alt="image" src="https://github.com/user-attachments/assets/ef221e94-dcee-43a1-b16d-bcc6a4ae05f8" />

running glue job 
<img width="1897" height="631" alt="image" src="https://github.com/user-attachments/assets/f80b20f6-0465-4537-9318-e92fec7222b7" />



output bucket 
<img width="1901" height="657" alt="image" src="https://github.com/user-attachments/assets/f9d9ef50-95ec-4816-b040-dbeea452d934" />

output data (Json format)
<img width="657" height="272" alt="image" src="https://github.com/user-attachments/assets/4ad6cc39-7d23-4a7e-a237-68ed8a814599" />


