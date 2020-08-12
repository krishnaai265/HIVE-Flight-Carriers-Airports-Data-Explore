# HIVE Flight Carriers Airports Data Explore
-----------------------

### HIVE

* Hive gives a SQL-like interface to manage data. It is used in Amazon H3 file system. It also support HiveQL. Hive implicitly codeword hiveQL statement into Adirected acyclic graph of mapreduce those the spark jobs. <br/>
* It support Advance features such as indices, partition, buckets, asummetric transactions, custom user defined functions, joins, sampling & many others. Lots of them take a considerable amount of time if implemented manually. <br/>


### Create directory in Hadoop

<img src="Screenshots/create_directory.png"> <br/>

In the above screenshot, I have created directory “/flight-data” in HDFS. <br/>

### Copy file to Hadoop File System

<img src="Screenshots/copy_file_to_hdfs.png "> <br/>

In the above screenshot, I have put Dataset file to HDFS directory “/flight-data”. <br/>

### Create table in hive
 
<img src="Screenshots/create_table_flying.png"> <br/>

In the above screenshot, I have created table “flying”.

### Load Data into table flying
 
<img src="Screenshots/load_flying.png"> <br/>

In the above screenshot, I have loaded data into table. <br/>
**load data:** load data command <br/>
**Inpath ‘/flight-data/78*’:** path where data is present <br/>
**Into table flying:** table ipinyou to store data <br/>

### Create table airports in hive
 
<img src="Screenshots/create_table_airports.png"> <br/>

In the above screenshot, I have created table “airports”. <br/>

### Load Data into table airports

<img src="Screenshots/load_airports.png"> <br/>

In the above screenshot, I have loaded data into table airports.
**load data:** load data command 
**Inpath ‘/flight-data/airports.csv’:** path where data is present
**Into table airports:** table ipinyou to store data

### Create table carriers in hive

<img src="Screenshots/create_table_carriers.png"> <br/>
 
In the above screenshot, I have created table “carriers”. <br/>

### Load Data into table carriers

<img src="Screenshots/load_carriers.png"> <br/>

In the above screenshot, I have loaded data into table airports.
**load data:** load data command 
**Inpath ‘/flight-data/carriers.csv’:** path where data is present
**Into table carriers:** table carriers to store data

### 1.	Find all carriers who cancelled more than 1 flights during 2007, order them from biggest to lowest by number of cancelled flights and list in each record all departure cities where cancellation happened.

<img src="Screenshots/carrier_who_cancelled_more_than_1_flight.png">
<img src="Screenshots/carrier_who_cancelled_more_than_1_flight2.png">


**Created by:** <br/>
**Name: Krishna Kumar Singh** <br/>
**Email: krishnaai265@gmail.com** <br/>
**Phone: +91-9368754996** 
