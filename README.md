# PhonePe Transaction Insights
An end-to-end Data Engineering and Business Analytics project built using the PhonePe Pulse dataset. This project extracts raw JSON data, transforms it into structured datasets, stores it in a MySQL database, performs SQL-based business analysis, and visualizes insights through an interactive Streamlit dashboard.

The project begins with extracting raw nested JSON data from the PhonePe Pulse GitHub repository. Since the dataset is stored in hierarchical folder structures, Python is used to automate the extraction, parsing, and transformation process. The transformed data is then converted into structured tabular formats using Pandas DataFrames and loaded into a MySQL relational database for efficient storage and querying.

## Project Overview

The PhonePe Transaction Insights project demonstrates a complete ETL and analytics workflow using real-world digital payment data from the PhonePe Pulse GitHub Repository.

The project focuses on:
- Extracting nested JSON data
- Transforming and cleaning datasets using Python
- Designing relational database schemas in MySQL
- Performing SQL-based business analysis
- Building interactive dashboards with Streamlit
- Generating business insights from transaction, user, and insurance data

This project simulates how real-world fintech companies analyze digital payment ecosystems for decision-making and strategic growth.

## Technology Stack
- Category	Tools & Technologies
- Programming Language	Python 3.x
- Data Processing	Pandas, NumPy
- Database	MySQL, SQLAlchemy, PyMySQL
- Visualization	Plotly, Matplotlib
- Dashboard	Streamlit
- Development Environment	JupyterLab, Anaconda
- Data Source	PhonePe Pulse Dataset

## Project Architecture

The project follows a complete data pipeline:

### Data Extraction
- Raw JSON files are extracted from the PhonePe Pulse dataset.
### Data Transformation
- Nested JSON structures are converted into clean tabular DataFrames.
### Database Design
- Multiple MySQL tables are created for transactions, users, and insurance data.
### Data Loading
- Cleaned datasets are inserted into MySQL using SQLAlchemy.
### SQL Business Analysis
- 12 business case queries are executed for analytical insights.
### Dashboard Development
- Interactive Streamlit dashboard built with filters, KPIs, and visualizations.
### Insight Generation
- Key findings and business recommendations are derived from the analysis.

## Database Schema

The database contains 9 structured tables categorized into:

- Aggregated Tables
- aggregated_transaction
- aggregated_user
- aggregated_insurance
- Map Tables
- map_transaction
- map_user
- map_insurance
- Top Tables
- top_transaction
- top_user
- top_insurance

These tables store transaction, user engagement, district-level, pincode-level, and insurance-related analytics data.

## Business Case Analysis

The project includes 12 SQL business case analyses, such as:

- Top states by transaction amount
- Top states by transaction count
- Category-wise payment analysis
- Year-wise and quarter-wise trends
- District-level transaction insights
- User engagement analysis
- Insurance growth analysis
- State-wise growth comparison

### These analyses help identify:

- High-performing regions
- User engagement patterns
- Growth opportunities
- Regional transaction behavior
- Insurance adoption trends

## Streamlit Dashboard Features

The project includes a fully interactive Streamlit dashboard with:

### Sidebar Filters
- Year filter
- Quarter filter
- State selector
### KPI Cards
- Total Transaction Amount
- Total Transactions
- Top Performing State
- Average Transaction Amount
### Dashboard Sections
- Transaction Analysis
- User Analysis
- Insurance Analysis
- Top Districts & Pincodes
  
## Insights & Recommendations

Interactive visualizations are created using Plotly charts for better business interpretation.

### Key Insights
- Transaction Insights
- Few states contribute a major portion of transaction value.
- High transaction frequency does not always indicate high transaction amount.
- Seasonal and yearly trends reveal changing digital payment behavior.
### User Insights
- Some states show strong registrations but low app engagement.
- Device brand analysis helps understand user accessibility patterns.
### Insurance Insights
- Insurance adoption is concentrated in selected states.
- Growth trends indicate increasing financial product awareness.
### Geographic Insights
- District and pincode-level analysis identifies micro-market opportunities.
- Regional hotspots support targeted business expansion strategies.
