# AWS-Database

 Databases

RDS (MySQL, PostgreSQL, Aurora, SQL Server)

	• Concepts:
		○ RDS: Fully managed relational database service supporting MySQL, PostgreSQL, Aurora, and more.
		○ Aurora: High-performance, scalable database compatible with MySQL and PostgreSQL.
	• Real-Time Example:
		○ An e-commerce platform uses RDS MySQL for transactional data such as order and customer information.
	• Use Cases:
		○ RDS: Scalable, managed databases for web apps and data-driven platforms.
		○ Aurora: Applications requiring high availability and low latency.
	• Secondary Options: DynamoDB for NoSQL, Google Cloud SQL, Azure SQL.

DynamoDB and ElastiCache

	• Concepts:
		○ DynamoDB: Managed NoSQL database for low-latency applications.
		○ ElastiCache: In-memory data store (Redis or Memcached) for caching and fast retrieval.
	• Real-Time Example:
		○ DynamoDB: A social media app stores user session data for real-time access.
		○ ElastiCache: A ride-sharing app caches frequently queried location data.
	• Use Cases:
		○ DynamoDB: Real-time apps, serverless architectures.
		○ ElastiCache: Database query optimization, session caching.
	• Secondary Options: MongoDB Atlas, Redis Labs.

Redshift

	• Concepts:
		○ Redshift: A data warehouse solution for OLAP workloads.
	• Real-Time Example:
		○ A retail company uses Redshift for analyzing historical sales data and generating business intelligence reports.
	• Use Cases:
		○ Big data analytics, reporting, and dashboards.
	• Secondary Options: Snowflake, BigQuery.

Amazon Neptune, QLDB, Timestream

	• Concepts:
		○ Neptune: Managed graph database for relationships (e.g., social networks).
		○ QLDB: Ledger database for immutable, verifiable transaction logs.
		○ Timestream: Time-series database for IoT and metrics.
	• Real-Time Example:
		○ Neptune: A dating app models relationships and friend connections.
		○ QLDB: A financial system logs immutable transaction histories.
		○ Timestream: Monitoring temperature data from IoT sensors.
	• Use Cases:
		○ Neptune: Social networks, recommendation engines.
		○ QLDB: Financial transactions, supply chain tracking.
		○ Timestream: IoT data, telemetry.
	• Secondary Options: Azure Cosmos DB (graph), MongoDB (document).
