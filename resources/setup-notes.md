# Preface — Setup Notes

## Why SQL Matters

SQL is a long-standing language used to store, organize, manipulate, and retrieve structured data. The book emphasizes that SQL remains important for data analysis, business intelligence, data science, and reporting work.

## Example Database Used

The book uses the **Sakila sample database** for its examples and exercises.

To follow along, I need:

- MySQL installed
- the Sakila schema loaded
- the Sakila data loaded
- access to the database from either the MySQL command line or Jupyter notebooks

## Sakila Setup Summary

The book’s setup process is:

1. Download the Sakila database files from MySQL’s example databases page.
2. Save the files locally.
3. Load the schema file: `sakila-schema.sql`
4. Load the data file: `sakila-data.sql`
5. Confirm the database is populated and ready for queries.

## My Setup

I am using a local Linux machine with the Sakila database installed locally.

## GitHub / Notebook Requirements

To make this repo easy for others to follow, each notebook should include:

- what chapter the notebook covers
- what database is being used
- required Python packages
- database connection assumptions
- SQL queries shown clearly
- markdown explanations of what each query is doing
- outputs displayed in tables when helpful
- short reflections connecting the SQL concept to market analysis

## Important Note

I will not upload private passwords, local database credentials, or sensitive connection details to GitHub.
