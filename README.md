# 🚴‍♂️ Cycling Equipment Manufacturing – Power BI Dashboard

This is an **end-to-end Power BI data analysis project** that focuses on the full **data analysis life cycle**, including:

- **ETL techniques** (Extract, Transform, Load)
- Creating a **relational data model**
- Defining **table relationships**
- Writing custom **DAX measures**
- Designing a **dynamic and interactive dashboard**

## 🎯 Project Objectives

- ✅ Connect and transform raw data using Power Query
- ✅ Build a relational data model with well-structured tables
- ✅ Create calculated columns and measures using DAX
- ✅ Track key KPIs such as **Sales**, **Profit**, **Revenue**, and **Returns**
- ✅ Design an interactive dashboard to visualize key metrics
- ✅ Compare performance across regions
- ✅ Analyze product-level trends and identify high-value customers

---

> 💡 This project simulates a real-world scenario for a **global manufacturing company** that produces cycling equipment, aimed at helping stakeholders monitor performance and make data-driven decisions.

## 🗂️ Data Structure Overview

The image below shows the **data model**, also referred to as a **normalized schema**.

**Normalization** is the process of organizing tables and columns in a relational database to reduce data redundancy and improve data integrity.

In general, a data model consists of two main types of tables:

- **Fact Table**: Contains measurable metrics or quantitative data.
  - In our case: `Sales Data` is the **fact table**.

- **Dimension Tables**: Contain descriptive attributes related to the fact data.
  - In our case:
    - `Territory Lookup`
    - `Customer Lookup`
    - `Product Lookup`
    - `Calendar Lookup`

These dimension tables are connected to the fact table through **relationships**, forming a **star schema** structure that supports efficient slicing and dicing of data.

![Data Model](assets/screenshots/data-model.PNG)

## 🗂️  Project Structure

## Dashboard Preview

![Dashboard Screenshot](assets/screenshots/screenshoot-report.PNG)

---

## 📽️ Demo Video

![Watch the demo](https://www.linkedin.com/feed/update/urn:li:activity:7331704016424292352/)


## 📄 Report

👉 [Click here to view the full report (PDF)](docs/Cycling-Equipment-Report.pdf)

---

## 🙋‍♂️ About Me

**Mohammed Ayoub Essbai**

Data Analyst | Power BI Enthusiast | Python Developer

🔗 [LinkedIn](https://www.linkedin.com/in/mohammed-ayoub-essbai/)

💻 [GitHub](https://github.com/ayoub22222222)

---

## 📜 License

This project is licensed under the MIT License.
