# Projects

## Single Customer View Framework                        | Mar’17 – Jan’19

The objective of this project is to create a Data Lab which will help to enable a 360-degree view of the customers by joining data across systems and countries. It will also help to capture the large volume of data in a single repository.  

### Roles and Responsibilities

  1. Development of Apache SQL framework which read property files and execute the queries in the property files using Spark abstraction API’s DataFrame.
  2. Development of property files which includes joining multiple tables in Hive
  3. Development of nifi jobs for copying data from one cluster to the new HaaS cluster
  4. Control-M jobs to automate the process - nifi file copy and transformation job.

#### Technologies used: 
Spark Core, Spark SQL, Scala, Hadoop, Hive, HDFS, Apache Nifi, Control-M

## Real-time Data Ingestion Framework                    | May’16 – Mar’17

The objective of this project is to develop a real-time streaming application in which XML messages will be sourced from various sources and the messages will be parsed into different types of fields and then store those fields into various hive tables. The table data will be further used by the downstream application for different types of analytics. 

### Roles and Responsibilities

  1. Development of Kafka producer which transfers the XML message and places it in the Kafka topic.
  2. Development of Spark streaming application in Scala which reads from the Kafka topic.
  3. Development of programs to perform column and table shredding of the XML messages using Scala/java and then load messages into Hbase.
  4. Development of automated jobs that reads Hbase tables at the end of the day and store daily files in the hive tables.

#### Technologies used
Spark, Scala, Kafka, Zookeeper, Oozie, HBase, Hadoop, Hive, Java	


## Data Ingestion Framework (Batch) 					            | Dec’15 – May’16

The objective of this project is to develop a common data lake where data from various payment sources will be sources using Hadoop technologies. 

### Roles and Responsibilities

  1. Development of Map Reduce programs which will perform different types of file and data validations.
  2. Development of falcon/oozie workflow to integrate map reduce programs. 
  3. Development of control-m jobs to schedule the data ingestion on a daily basis based on the frequency of files.
  4. Development of hive views in the common data lake in order to provide access to different teams

#### Technologies used: 
MapReduce, falcon, Zookeeper, Oozie, Hadoop, Hive, Impala, Java, control-m



