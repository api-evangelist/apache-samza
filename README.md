# Apache Samza (apache-samza)
Apache Samza is a distributed stream processing framework that provides a simple API for building stateful stream processing applications. It integrates with Apache Kafka for messaging and supports both stream and batch processing.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-samza/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-samza/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Big Data, Hadoop, Kafka, Stream Processing, Streaming, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Samza REST API
Samza provides REST endpoints for job management, task monitoring, and checkpoint retrieval, along with high-level Streams API and SQL support for building stateful stream processing applications on Apache Kafka and YARN.

**Human URL:** [https://samza.apache.org/learn/documentation/](https://samza.apache.org/learn/documentation/)

#### Tags:

 - Job Management, REST, Stream Processing, Apache, Open Source

#### Properties

- [Documentation](https://samza.apache.org/learn/documentation/)
- [OpenAPI](openapi/apache-samza-rest-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/samza)
- [Documentation](https://samza.apache.org/)
- [SpectralRules](rules/apache-samza-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-samza-vocabulary.yaml)
- [NaftikoCapability](capabilities/samza-workflow.yaml)
- [JSON-LD](json-ld/apache-samza-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Kafka Integration | Native Apache Kafka consumer/producer for stream processing |
| YARN Execution | Runs on Apache YARN for resource management and fault tolerance |
| Stateful Processing | Local state stores with RocksDB for low-latency stateful computations |
| Exactly-Once Processing | Transactional state stores for exactly-once semantics |
| Flexible Deployment | Run on YARN, Kubernetes, or standalone |
| High Level API | Fluent API and SQL support for stream transformations |

## Use Cases

| Name | Description |
|------|-------------|
| Event Stream Processing | Real-time processing of Kafka event streams |
| Stateful Aggregations | Windowed aggregations over streaming data |
| Stream Joins | Join multiple Kafka streams for enrichment |
| Change Data Capture | Process CDC events from databases in real time |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Primary messaging system for Samza input and output streams |
| Apache YARN | Resource management and job scheduling on Hadoop |
| Apache Hadoop | HDFS integration for checkpoint storage |
| RocksDB | Embedded state store for local stateful processing |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Samza REST API](openapi/apache-samza-rest-api.yaml)

### JSON Schema

- [Job](json-schema/apache-samza-job-schema.json)
- [Task](json-schema/apache-samza-task-schema.json)
- [Checkpoint](json-schema/apache-samza-checkpoint-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache Samza JSON Structures](json-structure/)

### JSON-LD

- [Apache Samza Context](json-ld/apache-samza-context.jsonld)

### Examples

- [Apache Samza Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Stream Processing Workflow](capabilities/samza-workflow.yaml) | Apache Samza | 6 | Data Engineer, Platform Engineer |

## Vocabulary

- [Apache Samza Vocabulary](vocabulary/apache-samza-vocabulary.yaml) — Unified taxonomy mapping stream processing resources, actions, workflows, and personas

## Rules

- [Apache Samza Spectral Rules](rules/apache-samza-spectral-rules.yml) — Rules enforcing Apache Samza API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
