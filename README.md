# COVID-19 Data Exploration Project

## **Overview**
This project provides an in-depth analysis of **COVID-19 data** through **SQL queries and Python processing**. It explores **infection trends, death rates, testing patterns, and vaccination rates** to identify correlations and trends across different demographics. Additionally, interactive **Tableau visualizations** enhance the data interpretation process.

## **Table of Contents**
1. [Getting Started](#getting-started)  
   - [Requirements](#requirements)  
2. [Download and Installation](#download-and-installation)  
3. [Data Source](#data-source)  
4. [Data Exploration Process](#data-exploration-process)  
5. [License](#license)  

## **Getting Started**
To run the SQL queries and analyze the dataset, follow the steps below.

### **Requirements**
- A **Database Management System (DBMS)** supporting standard SQL (e.g., MySQL, PostgreSQL, Microsoft SQL Server **(used in this project)**, or Oracle).
- A **Database Manager** (e.g., MySQL Workbench, Microsoft SQL Server Management Studio) for better query execution and result visualization.
- **Python (Optional)**: For data processing and additional analysis.
- **Tableau (Optional)**: For interactive visualizations.

## **Download and Installation**
1. **Clone or Download the Repository:**  
   ```sh
   git clone https://github.com/jeshwanthsingh/COVID-19-data-exploration.git
   ```
   Or download the **.zip** file manually and extract it.

2. **Import Data into Your DBMS:**  
   - Find the dataset in the `tables/` folder.
   - Import these files into your **SQL database** using your DBMS import tools.

3. **Execute Queries:**  
   - The SQL queries are stored in the `queries/` folder.
   - Open and execute them in your database query editor.

4. **(Optional) Python & Tableau:**  
   - Run `python analysis.py` (if applicable) for additional data processing.
   - Open the Tableau dashboard to explore visualizations.

## **Data Source**
- The dataset originates from **[Our World in Data](https://ourworldindata.org/covid-deaths)**.
- The original dataset was **cleaned and modified** into structured tables for better analysis.

## **Data Exploration Process**
- **SQL Analysis:**
  - **Joins, CTEs, Temp Tables, Window Functions**
  - **Aggregations, Data Type Conversions, Case Statements**
  - **Creating Views for simplified analysis**
- **Python Processing:**
  - Data wrangling using `pandas` and `numpy`
  - Statistical insights on COVID-19 trends
- **Tableau Visualizations:**
  - Interactive dashboards to explore **global COVID-19 patterns**
  - Identification of **pandemic risk factors**

## **Key Insights (May 2022 – July 2023)**
- Processed **5M+ records** to extract statistical trends.
- Identified **correlations between vaccination rates and infection control**.
- Highlighted **peak infection periods** through time-series analysis.

## **License**
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

