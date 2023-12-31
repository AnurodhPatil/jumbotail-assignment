# Jumbotail Assignment-2

## Problem Description
This assignment involves developing a system to track user journeys in an e-commerce application and analyze user behavior at various stages of the application funnel. The goal is to efficiently handle a large volume of events generated by daily active users, track the percentage of users at each stage of the user journey, and evaluate the performance of different cities based on user engagement.

## Solution Overview
The solution uses a data engineering approach, combining data processing, real-time analytics, and database management to create a system that analyzes and tracks user journeys in the e-commerce application.

### Technology Stack
- Programming Language: Python
- Web Framework: Flask
- Database: Oracle
- In-Memory Model: Apache Spark (PySpark)

## Getting Started

### Prerequisites
- Python should be installed on the system.
- Install the required libraries by running `pip install flask kafka-python pyspark cx_Oracle` in your command prompt or terminal.
- Install and configure Oracle Database on the system.
- Set up Apache Kafka and create the necessary topics to handle the event streams.

### Setup Instructions
1. Clone the repository:
git clone <repository-url>

markdown
Copy code

2. Install Dependencies:
pip install -r requirements.txt

vbnet
Copy code

3. Configure Oracle Database:
- Create a new schema or tablespace to store the event data.
- Note down the connection details (e.g., host, port, username, password) for accessing the Oracle database.

4. Set Up Apache Kafka:
- Install and configure Apache Kafka on the system.
- Create the required Kafka topics to handle event streams.

5. Running the Solution:
- Start the Flask application by running `python app.py`.
- Simulate user journeys by running the Event Producer class with multithreading.
- Monitor system performance, response times, and data consistency.
- Verify that events are properly pushed to Kafka, consumed by the Queue Consumer, and stored in the Oracle database.
- Perform queries on the Oracle database to retrieve necessary data for generating desired output.

## Conclusion
In conclusion, this solution provides a system for tracking user journeys in an e-commerce application. It utilizes technologies such as Python, Flask, Apache Kafka, PySpark, and Oracle Database to capture and analyze user behavior, calculate percentages at each stage of the user journey, and evaluate city performance. This solution enables data-driven insights for improving user engagement and overall application performance.

