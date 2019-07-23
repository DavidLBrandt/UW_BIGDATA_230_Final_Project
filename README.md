# Project Description
This project attempts to analyse the taxi pickup and dropoff location usage in New York city to see which locations are most and least remote based on the diversity of connecting taxi trips.

I will be patterning my project after the approach outlined by [Neo4j Streams Kafka Integration](https://neo4j.com/labs/kafka/) at [neo4j.com](https://neo4j.com)

# Data Source
the data source will be the Java [Taxi Data Simulator](https://bigdatatechnologiesstor.blob.core.windows.net/data/taxi_simulator.jar) provided in the UW BIGDATA 220 course last quarter.  This provides a stream of taxi data from [TLC Trip Record Data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page) as if it were happening in real time.

# Tools
* [Taxi Data Simulator](https://bigdatatechnologiesstor.blob.core.windows.net/data/taxi_simulator.jar)
* [Apache Kafka](https://kafka.apache.org/quickstart)
* [Kafka Connect: Neo4j Source Plugin (Confluent Hub)](https://neo4j-contrib.github.io/neo4j-streams/#_kafka_connect)
* [Neo4j Plugin: Change Data Source](https://neo4j-contrib.github.io/neo4j-streams/#_neo4j_streams_producer)
* [Neo4j Plugin: Sink](https://neo4j-contrib.github.io/neo4j-streams/#_neo4j_streams_consumer)
* [Neo4j Plugin: Procedures](https://neo4j-contrib.github.io/neo4j-streams/#_procedures)
* [Docker Compose setups](https://neo4j-contrib.github.io/neo4j-streams/#docker)

# Questions Answered
* Which location is most isolated based on connecting taxi trips?
* Which location is most central based on connecting taxi trips?
