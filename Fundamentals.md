
## Event Stream
![image](https://github.com/himouli/DataEngineering/assets/156985545/72270821-0447-42ae-aee5-a1907c581f13)

### Event Shelf Life
![image](https://github.com/himouli/DataEngineering/assets/156985545/8dc725f4-1f02-4722-b0d6-ce69c5888c66)

### Batch Processing
![image](https://github.com/himouli/DataEngineering/assets/156985545/9cb595a6-90d3-4190-b46d-699973007f2b)

### Real-Time Processing
![image](https://github.com/himouli/DataEngineering/assets/156985545/14b56ce5-b297-4e0f-972f-800aa0e59f07)

### Real-Time Analytics UseCases
![image](https://github.com/himouli/DataEngineering/assets/156985545/7371fbcc-5dab-4839-9cc5-9878428e2fbe)

![image](https://github.com/himouli/DataEngineering/assets/156985545/3b4bf596-16a9-4a15-80e4-aa72d45205d9)

### Real-Time Analytics Quadrants 
![image](https://github.com/himouli/DataEngineering/assets/156985545/14a87582-00b2-4daa-8b83-d2bdf6042efa)



## Transition from traditional architecture to Micro Services Architecture:

![image](https://github.com/himouli/DataEngineering/assets/156985545/3dc9eff5-29d7-4e19-9991-ebe1c1cc66d3)

![image](https://github.com/himouli/DataEngineering/assets/156985545/051c5861-464c-48ed-9bc9-71e140499d31)

## Traditional Datawarehouse for data analytics

![image](https://github.com/himouli/DataEngineering/assets/156985545/a3af7ac7-661a-4d71-82e5-7fbf39227bdb)

## Type of Queries:
Once the data has been imported into the data warehouse it can be queried and analyzed. Typically, there are two classes of queries executed on a data warehouse. 
* The first type are periodic report queries that compute business-relevant statistics such as revenue, user growth, or production output. These metrics are assembled into reports that help the management to assess the businesses overall health. 
* The second type are ad-hoc queries that aim to provide answers to specific questions and support business-critical decisions, for example a query to collect revenue numbers and spending on radio commercials to evaluate the effectiveness of a marketing campaign. Both kinds of queries are executed by a data warehouse in a batch processing fashion.

Stateful stream processing is a versatile and flexible design architecture that can be used for many different use cases. Three classes of applications that are commonly implemented using stateful stream processing: 
* (1) event-driven applications,
* (2) data pipeline applications, and
* (3) data analytics applications.

A traditional approach to synchronize data in different storage systems is periodic ETL jobs. However, they do not meet the latency requirements for many of today's use cases. An alternative is to use an event log to distribute updates. The updates are written to and distributed by the event log. Consumers of the log incorporate the updates into the affected data stores. Depending on the use case, the transferred data may need to be normalized, enriched with external data, or aggregated before it is ingested by the target data store.

Ingesting, transforming, and inserting data with low latency is another common use case for stateful stream processing applications. This type of application is called a data pipeline. Data pipelines must be able to process large amounts of data in a short time. A stream processor that operates a data pipeline should also feature many source and sink connectors to read data from and write data to various storage systems. Again, Flink does all of this.

![image](https://github.com/himouli/DataEngineering/assets/156985545/4e974edf-75df-4cf3-9689-a5b01dbca934)

The observation that data processing systems (at this point in time) could either provide fast or accurate results led to the design of the so-called lambda architecture.

## LAMBDA Architecture
![image](https://github.com/himouli/DataEngineering/assets/156985545/5c032e9d-ee96-417d-924e-5417280b72bf)

## Modern Streaming Stack
![image](https://github.com/himouli/DataEngineering/assets/156985545/e6e39ff5-41ae-4e34-a9cd-f7ac6c8895be)

### Event Producers
![image](https://github.com/himouli/DataEngineering/assets/156985545/99d60bd0-3263-4e78-97ac-35308a5b5967)

### Streaming Data Platform
![image](https://github.com/himouli/DataEngineering/assets/156985545/87a859a5-7388-448c-97aa-993b2511f4ee)

#### Topics in the Streaming Data Platform
![image](https://github.com/himouli/DataEngineering/assets/156985545/97c80e63-b93f-40df-89ee-2163b019d004)

#### Append only log file
![image](https://github.com/himouli/DataEngineering/assets/156985545/840271c1-88e2-47af-9283-09450208579b)

### Stream Processing Layer
![image](https://github.com/himouli/DataEngineering/assets/156985545/40b19c97-7170-4ed6-99b4-92f09f2a1363)

#### Stream Processor Patterns
![image](https://github.com/himouli/DataEngineering/assets/156985545/66f3085d-1d2b-4d8e-a06b-0d1a5745182d)

#### Diminishing Value of Individual data points
![image](https://github.com/himouli/DataEngineering/assets/156985545/4db69d97-05e5-4074-8ccf-0ba8d812d118)

#### Increasing Value of collective/aggregate data points
![image](https://github.com/himouli/DataEngineering/assets/156985545/20ebc61a-d4eb-4002-a505-da305ce70c5e)

### Serving Layer
![image](https://github.com/himouli/DataEngineering/assets/156985545/2b02fc20-f301-4392-a0c5-f8ed0e022d60)
* Ingestion Latency
* Query Latency
* Concurrency
* Key-Value Stores/ NoSQL stores / Realtime OLAP
  
