# Mini-ETL-project


🎯 **Goal of the Project**
The objective of this project is to simulate a real-world ETL (Extract, Transform, Load) pipeline using Python. It demonstrates how raw data from different sources can be collected, cleaned, transformed, and stored in a structured format, ready for analysis or further processing.


📌 **Introduction**


ETL processes are foundational in the field of data engineering and analytics. In this mini project, I’ve built an ETL pipeline using Python to:

Simulate extracting data from multiple CSV files

Transform the data by cleaning, formatting, and combining it

Load the transformed data into a final CSV file for further use

This project serves as a simplified example of how data flows through a basic pipeline, reflecting concepts used in production-level data systems.




🔧 **Work Done Using Python Libraries**
This project makes use of the following Python libraries:

pandas: For data manipulation and transformation

os: For navigating through directories and handling file paths

datetime: For timestamp generation and handling

glob: To fetch all files of a particular type from the source directory

**Steps performed:**

**Extract Phase:**

  Fetched multiple CSV files from a source folder using glob.

  Read them using pandas and appended into a single DataFrame.

**Transform Phase:**

  Cleaned and formatted the data by:

  Renaming columns

  Handling missing or inconsistent values

  Standardizing data types

  Adding new calculated columns

  Added metadata like a timestamp column for tracking

**Load Phase:**

  Saved the final cleaned and transformed data into a new CSV file using to_csv().



📍 **Key Points**
  Created an automated ETL pipeline in Python.

  Handled multiple data sources using glob and os.

  Applied data cleaning and transformation techniques using pandas.

  Implemented a modular structure with functions for each ETL phase.

  Ensured scalability by designing the project in a reusable way.


✅ **Conclusion**
This Mini ETL Project showcases the core principles of building an ETL pipeline using Python. It emphasizes automation, data cleaning, and structured output—all essential in real-world data workflows. It’s a great stepping stone toward more complex data engineering tasks, such as integrating with databases, APIs, or cloud-based pipelines.









