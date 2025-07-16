# 🚀 Building a Prototype of a Spark and Kafka Cluster

This project documents the setup and configuration of a prototype distributed computing environment implemented on the University of La Laguna's IaaS infrastructure. The core technologies used are Apache Spark and Apache Kafka, combined with integrations of popular NoSQL databases like Redis, Cassandra, and MongoDB.

## 🎯 Objectives

* Create a distributed data-processing cluster using Apache Spark (Master and Worker nodes).
* Implement real-time data streaming using Apache Kafka integrated with Spark Structured Streaming.
* Demonstrate practical integration of NoSQL databases (Redis, Cassandra, MongoDB) with Spark and Kafka.

## 🖥️ Infrastructure Overview

The infrastructure was provisioned using virtual machines on the IaaS environment provided by the University of La Laguna (ULL). Each VM was configured with:

* **Operating System**: Ubuntu 22.04
* **RAM**: 8 GB
* **CPUs**: 8 Virtual CPUs
* **Storage**: 25 GB

Machines were set up across different subnets, demonstrating distributed computing and networking concepts.

## ⚙️ Implemented Technologies

* **Apache Spark** for distributed computing.
* **Apache Kafka** for real-time data streaming.
* **Redis** for high-speed key-value storage.
* **Cassandra** for column-oriented distributed storage.
* **MongoDB** for flexible document-oriented storage.

## 📌 Key Implementations

* Configured secure SSH communication between Spark Master and Worker nodes.
* Set up JupyterLab on the Spark Master node for interactive computing.
* Conducted functional tests, including calculating π using Spark's Monte Carlo simulation and real-time word-count streaming using Kafka and Spark.

## 📑 Documentation

Detailed configuration steps, tests, and integrations performed are documented comprehensively in the provided PDF report (`Informe_Tecnologia_datos_masivos.pdf`), which includes configuration screenshots, test outcomes, and extensive technical details.

## 🎓 Author

**Francesca Tuninetti**
MSc in Cybersecurity and Data Intelligence (2024/2025)
University of La Laguna (ULL)

For detailed implementation, please refer to the attached documentation.
