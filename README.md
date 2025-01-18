# Data Engineering Zoomcamp

## Taking the course

### 2025 Cohort

- **Start**: 13 January 2025
- **Registration link**: https://airtable.com/shr6oVXeQvSI5HuWD
- Materials specific to the cohort: [cohorts/2025/](cohorts/2025/)

### Self-paced mode

All the materials of the course are freely available, so that you
can take the course at your own pace

- Follow the suggested syllabus (see below) week by week
- You don't need to fill in the registration form. Just start watching the videos and join Slack
- Check [FAQ](https://docs.google.com/document/d/19bnYs80DwuUimHM65UV3sylsCn2j1vziPOwzBwQrebw/edit?usp=sharing) if you have problems
- If you can't find a solution to your problem in FAQ, ask for help in Slack

## Syllabus

We encourage [Learning in Public](learning-in-public.md)

> **Note:** NYC TLC changed the format of the data we use to parquet.
> In the course we still use the CSV files accessible [here](https://github.com/DataTalksClub/nyc-tlc-data).

### [Module 1: Containerization and Infrastructure as Code](01-docker-terraform/)

- Course overview
- Introduction to GCP
- Docker and docker-compose
- Running Postgres locally with Docker
- Setting up infrastructure on GCP with Terraform
- Preparing the environment for the course
- Homework

[More details](01-docker-terraform/)

### [Module 2: Workflow Orchestration](02-workflow-orchestration/)

- Data Lake
- Workflow orchestration
- Workflow orchestration with Kestra
- Homework

[More details](02-workflow-orchestration/)

### [Workshop 1: Data Ingestion](cohorts/2025/workshops/dlt.md)

- Reading from apis
- Building scalable pipelines
- Normalising data
- Incremental loading
- Homework

[More details](cohorts/2025/workshops/dlt.md)

### [Module 3: Data Warehouse](03-data-warehouse/)

- Data Warehouse
- BigQuery
- Partitioning and clustering
- BigQuery best practices
- Internals of BigQuery
- BigQuery Machine Learning

[More details](03-data-warehouse/)

### [Module 4: Analytics engineering](04-analytics-engineering/)

- Basics of analytics engineering
- dbt (data build tool)
- BigQuery and dbt
- Postgres and dbt
- dbt models
- Testing and documenting
- Deployment to the cloud and locally
- Visualizing the data with google data studio and metabase

[More details](04-analytics-engineering/)

### [Module 5: Batch processing](05-batch/)

- Batch processing
- What is Spark
- Spark Dataframes
- Spark SQL
- Internals: GroupBy and joins

[More details](05-batch/)

### [Module 6: Streaming](06-streaming/)

- Introduction to Kafka
- Schemas (avro)
- Kafka Streams
- Kafka Connect and KSQL

[More details](06-streaming/)

### [Project](projects)

Putting everything we learned to practice

- Week 1 and 2: working on your project
- Week 3: reviewing your peers

[More details](projects)

## Overview

<img src="images/architecture/arch_v4_workshops.jpg" />

### Prerequisites

To get the most out of this course, you should feel comfortable with coding and command line
and know the basics of SQL. Prior experience with Python will be helpful, but you can pick
Python relatively fast if you have experience with other programming languages.

Prior experience with data engineering is not required.

## Instructors

- [Victoria Perez Mola](https://www.linkedin.com/in/victoriaperezmola/)
- [Alexey Grigorev](https://linkedin.com/in/agrigorev)
- [Michael Shoemaker](https://www.linkedin.com/in/michaelshoemaker1/)
- [Zach Wilson](https://www.linkedin.com/in/eczachly)
- [Will Russell](https://www.linkedin.com/in/wrussell1999/)
- [Anna Geller](https://www.linkedin.com/in/anna-geller-12a86811a/)

Past instructors:

- [Ankush Khanna](https://linkedin.com/in/ankushkhanna2)
- [Sejal Vaidya](https://www.linkedin.com/in/vaidyasejal/)
- [Irem Erturk](https://www.linkedin.com/in/iremerturk/)
- [Luis Oliveira](https://www.linkedin.com/in/lgsoliveira/)
