# Coding Challenge
This coding challenge tests problem-solving, execution, communication, and documentation. Documentation is essential, and the solution should provide specific instructions for building and running it. 

Solution architecture design is more art than a skill, so be creative and have fun.

## Challenge Statement
### Scenario:
Your company is experiencing a rapid growth in user activity, generating a constant stream of data from various sources. This includes website clickstream data, user interactions with a mobile app, and real-time sensor readings from your infrastructure.

### Your Responsibilities:
You are tasked with designing and implementing a real-time data pipeline using Apache Kafka as the central messaging system. This pipeline will ingest data from these diverse sources, process it in real-time, and store it in a scalable cloud data lake (your choice -  AWS, GCP, or Azure). The data lake will serve as the foundation for future analytics and machine learning applications.
* Data Ingestion with Kafka: Design and implement real-time data pipeline using Confluent Kafka topic. You can use Datagen Source connector for sample data.
* Real-time Stream Processing: Develop Kafka consumer that subscribe to the topic and perform necessary transformations on the data stream.
* Cloud Data Lake Integration: Integrate the processed data stream with a cloud data lake solution (e.g., AWS S3, Azure ADLS, GCS bucket) for persistent storage. Utilize appropriate connectors or libraries for seamless data transfer between Kafka and the data lake.
* Scalability and Performance: Design your architecture to handle growing data volumes.
### Note: All cloud resources are to be deployed using Terraform.
---
### Deliverables:
* Technical Documentation (mandatory): A detailed document outlining your design decisions, chosen technologies, and implementation steps.
* Code Samples (if developed): Well-commented code snippets showcasing your Kafka producers, consumers, and data processing logic within the consumers.
* Visual Representation (mandatory): A diagram or flowchart depicting the real-time data pipeline with Kafka at its core.
---
### Evaluation Criteria:
* Completeness of the Architecture: We will assess the overall design of your data pipeline, including Kafka topic structure, data processing within consumers, and integration with the cloud data lake.
* Efficiency and Scalability: Your approach to handling real-time data volume and ensuring the architecture can scale with Kafka will be evaluated.
* Code Quality and Maintainability: Clarity, efficiency, and adherence to best practices will be considered when reviewing the code samples for Kafka producers and consumers.
* Documentation and Communication: Your ability to document design decisions, code functionality, and potential challenges through clear and concise communication will be evaluated.
---
## Summary
