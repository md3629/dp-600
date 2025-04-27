# Transitioning from MCSE: Data Management and Analytics to Microsoft Certified: Fabric Analytics Engineer Associate

This guide provides detailed steps to transition your skills from **MCSE: Data Management and Analytics** to the **Microsoft Certified: Fabric Analytics Engineer Associate** certification and prepares you for the new exam.

---

## 1. Understand the Certification Path

The **Fabric Analytics Engineer Associate** certification validates your expertise in **Microsoft Fabric**, focusing on cloud-based data engineering, storage, visualization, and advanced security. Key focus areas include:

- Ingesting data from multiple sources.
- Transforming and modeling data for analytics.
- Visualizing data with **Power BI**.
- Optimizing data performance and security.

The exam for this certification is **Exam DP-600T00**.

-

## 2. Key Skills Transition Guide

### 2.1 Maintain a Data Analytics Solution (25–30%)

- **Implement security and governance**:
  - Implement **workspace-level access controls**.
  - Implement item-level access controls, including **row-level**, **column-level**, **object-level**, and **file-level** access.
  - Apply sensitivity labels to items.
  - Endorse items.

- **Maintain the analytics development lifecycle**:
  - Configure version control for a workspace.
  - Create and manage a **Power BI Desktop project (.pbip)**.
  - Create and configure **deployment pipelines**.
  - Perform **impact analysis** of downstream dependencies from lakehouses, data warehouses, dataflows, and semantic models.
  - Deploy and manage semantic models using the **XMLA endpoint**.
  - Create and update reusable assets, including **Power BI template (.pbit)** files, **Power BI data source (.pbids)** files, and shared semantic models.

---

### 2.2 Prepare Data (45–50%)

- **Get Data**

  - Create a data connection.
  - Discover data using **OneLake Data Hub** and **Real-Time Hub**.
  - Ingest or access data as needed.
  - Choose between a **lakehouse**, **warehouse**, or **eventhouse**.
  - Implement **OneLake integration** for eventhouse and semantic models.

- **Transform Data**

  - Create views, functions, and stored procedures.
  - Enrich data by adding new columns or tables.
  - Implement a **star schema** for a lakehouse or warehouse.
  - Denormalize data.
  - Aggregate data.
  - Merge or join data.
  - Identify and resolve duplicate data, missing data, or null values.
  - Convert column data types.
  - Filter data.

- **Query and Analyze Data**

  - Select, filter, and aggregate data using the **Visual Query Editor**.
  - Select, filter, and aggregate data using **SQL**.
  - Select, filter, and aggregate data using **KQL**.

---

### 2.3 Implement and Manage Semantic Models (25–30%)

- **Design and Build Semantic Models**

  - Choose a storage mode.
  - Implement a **star schema** for a semantic model.
  - Implement relationships, such as **bridge tables** and **many-to-many relationships**.
  - Write calculations using **DAX variables** and functions (e.g., iterators, table filtering, windowing, and information functions).
  - Implement **calculation groups**, **dynamic format strings**, and **field parameters**.
  - Identify use cases for and configure large semantic model storage formats.
  - Design and build **composite models**.

- **Optimize Enterprise-Scale Semantic Models**

  - Implement performance improvements in queries and report visuals.
  - Improve DAX performance.
  - Configure **Direct Lake**, including default fallback and refresh behavior.
  - Implement **incremental refresh** for semantic models.

---

## 3. Study Resources and Training

### 1. Microsoft Learn (Free)
Microsoft offers free courses to build foundational knowledge.

[Microsoft Fabric Analytics Engineer](https://learn.microsoft.com/en-us/training/courses/dp-600t00)
- [Get Started with Microsoft Fabric](https://learn.microsoft.com/en-us/training/paths/get-started-fabric/)
- [Implement a data warehouse with Microsoft Fabric](https://learn.microsoft.com/en-us/training/paths/work-with-data-warehouses-using-microsoft-fabric/)
- [Work with semantic models in Microsoft Fabric](https://learn.microsoft.com/en-us/training/paths/work-semantic-models-microsoft-fabric/)
- Administer and govern Microsoft Fabric
- [Ingest data with Microsoft Fabric](https://learn.microsoft.com/en-us/training/paths/ingest-data-with-microsoft-fabric/)
---
- [Get Started with Microsoft Fabric](https://learn.microsoft.com/en-us/training/paths/get-started-fabric/)

  - [Introduction to end-to-end analytics using Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/introduction-end-analytics-use-microsoft-fabric/)
    - [What is Microsoft Fabric admin?](https://learn.microsoft.com/en-us/fabric/admin/microsoft-fabric-admin)

  - [Get started with lakehouses in Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/get-started-lakehouses/)
    - [How to create an Apache Spark job definition in Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/create-spark-job-definition)
    - [OneLake shortcuts](https://learn.microsoft.com/en-us/fabric/onelake/onelake-shortcuts)
    - [Data Engineering documentation in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/)
    - [Exercise - Create a Microsoft Fabric lakehouse](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/01-lakehouse.html)

  - [Use Apache Spark in Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/use-apache-spark-work-files-lakehouse/)
    - [Capacity administration settings for Data Engineering and Data Science](https://learn.microsoft.com/en-us/fabric/data-engineering/capacity-settings-overview)
    - [Configuring starter pools in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/capacity-settings-overview)
    - [How to create custom Spark pools in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/create-custom-spark-pools)
    - [Apache Spark Runtimes in Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/runtime)
    - [Create, configure, and use an environment in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/create-and-use-environment)
    - [Native execution engine for Fabric Spark](https://learn.microsoft.com/en-us/fabric/data-engineering/native-execution-engine-overview?tabs=sparksql)
    - [High concurrency mode in Apache Spark for Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/high-concurrency-overview)
    - [Configure and manage data engineering and data science settings for Fabric capacities](https://learn.microsoft.com/en-us/fabric/data-engineering/capacity-settings-management)
    - [Analyze data with Apache Spark in Fabric](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/02-analyze-spark.html)
    - [Spark SQL, DataFrames and Datasets Guide](https://spark.apache.org/docs/latest/sql-programming-guide.html)
   
  - [Work with Delta Lake tables in Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/work-delta-lake-tables-fabric/)
    - [Structured Streaming Programming Guide](https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html)
    - [Exercise - Use delta tables in Apache Spark](https://learn.microsoft.com/en-us/training/modules/work-delta-lake-tables-fabric/6-exercise-delta-tables)
   
  - [Orchestrate processes and data movement with Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/use-data-factory-pipelines-fabric/)
    - [Activity overview](https://learn.microsoft.com/en-us/fabric/data-factory/activity-overview)
    -[Exercise - Ingest data with a pipeline](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/04-ingest-pipeline.html)

  - [Ingest Data with Dataflows Gen2 in Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/use-dataflow-gen-2-fabric/)
    - [Power Query documentation](https://learn.microsoft.com/en-us/power-query/)
    - [Exercise - Create and use a Dataflow Gen2 in Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/use-dataflow-gen-2-fabric/5-exercise)
   
  - [Get started with data warehouses in Microsoft Fabric](https://learn.microsoft.com/en-gb/training/modules/get-started-data-warehouse/)
    - [Understand star schema and the importance for Power BI](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema)
    - [Clone table in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-warehouse/clone-table)
    - [Tutorial: Clone a table with T-SQL in a Warehouse](https://learn.microsoft.com/en-us/fabric/data-warehouse/tutorial-clone-table)
    - [Tables in data warehousing in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-warehouse/tables)
    - [Diagram view](https://learn.microsoft.com/en-us/power-query/diagram-view)
  - [Get started with Real-Time Intelligence in Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/get-started-kusto-fabric/)
    - [Supported sources for Fabric Real-Time hub](https://learn.microsoft.com/en-us/fabric/real-time-hub/supported-sources)
    - [Process event data with event processor editor](https://learn.microsoft.com/en-us/fabric/real-time-intelligence/event-streams/process-events-using-event-processor-editor?pivots=enhanced-capabilities)
    - [Add and manage a destination in an eventstream](https://learn.microsoft.com/en-us/fabric/real-time-intelligence/event-streams/add-manage-eventstream-destinations?pivots=enhanced-capabilities)
    - [Kusto Query Language overview](https://learn.microsoft.com/en-us/kusto/query/?view=microsoft-fabric)
    - [Create a Real-Time Dashboard](https://learn.microsoft.com/en-us/fabric/real-time-intelligence/dashboard-real-time-create)
    - [Visualize data in a Power BI report](https://learn.microsoft.com/en-us/fabric/real-time-intelligence/create-powerbi-report)
    - [What is Activator?](https://learn.microsoft.com/en-us/fabric/real-time-intelligence/data-activator/activator-introduction)
    - [Exercise - Explore Real-Time Intelligence in Fabric](https://learn.microsoft.com/en-us/training/modules/get-started-kusto-fabric/5-exercise-use-kusto-query-data-onelake)
    - [Real-Time Intelligence documentation in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/real-time-intelligence/)
   
  - [Get started with data science in Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/get-started-data-science-fabric/)
    - [Exercise - Explore data science in Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/get-started-data-science-fabric/5-exercise-use-notebook)
   
  - [Administer a Microsoft Fabric environment](https://learn.microsoft.com/en-us/training/modules/administer-fabric/)
    - [What is Microsoft Fabric admin?](https://learn.microsoft.com/en-us/fabric/admin/microsoft-fabric-admin)
    - [Microsoft Power BI Cmdlets for Windows PowerShell and PowerShell Core](https://learn.microsoft.com/en-us/powershell/power-bi/overview?view=powerbi-ps)
   
- [Work with semantic models in Microsoft Fabric](https://learn.microsoft.com/en-us/training/paths/work-semantic-models-microsoft-fabric/)
  - [Add measures to Power BI Desktop models](https://learn.microsoft.com/en-us/training/modules/dax-power-bi-add-measures/)
  - [Design scalable semantic models](https://learn.microsoft.com/en-us/training/modules/design-scalable-semantic-models/)
    - [Data reduction techniques for Import modeling](https://learn.microsoft.com/en-us/power-bi/guidance/import-modeling-data-reduction)
    - [DirectQuery model guidance in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/guidance/directquery-model-guidance)
    - [Composite model guidance in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/guidance/composite-model-guidance)
    - [Large semantic models in Power BI Premium](https://learn.microsoft.com/en-us/power-bi/enterprise/service-premium-large-models)
    - [Incremental refresh and real-time data for semantic models](https://learn.microsoft.com/en-us/power-bi/connect-data/incremental-refresh-overview)
    - [Advanced incremental refresh and real-time data with the XMLA endpoint](https://learn.microsoft.com/en-us/power-bi/connect-data/incremental-refresh-xmla)
    - [Create calculation groups](https://learn.microsoft.com/en-us/power-bi/transform-model/calculation-groups)
    - [Let report readers use field parameters to change visuals (preview)](https://learn.microsoft.com/en-us/power-bi/create-reports/power-bi-field-parameters)
    - [Create dynamic format strings for measures](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-dynamic-format-strings)
    - [Exercise - Design a scalable semantic model](https://learn.microsoft.com/en-us/training/modules/design-scalable-semantic-models/7-exercise)
   
  - [Optimize a model for performance in Power BI](https://learn.microsoft.com/en-us/training/modules/optimize-model-power-bi/)
    - [Data reduction techniques for Import modeling](https://learn.microsoft.com/en-us/power-bi/guidance/import-modeling-data-reduction)
    - [DirectQuery model guidance in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/guidance/directquery-model-guidance)
    - [DirectQuery limitations](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-directquery-about#implications-of-using-directquery)
    - [DirectQuery model guidance in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/guidance/directquery-model-guidance)

  - [Create and manage Power BI assets](https://learn.microsoft.com/en-us/training/modules/create-manage-power-bi-assets/)
    - [What is an on-premises data gateway?](https://learn.microsoft.com/en-us/data-integration/gateway/service-gateway-onprem)
    - [Create and use report templates in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-templates)
    - [Power BI Desktop projects (PREVIEW)](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-overview)
    - [What is lifecycle management in Microsoft Fabric?](https://learn.microsoft.com/en-us/fabric/cicd/cicd-overview)
    - [Endorsement overview](https://learn.microsoft.com/en-us/fabric/governance/endorsement-overview)
    - [Semantic model connectivity with the XMLA endpoint]((https://learn.microsoft.com/en-us/power-bi/enterprise/service-premium-connect-tools)
    - [Exercise: Create reusable Power BI assets](https://learn.microsoft.com/en-us/training/modules/create-manage-power-bi-assets/5-exercise-create-reusable)

- 
- [Labs](https://github.com/MicrosoftLearning/mslearn-fabric)
- [Microsoft Fabric fundamentals documentation](https://learn.microsoft.com/en-us/fabric/fundamentals/)
- Lakehouses and Synapse Analytics tutorials.
- Power BI data modeling and visualization.

### 2. Training Courses (Instructor-led or Self-paced)
Consider official courses like **DP-600T00** for in-depth training on:

- [Microsoft Fabric Analytics Engineer](https://learn.microsoft.com/en-us/training/courses/dp-600t00)
- Fabric data integration and pipelines.
- Analytics and performance optimization.
- **OneLake** and **Delta Lake** storage management.

### 3. Hands-on Practice
Set up a Microsoft Fabric trial (if available) or use your organization’s capacity to:

- Build data pipelines to integrate multiple data sources.
- Create and query a **Synapse Lakehouse**.
- Develop a **Power BI** report with real-time data connections.

---

## 4. Certification Exam Details

| Exam Code            | DP-600 (Fabric Analytics Engineer Associate) |
|----------------------|----------------------------------------------|
| Number of Questions  | ~40–60 questions                             |
| Question Types       | Multiple choice, case studies, performance-based scenarios. |
| Duration             | ~120–150 minutes                             |
| Passing Score        | 700/1000                                     |
| Exam Fee             | $165 USD (varies by location)                |

---

