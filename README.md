## Introduction
This project builds a data engineering pipeline using TCP/IP socket, Apache Spark, OpenAI LLM and Kafka.
It starts from extracting data from yelp dataset, process it, use sentiment analysis with ChatGPT and produce kafka topic.

The project is designed with the following components:

- **Data Source**: `yelp.com` dataset is used for pipeline.
- **TCP/IP Socket**: Used to stream data over the network in chunks
- **Apache Spark**: For data processing with its master and worker nodes.
- **Confluent Kafka**: Our cluster on the cloud
- **Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.

