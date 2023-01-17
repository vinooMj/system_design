𝗢𝗽𝗲𝗻 𝗦𝗼𝘂𝗿𝗰𝗲 𝗮𝗻𝗱 𝗖𝗹𝗼𝘂𝗱 𝗧𝗲𝗰𝗵𝗻𝗼𝗹𝗼𝗴𝗶𝗲𝘀 𝘂𝘀𝗲𝗱 𝗯𝘆 𝗡𝗲𝘁𝗳𝗹𝗶𝘅

Netflix has more than ~300 million subscribers from 190+ countries. In addition, Netflix processes trillions of events and petabytes of data daily to support daily
business needs.

Netflix is a data-driven company. Data back almost all business decisions there. The Data Platform lies in the heart of the Platform Organization of Netflix, serving 
all the
company's data needs.

It uses a plethora of technologies at each layer :

Realtime Processing :

it is one of the key factors that enable Netflix to maintain its leading position in the competition of entertaining its users.

Kafka(Multi-tenant messaging as a service )
Flink (Stream Processing as a Service )

Netflix Mantis: Mantis is a platform to build an ecosystem of realtime stream processing applications,provides the APIs to manage the life cycle of jobs 
(like deploy, update, and terminate).

Netflix KeyStone: Keystone Stream Processing Platform is Netflix’s data backbone and an essential infrastructure enabling engineering data-driven culture.

The Keystone platform offers two production services:

Data Pipeline: streaming enabled Routing Service, and Kafka enabled Messaging Service, together is, responsible for producing, collecting, processing, aggregating, 
and moving all microservice events in near realtime.


Stream Processing as a Service (SPaaS): enables users to build & operate custom-managed stream processing applications, allowing them to focus on business application 
logic while platform provides the scale, operations, and domain expertise.


Batch Processing:

Netflix extensively uses Spark to ETL data into the Petabytes-scale data warehouse and access that data using Spark and Presto/TrinoDB. It also provides sub-second 
latency for a specific class of queries using Druid.

Presto 
Spark 
Hadoop
Druid
Iceberg

WorkFlow :

Netflix Maestro : Data Workflow Orchestration platform to meet the current and future needs of Netflix. It is a general-purpose workflow orchestrator that provides 
a fully managed workflow-as-a-service (WAAS) to the data platform at Netflix.


Scheduler :

Netflix Meson : its registered as a Mesos framework, manages the launch, flow control and runtime of the various workflows. Meson delegates the actual resource 
scheduling to Mesos.

Storage:

Data warehouse, contains hundreds of Petabytes of data, and each day, they ingest and create additional Petabytes.

Cassandra
Mysql
R.D.S. 
Elastic Search
R.D.S. 
S3

Netflix's data landscape is complex, and a monumental task and requires scalable architecture, robust design, a strong engineering team, and amazing cross-functional
collaboration.
