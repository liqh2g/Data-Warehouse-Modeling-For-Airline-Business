# Airline Company Data Warehouse Project

## Overview
This repository contains code for the Data Warehouse project designed for an airline business.
- The project aims to enable the executive management to analyze current business processes and identify new opportunities through a structured Data Warehouse that consolidates data from various sources.
- This enables efficient analytical reporting and business intelligence for improving service delivery and expanding the company's market reach.

## Project Milestones
- Data Wareouse Model (7 Business Processes Modeled on 2 Deliverables)
- PowerBI Dashboard Build on top of the DWH Model

## Features
The Data Warehouse incorporates several key features:
- **Ticketing Transactions**: Analyzes sales performance, customer booking behaviors, and revenue management.
- **Frequent Flyers**: Tracking flyer behaviors and booking patterns for company's frequent flyers.
- **Customer Care**: Focuses on enhancing customer satisfaction by managing inquiries and feedback.
- **Flights**: Supports performance analysis and operational planning for flight operations.
- **Loyalty Program**: Manages the airline's loyalty program over all partnered companies.
- **Expenses**: Analyzes company's operational Expenses across different business processes.
- **Revenue**: Analyzes company's revenue over time.

## DWH MODEL

### First Delivery

![Model Delivery 1](link-to-image)

### Second Delivery

![Model Delivery 2](link-to-image)

### Data Marts (Sample)

#### Reservations

![Reservations](link-to-image)

#### Customer Care

![Customer Care](link-to-image)

## Analysis with Power BI


## Installation
To set up the project on your local machine for development and testing purposes, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/liqh2g/Data-Warehouse-Modeling-For-Airline-Business.git
   ```
2. Set up for configuring SQL server on docker, run command:
   ```bash
   docker compose up -d
   ```

## Usage
The project uses SQL server DBMS built on Docker. Ensure you have docker installed and configured on your system. Here are the steps to import the project and run it:
1. Execute the SQL scripts found in the `Schema Creation.SQL` to set up the database schema.
2. Use the `Populate.py` script to generate sample data.
3. Populate the data into your database using the scripts in the `Data Population` folder.
4. Utilize SQL queries or BI tools to analyze the data.