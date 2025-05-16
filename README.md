Global Cancer Patients (2015–2024) Database
📋 Project Title
Global_Cancer_Patients_2015_2024 – A Relational Database for Cancer Patient Records

📌 Description
This project involves the design and implementation of a full-featured MySQL database using real-world cancer patient data obtained from Kaggle. The database captures global patient records from 2015 to 2024 and is structured to support queries for insights such as:

Cancer type and frequency

Survival rates

Gender/age distribution

Country-based statistics

The design includes tables for patient demographics, cancer types, treatments, outcomes, and countries, ensuring data normalization and integrity through proper constraints and relationships.

⚙️ How to Run/Setup the Project
Prerequisites
MySQL installed (v8.0+ recommended)

MySQL Workbench (optional but recommended)

Steps to Setup:
Download or clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/Global_Cancer_Patients_2015_2024.git
Open MySQL Workbench or any MySQL client.

Run the SQL file:

Open global_cancer_patients.sql provided in the repository.

Execute the file to create the database and tables.

(Optional) Import the CSV file:

Load data using LOAD DATA INFILE or import using MySQL Workbench.

Example:

sql
Copy
Edit
LOAD DATA INFILE '/path/to/Global_Cancer_Patients.csv'
INTO TABLE patients
FIELDS TERMINATED BY ','
ENCLOSED BY '"'
LINES TERMINATED BY '\n'
IGNORE 1 ROWS;



📊 Entity Relationship Diagram (ERD)

Or view it online: Link to ERD (e.g., dbdiagram.io)

🗂️ Repository Structure
graphql
Copy
Edit
Global_Cancer_Patients_2015_2024/
│
├── global_cancer_patients.sql       # SQL file with CREATE TABLE statements
├── Global_Cancer_Patients.csv       # Original dataset from Kaggle
├── README.md                        # Project documentation
└── ERD.png                          # ERD image (or PDF)


