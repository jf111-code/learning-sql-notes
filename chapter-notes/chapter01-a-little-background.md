# Chapter 1 — A Little Background

## Chapter Objective

Understand how databases evolved, why relational databases became dominant, and how SQL emerged as the standard language for working with data.

---

## Key Concepts

### Database

A database is a collection of related information.

Examples:

- telephone directory
- customer records
- bank accounts
- stock market data
- financial statements

Computerized databases improve:

- speed
- accuracy
- searchability
- data maintenance

---

### Early Database Systems

Before relational databases, two major approaches existed:

#### Hierarchical Databases

Data organized like a tree:

Customer
└── Account
    └── Transactions

Advantages:
- simple structure

Disadvantages:
- difficult to query flexibly
- limited relationships

#### Network Databases

Data connected through links.

Advantages:
- more flexible relationships

Disadvantages:
- complicated navigation
- difficult maintenance

---

### Relational Databases

Introduced by E.F. Codd at IBM in 1970.

Core idea:

Store information in tables rather than linked trees.

Examples:

- Customers
- Accounts
- Transactions
- Products

Tables can be connected using shared identifiers.

---

### Primary Keys

A column that uniquely identifies a row.

Examples:

- customer_id
- account_id
- transaction_id

Purpose:

- uniquely identify records
- prevent duplicates

---

### Foreign Keys

A column that links one table to another.

Example:

account.customer_id

links:

Account → Customer

Purpose:

- connect related tables
- support joins

---

### Normalization

Design principle:

Store each piece of information only once.

Benefits:

- reduces redundancy
- improves consistency
- reduces errors

---

### SQL

SQL evolved from IBM research into the standard language for relational databases.

SQL is used to:

- retrieve data
- insert data
- update data
- delete data
- define database structures

---

### Major SQL Statement Types

Schema Statements:

- CREATE
- ALTER
- DROP

Data Statements:

- SELECT
- INSERT
- UPDATE
- DELETE

Transaction Statements:

- COMMIT
- ROLLBACK

---

### SQL Is Nonprocedural

Traditional programming tells the computer HOW to do something.

SQL tells the database WHAT results you want.

The database optimizer decides how to retrieve the data.

---

## Important SQL Pattern

Most queries follow:

SELECT
FROM
WHERE

Example:

SELECT customer_name
FROM customers
WHERE state = 'IL';

---

## Why This Matters For Market Analysis

Market data naturally fits relational databases.

Examples:

### Company Table

- ticker
- company name
- sector

### Price Table

- ticker
- date
- close price

### Financial Statement Table

- ticker
- revenue
- earnings
- assets

### Economic Data Table

- date
- CPI
- unemployment
- GDP

SQL allows these datasets to be connected and analyzed efficiently.

---

## Personal Takeaways

- SQL remains highly relevant despite newer technologies.
- Relational thinking is more important than memorizing syntax.
- Understanding tables, keys, and relationships is foundational.
- SQL complements Python rather than replacing it.
- Market and financial data are naturally suited to relational databases.