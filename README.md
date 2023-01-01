# Simple ETL With Pandas
According to IBM, ETL, which stands for extract, transform and load, is a data integration process that combines data from multiple data sources into a single, consistent data store that is loaded into a data warehouse or other target system.

### Extract
During data extraction, raw data is copied or exported from source locations to a staging area. Data management teams can extract data from a variety of data sources, which can be structured or unstructured.

### Transform
In the staging area, the raw data undergoes data processing. Here, the data is transformed and consolidated for its intended analytical use case. This phase can involve the following tasks:

- Filtering, cleansing, de-duplicating, validating, and authenticating the data.
- Performing calculations, translations, or summarizations based on the raw data. This can  include changing row and column headers for consistency, converting currencies or other units of measurement, editing text strings, and more.
- Conducting audits to ensure data quality and compliance
- Removing, encrypting, or protecting data governed by industry or governmental regulators
- Formatting the data into tables or joined tables to match the schema of the target data warehouse.

### Load
In this last step, the transformed data is moved from the staging area into a target data warehouse. 

## This Mini Project

Process the registrant data for a hackathon called DQThon.

This dataset consists of 5000 rows of data (5000 registrants) in CSV (Comma-separated value) format and has several columns including:

- participant_id: ID of the hackathon participant. This column is unique so that participants must have different IDs
- first_name: participant's first name
- last_name: participant's last name
- birth_date: participant's date of birth
- address: the participant's residential address
- phone_number: Participant's cellphone/phone number
- country: the participant's country of origin
- institution: current participating institution, can be a company name or university name
- job: participant's current job
- register_time: time participants register for the hackathon in seconds

There are still many inconsistent values in the dataset which must pass through the ETL process.
