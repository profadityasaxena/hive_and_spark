# Hive and Spark - Mini Project – Big Data Analytics Tools

This summary outlines the practical, hands-on skills developed through the assignment exercises. The course focused on using modern big data tools such as Hadoop, Hive, and Apache Spark for data ingestion, transformation, and analysis.

---

## 💾 Big Data Environment Setup & Management
- Configured and managed virtual machines (VMs) using **Oracle VirtualBox**.
- Established secure remote access using **PuTTY** and **SSH**.
- Transferred datasets between host machines and virtual environments using `pscp`.

---

## 📂 Working with Hadoop Distributed File System (HDFS)
- Performed HDFS operations:
  - Upload/download: `put`, `get`
  - File management: `ls`, `cp`, `rm`, `cat`
- Created and maintained directories and datasets within HDFS.
- Prepared unstructured data for distributed processing.

---

## 🐘 Data Warehousing with Apache Hive
- Created and managed **Hive databases** and **tables** using HiveQL.
- Wrote and executed SQL-like queries for:
  - Filtering, aggregation, joins, subqueries
  - String and timestamp transformations
- Used **complex data types**: `ARRAY`, `MAP`, `STRUCT`.
- Applied **User-Defined Aggregate Functions (UDAFs)** such as:
  - `sentences()` – tokenizing text
  - `ngrams()` – extracting common phrases
- Imported structured data from **MySQL to Hive** using **Apache Sqoop**.

---

## ⚙️ Big Data Processing with Apache Spark
- Developed data pipelines using:
  - **RDD API** for low-level transformations (`map`, `flatMap`, `filter`, `reduceByKey`)
  - **DataFrame API** for structured processing and SQL queries
- Loaded and analyzed data from CSV and text files.
- Created PySpark batch jobs and executed them using `spark-submit`.
- Leveraged **Spark SQL** to run SQL queries over distributed datasets.

---

## 📊 Analytical Thinking & Problem Solving
- Designed complete workflows for data ingestion, processing, and querying.
- Extracted insights from large datasets such as NASA web logs and geo-tagged tweets.
- Built confidence working with real-world semi-structured and unstructured data.

---

## ✅ Summary
By completing these labs, students developed a solid foundation in big data engineering and analytics, with real-world exposure to distributed systems, data warehousing, and parallel processing using the Hadoop ecosystem and Apache Spark.
