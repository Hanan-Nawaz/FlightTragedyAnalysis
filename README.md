# Flight Tragedy Analysis

## Overview

**Flight Tragedy Analysis** is a comprehensive data analysis project focused on examining aviation accidents and incidents from 1905 to 2009. This project provides users with valuable insights into historical plane crashes and their associated data.

### Core Features

1. **Extensive Data Repository**: The project houses a rich dataset containing detailed information about plane crashes, including date, time, location, operator, flight number, route, aircraft type, registration, casualties, and more.

2. **Data Transformation and Storage**: The data is meticulously transformed and stored in a structured manner to enable efficient analysis, including data normalization, handling missing values, and ensuring data integrity.

3. **Robust ETL Processes**: Python scripts are utilized for Extract, Transform, Load (ETL) operations, facilitating the transfer of data from diverse sources to Amazon Redshift, a high-performance, fully managed data warehouse.

4. **Interactive Power BI Dashboard**: A dynamic Power BI dashboard has been crafted to offer users an intuitive interface for exploring and visualizing the dataset. Users can interact with the data to answer critical questions related to plane crashes.

5. **In-Depth Analysis**: The project empowers users to gain insights by addressing questions such as identifying peak years for plane crashes, determining which armed forces experienced the most losses, identifying common reasons for crashes, assessing companies with the highest incident rates, examining survival statistics, ground casualties, and pinpointing countries with the highest crash occurrences.

## Project Process

This repository contains the code and data for the FlightTragedyAnalysis Data Engineering Project. The project involves analyzing airplane crash data from Kaggle, building a data model, creating a relational database, performing ETL (Extract, Transform, Load) processes, storing the data in Amazon S3, and finally, creating a Power BI dashboard for comprehensive analysis.

### 1. Data Acquisition

- Downloaded the dataset from Kaggle, which contains historical airplane crash data from 1908 to 2009.

### 2. Data Modeling

- Created a data model to define the structure and relationships within the dataset.

![ERD](https://previews.dropbox.com/p/thumb/ACAeb33WgNiyFWR4EHU2QMtAsJIUl6-vdzCnQXprfyFoyAsmU_IuS1KuMNuDqgPFSmI1ba3haYBEU4Qz8VnEmPPeBR2PeAuZm-Or-5q3AjzzJvO_MQQNv1OkU0s0v5ZRUv-hzZFuXY6GgUyNA34v5-IP0MM0W62-17VdoR1nzlqkboUTnglYpg5s0-j_ABvtTg86FLgTpryQJ9_2DdrsoKf9JBzZalfxq7t_XID27ANs6-BFatSQ5W-cBINPoSHi8aaxzDcMfW_75K-dJCqHoWCp75Wq5qdRxD8SjvFp7gjwu5ZWumt5-TnPaApTqs4pV8FjNdMoGRaNVjyFU0Jyf1gY/p.png)

### 3. Database Creation

- Established a relational database (e.g., Amazon Redshift) to efficiently store and manage the structured data.

### 4. Data Storage

- Uploaded the processed dataset into an object store on Amazon S3 for easy access and scalability.

### 5. ETL Process

- Developed Python scripts for the ETL process to:
  - Extract data from the source dataset
  - Transform and clean the data
  - Load the data into the Amazon Redshift database for analysis

### 6. Power BI Dashboard

- Created a Power BI dashboard to visualize and analyze the airplane crash data, answering questions like:
  - Which year had the highest number of plane crashes?
  - Which armed forces experienced the most plane losses?
  - What is the most common reason for crashes?
  - Which company has the highest number of crashes?
  - How many people survived the crashes?
  - How many people on the ground died in these incidents?
  - In which country did most plane crashes occur?

## Technology Stack

- **ETL**: Python (Pandas), Amazon Redshift, SQL
- **Database**: Amazon Redshift
- **Data Storage**: Amazon S3
- **Visualization**: Power BI
- **Version Control**: Git, GitHub


## Repository Structure

- `data/`: Contains the downloaded dataset and any intermediate data files.
- `scripts/`: Includes Python scripts for data extraction, transformation, and loading (ETL).
- `database/`: Contains scripts or documentation related to the database setup.
- `power_bi/`: Stores files related to the Power BI dashboard.
- `README.md`: You are here, providing an overview of the project.

## Getting Started

To replicate this project, follow these steps:

1. Download the dataset from Kaggle or provide a link to the dataset you are using.

2. Set up your database (e.g., Amazon Redshift) and configure the necessary credentials.

3. Use the ETL scripts to process and load the data into your database.

4. Create a Power BI dashboard using the provided data to answer critical questions related to airplane crashes.

## Data Source

- Dataset: [Kaggle - Historical Plane Crashes](https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908)

## Contributors

- [Abdul Hanan Nawaz](https://www.github.com/Hanan-Nawaz)
- Associate Data Engineer 

Feel free to contribute to this project or contact the contributors for more information.

## License

This project is licensed under the [MIT License](LICENSE).

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://hanannawaz.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdulhanan0/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/hanannawaz0/)


<h3 align="left">Let's Talk about your project 😃 </h3>
<p align="center">
<a href="https://www.upwork.com/freelancers/~01da1397cb42c5b105"><img src="https://img.shields.io/badge/-Abdul%20Hanan%20Nawaz-6fda44?style=flat&logo=upwork&logoColor=white"/></a>
<a href="https://www.fiverr.com/abdulhanan90"><img src="https://img.shields.io/badge/-Abdul%20Hanan%20Nawaz-00b22d?style=flat&logo=Fiverr&logoColor=white"/></a>
