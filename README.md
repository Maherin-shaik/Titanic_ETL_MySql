# 🚢 Titanic ETL with MySQL

## 📌 What this Project Does

This project demonstrates a simple ETL (Extract, Transform, Load) pipeline using the Titanic dataset:

- 🔍 **Extract**: Reads Titanic CSV data using Pandas  
- 🧹 **Transform**: Cleans data (handles missing values, fixes types)  
- 🗄️ **Load**: Loads the cleaned data into a MySQL database table

This is a part of my Data Engineering learning journey.

---

## 🛠 Tools Used

- Python
- Pandas
- SQLAlchemy
- MySQL

---


## 📂 How to Run the Script

### 1. 🛠 Prerequisites

Make sure you have the following installed:
- Python 3.10+ (3.12 tested)
- MySQL installed and running

### 2. 🧪 Create the MySQL Database
Before running the notebook, create a MySQL database called etl_demo:
  ```
CREATE DATABASE etl_demo;
```
### 3. 📝 Update Credentials in Notebook
In the notebook, update your connection settings:
```
conn = mysql.connector.connect(
    host="localhost",
    user="root",
    password="your_password",  # change this
    database="etl_demo"
)
```
### 4. ▶️ Run the Jupyter Notebook
Open and run the cells in titanic_etl_mysql.ipynb. It will:

Create the titanic table (if not exists)

Insert cleaned rows into the table

## Author
Maherin Shaik
Aspiring Data Engineer

