### SmartStocks - NRT REST Processing with FLaNK

https://www.datainmotion.dev/2020/12/smart-stocks-with-flank-nifi-kafka.html

https://www.datainmotion.dev/2020/12/ingesting-websocket-data-for-live-stock.html

### Real-Time Stock Processing With Apache NiFi, Apache Flink and Apache Kafka 

We will ingest a variety of real-time feeds including stocks with NiFi, filter and process and segment it into Kafka topics. Kafka data will be in Apache Avro
format with schemas specified in Cloudera Schema Registry. Apache Flink, Kafka Connect and NiFi will do additional event processing along with machine learning 
and deep learning. We will store real-time feed data in Apache Kudu for real-time analytics and summaries. Apache OpenNLP, Apache MXNet, CoreNLP, NLTK and 
SpaCy will be used to analyse stock trend data in streams as well as stock prices and futures.   As part of the stream processing we will also be 
classifying images and stock data with Apache MXNet and DJL.

We will also produce cleaned and aggregated data to subscribers via Apache Kafka, Apache Flink SQL and Apache NiFi. We will push to applications, 
message listeners, web clients, Slack channels and to email,

To be useful in our enterprise, we will have full authorization, authentication, auditing, data encryption and data lineage via Apache Ranger, 
Apache Atlas and Apache NiFi.


### References:

* https://community.cloudera.com/t5/Community-Articles/Real-Time-Stock-Processing-With-Apache-NiFi-and-Apache-Kafka/ta-p/249221


### Using the Mm FLaNK Stack for Edge AI (Flink, NiFi, Kafka, Kudu)


Introducing the FLaNK stack which combines Apache Flink, Apache NiFi, Apache Kafka and Apache Kudu to build fast applications for IoT, AI, rapid ingest.

FLaNK provides a quick set of tools to build applications at any scale for any streaming and IoT use cases.

https://www.flankstack.dev/

### Tools

* Apache Flink, Apache Kafka, Apache NiFi, MiNiFi, Apache MXNet, Apache Kudu, Apache Impala, Apache HDFS

### References

* https://www.datainmotion.dev/2019/08/rapid-iot-development-with-cloudera.html
* https://www.datainmotion.dev/2019/09/powering-edge-ai-for-sensor-reading.html
* https://www.datainmotion.dev/2019/05/dataworks-summit-dc-2019-report.html
* https://www.datainmotion.dev/2019/03/using-raspberry-pi-3b-with-apache-nifi.html


### Continuous SQL with Kafka and Flink

In this talk, I will walk through how someone can setup and run continous SQL queries against Kafka topics utilizing Apache Flink. 
We will walk through creating Kafka topics, schemas and publishing data.

We will then cover consuming Kafka data, joining Kafka topics and inserting new events into Kafka topics as they arrive. This basic over view
will show hands-on techniques, tips and examples of how to do this.


### Hail Hydrate! From Stream to Lake


A cloud data lake that is empty is not useful to anyone.

How can you quickly, scalably and reliably fill your cloud data lake with diverse sources of data you already have and new ones you never imagined you needed. Utilizing open source tools from Apache, the FLaNK stack enables any data engineer, programmer or analyst to build reusable modules with low or no code. FLaNK utilizes Apache NiFi, Apache Kafka, Apache Flink and MiNiFi agents to load CDC, Logs, REST, XML, Images, PDFs, Documents, Text, semistructured data, unstructured data, structured data and a hundred data sources you could never dream of streaming before.

I will teach you how to fish in the deep end of the lake and return a data engineering hero. Let's hope everyone is ready to go from 0 to Petabyte hero.


### FLANK Stack for Cloud Data Lakes

Utilizing an all Apache STack for Rapid Data Lake Population and querying utilizing Apache Flink, Apache Arrow, Apache NiFi and Apache Kafka.

In the world of fast moving images, time series data, sensor readings and raw text data, we need a fast, open architecture that scales.

This is where the FLANK Stack comes in, By utilizing an all Apache Stack of Apache Flink, Apache Arrow, Apache NiFi and Apache Kafka.

This enables any data user to build smart applications for intelligent access to any data, any where, at anytime. We need not worry about how to get the data, how to translate or special access methods. The data is instantly usable in queries, reports, data science and business use case solving. The traditionally difficult parts of data engineering become easy with quick and easy DataOps and orchestration of IoT * data from edge devices, docker containers, k8 pods and anywhere data lives into live cloud data lakes at scale.


### Utilizing Apache Kafka, Apache NiFi and MiNiFi for EdgeAI IoT at Scale

A hands-on deep dive on using Apache Kafka, Kafka Streams, Apache NiFi + Edge Flow Manager + MiniFi Agents with Apache MXNet, OpenVino, TensorFlow Lite, and other Deep Learning Libraries on the actual edge devices including Raspberry Pi with Movidius 2, Google Coral TPU and NVidia Jetson Nano. We run deep learning models on the edge devices and send images, capture real-time GPS and sensor data. With our low coding IoT applications providing easy edge routing, transformation, data acquisition and alerting before we decide what data to stream real-time to our data space. These edge applications classify images and sensor readings real-time at the edge and then send Deep Learning results to Kafka Streams and Apache NiFi for transformation, parsing, enrichment, querying, filtering and merging data to various Apache data stores including Apache Kudu and Apache HBase.

https://www.datainmotion.dev/2019/08/updating-machine-learning-models-at.html

Summary:   Streaming IoT Events From Edge into Your Cloud Data Lake is easy utilizing the open source FLaNK Stack. I will show you how to bring in device data from the edge to your cloud data lake. ]
