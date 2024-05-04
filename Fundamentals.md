
Transition from traditional architecture to Micro Services Architecture:

![image](https://github.com/himouli/DataEngineering/assets/156985545/3dc9eff5-29d7-4e19-9991-ebe1c1cc66d3)

![image](https://github.com/himouli/DataEngineering/assets/156985545/051c5861-464c-48ed-9bc9-71e140499d31)

Traditional Datawarehouse for data analytics

![image](https://github.com/himouli/DataEngineering/assets/156985545/a3af7ac7-661a-4d71-82e5-7fbf39227bdb)

Type of Queries:
Once the data has been imported into the data warehouse it can be queried and analyzed. Typically, there are two classes of queries executed on a data warehouse. 
The first type are periodic report queries that compute business-relevant statistics such as revenue, user growth, or production output. These metrics are assembled 
into reports that help the management to assess the businessâs overall health. The second type are ad-hoc queries that aim to provide answers to specific questions 
and support business-critical decisions, for example a query to collect revenue numbers and spending on radio commercials to evaluate the effectiveness of a marketing 
campaign. Both kinds of queries are executed by a data warehouse in a batch processing fashion.

Stateful stream processing is a versatile and flexible design architecture that can be used for many different use cases. In the following, we present three classes of 
applications that are commonly implemented using stateful stream processing: (1) event-driven applications, (2) data pipeline applications, and (3) data analytics 
applications.


A traditional approach to synchronize data in different storage systems is periodic ETL jobs. However, they do not meet the latency requirements for many of todayâs use cases.
An alternative is to use an event log to distribute updates. The updates are written to and distributed by the event log. Consumers of the log incorporate the updates into the 
affected data stores. Depending on the use case, the transferred data may need to be normalized, enriched with external data, or aggregated before it is ingested by the target 
data store.

Ingesting, transforming, and inserting data with low latency is another common use case for stateful stream processing applications. This type of application is called 
a data pipeline. Data pipelines must be able to process large amounts of data in a short time. A stream processor that operates a data pipeline should also feature many 
source and sink connectors to read data from and write data to various storage systems. Again, Flink does all of this.

![image](https://github.com/himouli/DataEngineering/assets/156985545/4e974edf-75df-4cf3-9689-a5b01dbca934)

The observation that data processing systems (at this point in time) could either provide fast or accurate results led to the design of the so-called lambda architecture
** LAMBDA Architecture
![image](https://github.com/himouli/DataEngineering/assets/156985545/5c032e9d-ee96-417d-924e-5417280b72bf)




