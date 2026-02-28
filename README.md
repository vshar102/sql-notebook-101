# Introduction to SQL Notebooks
## 📌 Project Overview
This project is an introductory DataCamp workspace notebook designed to teach the fundamentals of working with SQL in a notebook environment. It serves as a beginner-friendly tutorial on how to navigate, execute, and submit SQL queries using interactive cells.
## 🎯 Key Objectives
The notebook systematically guides the user through the following foundational concepts:
* **Understanding Notebooks**: Learning how notebooks combine markdown (text) and executable code.
* **Working with Cells**: Differentiating between text cells used for documentation and SQL cells used to compute queries.
* **Executing SQL Queries**: Querying connected databases directly within the notebook and understanding how results are temporarily stored as DataFrames.
* **Managing Notebook Structure**: Adding and removing cells to keep the workspace organized.
* **Project Submission & Evaluation**: Understanding how automated tests evaluate the DataFrame output names, ordering, and exact column matching against correct solutions.
## 🛠️ Technologies Used
* **SQL** (Microsoft SQL Server / standard SQL syntax)
* **Jupyter Notebook**
## 📊 Dataset Context
The project interacts with a built-in mock schema called `sales`, querying specifically from the `sales.orders` table to retrieve transactional data details, including `order_id` and `customer_id`.
## 🧑‍💻 Task Execution
The capstone of this introductory project involves:
1. Familiarizing oneself with testing errors by executing deliberately incorrect SQL queries to read feedback prompts.
2. Correcting the target query to retrieve the `customer_id` from `sales.orders` where the `order_id` is exactly `10`.
