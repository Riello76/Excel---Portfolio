# Excel-Sales-Dataset-Analysis

This document provides an overview of the data analysis capabilities and features implemented within this Excel file, which contains various datasets (such as retail sales and student scores).

***

## 1. File Structure & Included Data

The workbook is structured into several sheets, typically including:
* **Source Data:** Sheets containing the raw, transactional data (e.g., `retail_sales_dataset`, `Transactions`).
* **Analytic Sheets:** Sheets dedicated to calculations and specific tasks (e.g., `Day 2 Task 2`).
* **Summary Sheets:** Sheets containing aggregated results and visualizations (e.g., `Pivot Table`, `Sheet2`, `Sheet3`).

***

## 2. Key Analysis Features

This section details the functions and tools used to process and analyze the data:

### 📊 Calculation & Aggregation Functions

| Function | Description | Typical Application |
| :--- | :--- | :--- |
| **SUM** | Calculates the total sum of values in a range. | Calculating **Total Sales** or overall scores. |
| **AVERAGE** | Calculates the arithmetic mean of a range of numbers. | Determining the **Average** unit price or student score. |
| **SUMIF** | Calculates the sum of values that meet a single, specified condition. | Summing sales for a specific **Product Category** or Region. |
| **AVERAGEIF** | Calculates the average of values that meet a single, specified condition. | Finding the average score for only **Female** students or sales in a specific year. |
| **VLOOKUP** | Searches for a value in the first column of a table and returns a corresponding value from a specified column. | Retrieving customer details (e.g., age or generation) or product price based on an ID. |

### ⚙️ Advanced Data Tools

| Tool | Description | Purpose |
| :--- | :--- | :--- |
| **Pivot Table** | A powerful tool used to quickly summarize, analyze, explore, and present large amounts of data. | Used to segment data (e.g., total sales by **Gender** and **Product Category**). |
| **Pivot Chart** | A dynamic visual representation linked directly to a Pivot Table. | Provides an immediate, interactive graph of the summarized data (e.g., bar chart of sales distribution). |
| **Formatting** | Includes standard number formats (currency, date, percentage) and **Conditional Formatting**. | Enhancing readability and using color rules (e.g., data bars or icons) to highlight high/low values. |

***

## 3. How to Use

The file is intended to be used by navigating to the relevant sheets to view the raw data or the pre-calculated analysis results.

* To modify the Pivot Table analysis, right-click on the table and select "Show Field List."
* Ensure all filters and sorting are cleared before attempting new calculations on the raw data sheets.
