# Chinook Database Investigation

This project analyzes the Chinook database to extract business insights using SQL queries and data visualizations using MatPlotLib. This project essentially combines Python and SQL. The Chinook database is a sample database often used for learning SQL and data analysis, and it contains information about a digital media store, including customers, invoices, tracks, artists, and more.

## Project Overview

In this notebook-based project, we connect to the Chinook SQLite database and investigate:

- Top-selling genres
- Best-performing artists and albums
- Customer purchase behaviors
- Employee performance (sales support agents)
- Country-wise revenue generation

The primary goal is to support business decisions with data-driven insights.

## Technologies Used

- **Python 3**
- **Jupyter Notebook**
- **SQLite**
- **pandas** – data manipulation
- **matplotlib** – data visualization
- **sqlite3** – SQL queries in Python

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/chinook_db_investigation.git
   cd chinook_db_investigation

2. Install the required libraries (preferably in a virtual environment):
```bash
   pip install pandas matplotlib seaborn

3. Run the Jupyter Notebook:
```bash
   jupyter notebook chinook_db_investigation.ipynb

4. Ensure you have the Chinook database file `Chinook_Sqlite.sqlite` in the same directory as the notebook.

## Repository Structure
```bash
   .
├── chinook_db_investigation.ipynb
├── Chinook_Sqlite.sqlite
├── README.md



