# 🥗 UK Food Hygiene Data Analysis (MongoDB + Python)

This project uses MongoDB and PyMongo to explore food hygiene ratings across the UK, based on public health inspection data from the Food Standards Agency.

## 🔍 Overview

The analysis is divided into three parts:

### Part 1: Database Setup
- Import data from a JSON file into a MongoDB collection
- Explore the structure of the dataset
- Use `find_one()`, list databases, and confirm successful setup

### Part 2: Database Updates
- Add a new restaurant ("Penang Flavours") to the database
- Update that entry with a missing business type ID
- Remove all records related to the "Dover" local authority
- Convert string-based fields (latitude, longitude, rating) to numeric values

### Part 3: Exploratory Analysis
- Use queries and aggregation to answer key editorial questions:
  - Establishments with high hygiene scores
  - Top-rated establishments near a specific location
  - Hygiene performance by local authority

## 🧰 Tools Used

- Python
- PyMongo
- MongoDB
- Pandas
- Pretty Print
- Jupyter Notebook

## 🗂 Key Files

- `database_setup.ipynb`: Notebook for loading and preparing data
- `hygiene_analysis.ipynb`: Notebook for answering analysis questions
- `Resources/establishments.json`: Original dataset from the Food Standards Agency

## 📝 Instructions to Run

1. Launch MongoDB locally
2. Run the `mongoimport` command shown in the setup notebook
3. Open Jupyter and run each notebook cell-by-cell
