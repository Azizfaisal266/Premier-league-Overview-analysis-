# Premier League Overall Performance Analysis

This project analyzes **Premier League player performance** and their contribution across different performance metrics using Microsoft Excel.

## 📊 Project Overview

The analysis transforms raw player data into a structured analytical dataset and provides insights into player performance, positions, and overall contribution.

## 🛠️ Tools Used

### Microsoft Excel

* **Power Query** — Data preparation and transformation
* **Power Pivot** — Data modeling and relationships
* **DAX** — Calculated columns and measures
* **Pivot Tables** — Data analysis and insight generation

## 🔄 Data Preparation — Power Query

The raw player dataset was cleaned and transformed using Power Query:

* Imported and transformed the raw player dataset.
* Renamed columns to improve clarity and consistency, such as `Age` → `PlayerAge`.
* Cleaned player age data by extracting numeric values from complex formats, such as `29-240` → `29`.
* Used **Column From Examples** to automate data transformation.
* Standardized data types, including converting `PlayerAge` to a Whole Number.
* Split multi-value position fields into separate rows using a delimiter, such as `FW,AM` → `FW` and `AM`.
* Removed unnecessary columns and reorganized the dataset.
* Created and renamed an index column as `PlayerID` to uniquely identify each player record.
* Produced a clean and structured dataset ready for data modeling and analysis.

## 🧩 Data Modeling — Power Pivot

The cleaned data was loaded into Power Pivot to create a structured data model:

* Loaded the transformed tables into Power Pivot.
* Established relationships between related tables using `PlayerID`.
* Created a structured model to manage multiple related tables efficiently.
* Created calculated columns and **DAX measures** for advanced analysis.
* Used Pivot Tables to extract meaningful insights from the data model.
* Enabled dynamic analysis through an integrated and scalable data model.

## 🎯 Project Goal

The goal of this project is to transform raw Premier League player data into meaningful insights by combining **data cleaning, data modeling, DAX, and analytical reporting** in Excel.

## 📷 Dashboard Preview

![Premier League Overall Performance Analysis](dashboard.png)

## 📁 Project Files

* `Premier League Overview Analysis.xlsx` — Excel analysis and dashboard
* `README.md` — Project documentation

