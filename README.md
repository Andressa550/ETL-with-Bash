Practice exercises from IBM DB0250EN using a Cloud IDE based on Theia and Postgres running in a Docker container.
Building ETL and Data Pipelines with Bash, Airflow and Kafka

<b>cp-access-log.sh</b>

Problem:

- Copy the data in the file ‘web-server-access-log.txt.gz’ to the table ‘access_log’ in the PostgreSQL database ‘template1’.
- The file is available at the location : “cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0250EN-SkillsNetwork/labs/Bash%20Scripting/ETL%20using%20shell%20scripting/web-server-access-log.txt.gz".
 - The following are the columns and their data types in the file:
a. timestamp - TIMESTAMP
b. latitude - float
c. longitude - float
d. visitorid - char(37)
 - The columns which we need to copy to the table are the first four coumns : timestamp, latitude, longitude and visitorid.
 - NOTE: The file comes with a header. So use the ‘HEADER’ option in the ‘COPY’ command.
