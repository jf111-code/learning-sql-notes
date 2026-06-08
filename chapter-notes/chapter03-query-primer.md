# Chapter 3 — Query Primer

## Chapter Objective

Learn the basic structure of SQL `SELECT` statements and understand how data is retrieved, filtered, joined, grouped, and sorted.

## Query Mechanics

When a query is submitted, the database server checks:

- permissions
- access rights
- syntax

If the query passes these checks, the optimizer decides how to execute it.

## Core Query Clauses

| Clause | Purpose |
|---|---|
| SELECT | Chooses columns for the result set |
| FROM | Identifies tables and joins |
| WHERE | Filters rows |
| GROUP BY | Groups rows |
| HAVING | Filters grouped rows |
| ORDER BY | Sorts results |

## SELECT Clause

The `SELECT` clause determines which columns appear in the result set.

Examples:

```sql
SELECT *
FROM language;

