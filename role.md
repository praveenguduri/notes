
**Role**

Individual Contributor or a leader role (leading a very small team of specialists) with deep technical expertise in following areas:

    - Data Platforms(Spark, Snowflake, Hive, Streaming, Databricks)
    - Public Cloud Services(AWS/GCP)
    - Microservice patterns, API design
    - Intermediate to Advanced Python or Java

* Guide data partners throughout the firm to onboard the analytical data into the enterprise data systems for analytical and machine learning.
* Own the responsibility of making the product successful in a fast-paced environment with deep focus on quality, scalability and architecture
* Provide tactical advice in solving technical issues as well as strategic guidance for the long-term reliability of the systems.
* Play SME role for application development teams to help Cloud, Big Data, Data Lake and Machine Learning application modernization.
* Play an instrumental role in building our state-of-the-art time series data platform that abstract away details and automate as much as possible, so it is easy to set up and operate continuously with very little intervention
* Develop utilities and tools to help the cloud data journey in the process.
* Research specific tools and Support assessment of new product/services across cloud data technology paradigm
* Motivate, engage, coach and provide leadership to a team while building an environment that is conducive to their development and delivery to the best of their ability


**Thoughts**

Reimagining Data Platforms

**Data should be easy to discover and use**


A data pipeline needs to have intelligence built in to abstract away details and automate as much as possible, so it is easy to set up and operate continuously with very little intervention. As a result, data pipelines are fast to build and deploy, fault tolerant, adaptive, and self healing. To do this, we need a single catalog that collects metadata about all data assets and presents the right information to the users depending on their needs.

A unified metadata system can be transformational to how an organization uses the data. Duplicated metadata across many systems becomes inconsistent over time. This causes misunderstanding leading to mistakes in how data is used. A Single Source of Truth for metadata is key to establishing a consistent understanding of data across the organization. Keeping a single source correct, consistent, and high quality is much easier than maintaining multiple copies of metadata spread across various systems. Example DQ tool should query centralized metastore to get any information about the data asset.

all the data users(consumers/producers) should have access to comprehensive metadata about data assets

    - Basic metadata: such as documentation, ownership information, pipelines, source code, sample data, lineage
    - Usage metadata: statistics on who used it, when, popular queries, and artifacts that are used together
    - Quality metadata: tests on the data, when do they run, which ones passed, and aggregate SLA provided by the data
    - Bugs and SLAs: bugs filed against the artifact, incidents, recent alerts, and overall SLA in responding to issues by owners 
    
![image](https://user-images.githubusercontent.com/11326854/154199977-06c2399b-558d-484d-b8eb-992de1a9f581.png)


To maximize the benefit of metadata, a central repository must be built for integrations. This requires an API-centric approach with well-designed, easy-to-use, and reusable APIs that consider various use cases across the tools, beyond UI and governance use cases.
