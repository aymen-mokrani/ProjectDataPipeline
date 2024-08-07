## Overview

ProjectDataPipeline is a data integration project that leverages multiple tools and technologies to facilitate seamless data transfer between PostgreSQL databases. The project utilizes Airbyte for data integration, Airflow for orchestration, and dbt for data transformation, all within a Docker Compose environment.

## Features

Data Integration: Use Airbyte to extract and load data from one PostgreSQL database to another.
Orchestration: Airflow orchestrates the data integration tasks using Directed Acyclic Graphs (DAGs).
Scheduling: Cron jobs are used to schedule recurring data integration tasks.
Data Transformation: dbt (data build tool) is employed to organize and facilitate SQL queries and transformations using macros and Jinja templates.
Containerization: The entire setup is containerized using Docker Compose for easy deployment and management.
