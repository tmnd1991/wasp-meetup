---
theme : "Beige"
customTheme : "noBorder"
transition: "slide"
highlightTheme: "monokai"
logoImg: "assets/logo.png"
slideNumber: true
title: "VSCode Reveal intro"
---

# WASP

Bologna Big Data meetup

3rd March 2020 @ LuogoComune

---

#### Speaker

Antonio Murgia

![](assets/AM2.jpeg)

**BIG** Data Engineer @ AgileLab

---

# Agenda

- What is WASP
- Use cases
- Features
- Upcoming Features

---

# What is WASP

WASP is a big data **platform** that allows you to not **waste time** with devops architectures and integrating different components. 

WASP lets you **focus** on your data, business logic and algorithms, without worrying about tipical big data problems.

--

![](assets/platform.png)

--

# Production Ready

WASP empowers **multiple** mission critical use cases

- running in production since 2017 🚀
- serves hundreds of thousands of devices

--

# Wide

- Real Time
- Near Real Time
- Batch
- Pluggable Datastore

--

# Analytics

- Iterative
- Real Time
- Windowed Aggregations

--

# Streaming

- at least once or exactly once delivery
- periodically training a machine learning model
- publishing your results in real time, to be reactive
- feeding different datastores from the same data flow in a safe way

--

# Platform

Not just a "library" but a simplified __way__ for:
- running
- managing
- monitoring

**mixed** Big Data workloads

---

# Use cases

--

### IoT

--

### Data Ingestion

--

### Data Transformation

--

### Kappa-Lambda Architecture

--

### Machine Learning

---

# Features...

- Encourages Architectural Correctness
- Monitoring
- High Availability
- `Either[Dev, Ops]`
- Producers
- RT-consumers

--

# Features...

- Spark as a Service
- Schema Registry Integration
- Avro Encoder
- Multi Data stores
- Kafka Multi Topic Writer
- Spark State Manager

--

### Architectural Correctness

- Wrong architectural choices are **difficult**
- Encourages process de-coupling
- ...

--

### Monitoring

- Opt-in automatic timestamping of data
- Kafka backlog monitoring from Spark Streaming Queries
- Throughput metrics

--

### High Availability

1. Each "role" is in **hot-standby**
2. Automatic recover
3. Close-to-zero downtime
   - even if multiple nodes fail 

--

### Either[Dev, Ops]

- Code agnostic from data format
- Clear distinction between
  - business logic
  - physical boundaries

--

### Producers

- Auto-generate data
- Reply events from storage
- Lightweight recurrent tasks

--

### RT-consumers

- Akka Stream
- Suitable for Low Latency
- Lower througput than Spark Streaming

--

### Spark as a Service

- Start/Stop processing from REST API
- ...
- ...

--

### Schema Registry Integration

Seamless darwin integration
![](assets/darwin.png)

--

### Spark State Evolution

#### When you try to add a field to the spark state
![](assets/state_evolution.jpg)

--

### Multi Data stores

- Configuration driven Data store
- Configuration driven Data format

(Things can go wrong)™

--

### Kafka Multi Topic Writer

![](assets/multi-topic.png)

--

### Spark State Manager

- Scale ⬆️ stateful streaming query
- Scale ⬇️ stateful streaming query
- Change format/content of the state 

*without data loss

---

# Upcoming features

--

![Delta](assets/delta-lake.png)

--

## Apache Flink

![Flink](assets/flink.gif)

--

## UI for better UX

- 🤓 REST is for NERDS

- 😎 UI are for everyone

--

## GDPR module

- Configuration driven data discovery

- Configuration driven data deletion

![](assets/gdpr2.jpg)

--

## Data (Lake) Catalog

![](assets/data_catalog.jpg)

--

## Kafka Batch Writer

---

# Questions ?

