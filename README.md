# Apache Tez (apache-tez)
Apache Tez is an application framework for complex directed-acyclic-graph (DAG) based processing of data built on Apache Hadoop YARN. It is the default execution engine for Apache Hive providing in-memory data passing, session reuse, and dynamic DAG optimization.

**URL:** [https://tez.apache.org/](https://tez.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Big Data, DAG, Execution Engine, Hadoop, YARN, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Tez DAG API
Java programming model for defining and submitting DAG computation jobs to Apache YARN with Vertex, Edge, and Processor implementations.

**Human URL:** [https://tez.apache.org/developer-docs.html](https://tez.apache.org/developer-docs.html)

#### Tags:

 - Java, DAG, YARN, Hadoop

#### Properties

- [Documentation](https://tez.apache.org/developer-docs.html)
- [APIReference](https://tez.apache.org/javadocs/)
- [Maven Java SDK](https://search.maven.org/search?q=org.apache.tez)

### Apache Tez UI REST API
REST endpoints for monitoring Tez application history, DAG details, vertex and task statistics via the YARN Application History Server.

**Human URL:** [https://tez.apache.org/tez-ui.html](https://tez.apache.org/tez-ui.html)

#### Tags:

 - REST, Monitoring, YARN, History

#### Properties

- [Documentation](https://tez.apache.org/tez-ui.html)

## Common Properties

- [GitHubRepository](https://github.com/apache/tez)
- [Documentation](https://tez.apache.org/)
- [Portal](https://tez.apache.org/)
- [ReleaseNotes](https://github.com/apache/tez/releases)
- [TermsOfService](https://www.apache.org/licenses/)

## Features

| Name | Description |
|------|-------------|
| DAG-Based Execution | Flexible DAG computation model replacing MapReduce for complex multi-stage pipelines. |
| In-Memory Data Passing | Direct in-memory data transfer between vertices eliminating HDFS I/O. |
| Session Reuse | Tez sessions reuse container allocations across DAG submissions for reduced latency. |
| Dynamic Optimization | Runtime DAG modification based on actual data statistics during execution. |
| YARN Integration | Native YARN resource management with fine-grained resource requests per vertex. |

## Use Cases

| Name | Description |
|------|-------------|
| Apache Hive Query Execution | Tez is the default execution engine for Apache Hive queries. |
| Apache Pig Script Execution | Execute Apache Pig Latin scripts as optimized Tez DAGs. |
| Complex ETL Pipelines | Multi-stage data transformation pipelines with in-memory data passing. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop YARN | Native YARN resource manager integration for cluster resource allocation. |
| Apache Hive | Default execution engine for Hive queries in HDP and CDH distributions. |
| Apache Pig | Tez execution backend for Apache Pig script compilation and execution. |
| Apache HDFS | Input/output storage for Tez job data via Hadoop Distributed File System. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
