# Data-Pipeline-based-on-Messaging-using-Pyspark-and-AirFlow

This project demonstrates building a big data pipeline on AWS at scale. The Covid-19 dataset is streamed real-time from an external UPI using NiFi. The complex JSON data is parsed into CSV using NiFi and the result is stored in HDFS. This data is then sent to Kafka for data processing using PySpark. The processed data will then be consumed from Spark and stored in HDFS. A Hive table is created on top of HDFS and finally the cleaned, transformed data is stored in the data lake and deployed.

<img width="778" alt="Screenshot 2023-06-01 at 10 10 02 AM" src="https://github.com/um2158/Data-Pipeline-based-on-Messaging-using-Pyspark-and-AirFlow/assets/78294167/56fa8382-97cd-4844-9d09-74940bcb5209">

# Further tasks:
- Use orchestration other than AirFlow, like Luigi, Prefect, Dagster
- Create a visualization
