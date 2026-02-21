# ecom_brazilian_datapipeline

Project Introduction

This project demonstrates the design and implementation of a complete end-to-end Data Engineering pipeline using the Brazilian E-Commerce Public Dataset (Olist dataset). The goal of this project is to simulate a real-world production-grade architecture that transforms transactional (OLTP) data into an analytical (OLAP) data warehouse optimized for business intelligence and reporting.

This project covers the full lifecycle of data engineering:
	•	Designing a normalized OLTP database schema
	•	Implementing transactional tables with constraints and indexing
	•	Extracting data into a staging layer
	•	Applying business transformations and data cleaning
	•	Building a dimensional star schema for OLAP
	•	Preparing the system for reporting and analytics


Project Objective

The primary objective of this project is to:
	1.	Design a scalable OLTP system that represents e-commerce transactional backend.
	2.	Transform normalized transactional data into a dimensional model.
	3.	Build an OLAP star schema optimized for reporting and aggregation.
	4.	Demonstrate core Data Engineering concepts such as:
	        •   Data modeling (3NF → Star Schema)
	        •	Surrogate key generation
	        •	Slowly Changing Dimensions (SCD)
	        •	Fact and dimension table design
	        •	Data validation and reconciliation
	        •	Incremental loading strategies

High-Level Architecture
The project follows a classic modern data architecture pattern:

                OLTP (Transactional Database)
                        ↓
                Staging Layer (Raw Extraction)
                        ↓
                Transformation Layer (Business Logic)
                        ↓
                OLAP Data Warehouse (Star Schema)
                        ↓
                Analytics / BI Reporting



🚀 Key Learning Outcomes

In real-world organizations:
	•	OLTP systems are optimized for fast inserts, updates, and operational queries.
	•	OLAP systems are optimized for aggregations, reporting, and business intelligence.
	•	Directly querying OLTP systems for analytics causes performance bottlenecks.
	•	Therefore, companies build dedicated analytical warehouses.

This project demonstrates how to bridge the gap between operational data and analytical insights. By completing this project, the following Data Engineering skills are demonstrated:
	•	Relational database design (3NF modeling)
	•	Dimensional modeling (Star Schema)
	•	Fact and Dimension design principles
	•	Handling transactional granularity
	•	Designing scalable analytics systems
	•	Preparing data for BI tools


📊 Business Questions This System Can Answer

Once transformed into OLAP, the system can answer:
	•	What is the monthly revenue trend?
	•	Which product categories generate the highest revenue?
	•	Which sellers perform best by region?
	•	What is the average delivery time?
	•	How do payment types impact order value?
	•	What is customer purchase behavior over time?


🏁 Project Scope

This project focuses on:
	•	Data modeling
	•	Transformation logic
	•	Warehouse design
	•	Performance optimization principles

Optional extensions include:
	•	Real-time CDC implementation
	•	Streaming ingestion using Kafka
	•	Automation using Airflow
	•	Cloud deployment (AWS / Snowflake / GCP)
