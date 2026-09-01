# Job Data Analysis Using Python APIs

## 📌 Project Overview

This project explores how Python can be used to retrieve, process, and analyze job posting data from an API.

The project was completed as a hands-on learning lab during the **IBM Data Analyst Professional Certificate on Coursera**.

The main objective was to analyze job postings based on **location** and **technology skills**, and export the results into Excel files for further analysis.

---

## 🎯 Objectives

The project focuses on:

* Retrieving job posting data using an API
* Working with JSON data in Python
* Filtering job postings by location
* Filtering job postings by technology/skill
* Creating reusable Python functions
* Exporting analysis results to Excel

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* REST API / HTTP Requests
* JSON
* Pandas
* Requests
* OpenPyXL
* Excel

---

## 📊 Dataset

The project uses a modified job-posting dataset provided through the IBM Skills Network.

The job data contains fields including:

* Job Title
* Job Experience Required
* Key Skills
* Role Category
* Location
* Functional Area
* Industry
* Role

---

## 🔎 Analysis Performed

### 1. Job Postings by Location

I created a Python function to calculate the number of available job postings for different locations.

The locations analyzed include:

* Los Angeles
* New York
* San Francisco
* Washington DC
* Seattle
* Austin
* Detroit

The results were exported to an Excel spreadsheet.

### 2. Job Postings by Technology

I also created a function to search the **Key Skills** field and calculate the number of job postings associated with different technologies.

Technologies analyzed include:

* C
* C#
* C++
* Java
* JavaScript
* Python
* Scala
* Oracle
* SQL Server
* MySQL Server
* PostgreSQL
* MongoDB

The results were stored in a separate Excel file.

---

## 🔄 Project Workflow

**API → JSON Data → Python Processing → Filtering → Job Counts → Excel Output**

1. Send an HTTP GET request using Python's `requests` library.
2. Retrieve the job dataset in JSON format.
3. Convert the API response into Python data structures.
4. Loop through individual job postings.
5. Filter postings based on location or technology.
6. Calculate the number of matching jobs.
7. Export the results into Excel using OpenPyXL.

---

## 💡 Skills Demonstrated

This project demonstrates practical experience with:

* API data collection
* HTTP GET requests
* JSON processing
* Python functions
* Loops and conditional statements
* String matching and filtering
* Data extraction
* Job market data analysis
* Excel file creation using Python

---

## 📚 What I Learned

Through this project, I gained hands-on experience retrieving data from an API and processing JSON responses using Python.

I also learned how to create reusable functions to filter larger datasets based on specific business questions, such as identifying job opportunities by location or technology skill.

Finally, I practiced exporting Python analysis results into structured Excel files that can be used for additional reporting and analysis.

---

## 📖 Course

This project was completed as a guided learning lab as part of the **IBM Data Analyst Professional Certificate on Coursera**.

The original learning materials and dataset were provided by IBM Skills Network.

## 👤 Author

**Smital Christian**

Aspiring Data Analyst | SQL | Python | Excel | Power BI
