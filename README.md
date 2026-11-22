# ![Nicholas Saros — Distributed systems and data processing](./assets/profile-header.svg)

I work on systems that store, move, and process data. Suppose a worker writes a result and crashes before saving its offset. Can it safely process the same record again? I like these questions because the answer depends on both sides of the pipeline — how the consumer tracks progress and how the destination handles a second write.

## Engineering focus

- **Distributed systems.** I’m interested in how a partition key shapes ordering, load distribution, and the work a cluster can do in parallel.
- **Stream and batch processing.** With Kafka and Spark, I care about what happens to the result when an event arrives late or a job replays yesterday’s input.
- **Databases and warehousing.** I like tracing a slow query back to the data layout. Partition pruning and the amount of data shuffled between workers can matter more than the final aggregation.

## Toolkit

| | Technologies |
| --- | --- |
| 🌊 **Data processing** | Apache Kafka · Apache Spark · Apache Hadoop · Apache Airflow |
| 🗄️ **Warehousing** | Oracle Autonomous Data Warehouse (ADW) |
| ☁️ **Cloud** | AWS · Oracle Cloud Infrastructure (OCI) · Google Cloud (GCP) |
| ⚙️ **Infrastructure** | Docker · Kubernetes · Terraform |
| 💻 **Languages** | C++ · Python · Java · Go |

## From my repositories

**[SimpleProtobuf](https://github.com/nicholassaros/SimpleProtobuf)** is a small C++ producer–consumer project. Producers enqueue Protocol Buffers messages, and consumers wait on a condition variable until a message is available. [Read the queue implementation →](https://github.com/nicholassaros/SimpleProtobuf/blob/HEAD/src/ThreadSafeQueue.cpp)

[Explore all repositories →](https://github.com/nicholassaros?tab=repositories)
