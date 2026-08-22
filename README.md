# Apache Tez (apache-tez)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
