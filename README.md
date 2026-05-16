# Initiative for Urban Mobility & Logistics Analytics (NorthStar).
# Overview
The project identifies inefficiencies in NorthStar Urban Mobility and Logistics, a multi-service transport and delivery company.
The company services such as shuttle transport, last-mile delivery, EV charging, warehouse dispatch and the mobile platform.

# With the rising demand, NorthStar is facing rising:

- Failure and delay in delivery.
- Customer complaints
- Operating costs that are higher than revenue growth.
- The problem is that there are separate data systems, and structured relational data and semi-structured platform data are not connected.

# Project Objective
This project aims at designing an integrated analytics solution that:

Comprehends main operational inefficiencies
In addition to the above, analyse patterns of failures in hubs and zones
Responds to customer complaints and financial loss
Investigates relationships within operational factors such as drivers, routes, incidents
Builds a NoSQL database to store complicated event-driven data

# Key Research Questions
1. What are the top failure percentages and what are the causes of those failures in hubs and zones?
2. Are there any service quality implications of driver behaviour (manual route overrides)?
3. Which customers create reoccurring failures and compensation?
4. Are there any indicators that are able to predict failure in delivery or severity of incident?

# Technologies Used
SQL query, statistical analysis, visualisation, R (sqldf, dplyr, ggplot2)
Python → Data processing and transformation
Consuming data via the NoSQL database MongoDB Atlas.Consuming via NoSQL database design MongoDB Atlas.
Google Colab → Development environment
The project structure and version control is demonstrated using GitHub.Version Control and Project structure using GitHub.

# Workflow
1. SQL Analysis (R)
The SQL queries that are run under sqldf.The SQL queries run under sqldf.
Captures failure rates, delays and service blockages
2. Statistical Analysis (R)
Manipulating data with dplyr
Visualisation using ggplot2
Sees patterns and areas that need improvement
3. Data Processing (Python)
Data cleaning and transformation
Additional analysis and charting
4. Design of NoSQL Database (MongoDB)
Document-based modelling for:
Complaints
Deliveries & incidents
App event sessions
Optimised to support flexible data, nested, and event-driven data.

# Key Insights (Summary)
The failure rate is much higher in the central zone hubs.
There are differences in operational inefficiencies in each hub and zone
Deliveries which cause a complaint are highly correlated with complaints.
Platform issues are consequential monetary losses.
When data is split across multiple tables and fragments, visibility and decision making is impeded.

# Solution Approach
The project combines:
Structured data analysis: relational analysis (SQL)
To gain deeper insights, a statistical modelling (R) is used.
Flexible and scalable due to Python processing.
NoSQL (MongoDB), for complex data.
With this blend of the two, an overall picture of operations can be obtained and decisions made based on data.

# Notes
The data is uploaded either from Google Drive or from the /data folder
You can use each notebook separately.
Implements NoSQL in the cloud with MongoDB Atlas.

# Conclusion
Overall, this project illustrates a case study on how the integration of SQL, R, Python, and NoSQL technologies enhance the solution of real-world data challenges by making fragmented systems more manageable, efficient, and effective.
