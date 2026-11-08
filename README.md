# SQL Practice --- DVD Rental Database

A collection of 25 SQL practice questions and solutions using the **DVD
Rental** sample database in PostgreSQL.

The project documents my SQL learning journey, from basic queries to
joins, aggregations, CTEs, and window functions.

## Topics Covered

-   `SELECT`, `WHERE`, `LIKE`, `ORDER BY`, and `LIMIT`
-   `INNER JOIN` and `LEFT JOIN`
-   Aggregate functions: `COUNT()`, `SUM()`, and `AVG()`
-   `GROUP BY` and `HAVING`
-   `CASE WHEN`
-   Subqueries and Common Table Expressions (CTEs)
-   Date analysis with `DATE_TRUNC()`
-   `CROSS JOIN`
-   Window functions, including `LAG()`

## Practice Questions

The exercises cover tasks such as:

1.  Retrieving film and customer information
2.  Filtering films and customers
3.  Joining customers with city and country information
4.  Finding films by category
5.  Identifying top-spending customers
6.  Finding customers who have never rented
7.  Counting films by category
8.  Calculating revenue by store and category
9.  Classifying films by length with `CASE WHEN`
10. Using subqueries and CTEs for customer and film analysis
11. Analyzing monthly revenue
12. Finding the most-rented films and categories
13. Finding customers who rented from both stores
14. Filtering grouped results with `HAVING`
15. Comparing customer activity with the average
16. Comparing monthly revenue with the previous month using `LAG()`

See [`25questions.sql`](./25questions.sql) for the full exercise prompts
and SQL work.

## Database

These exercises use the **DVD Rental** sample database, a PostgreSQL
practice database containing tables such as:

-   `film`
-   `customer`
-   `rental`
-   `payment`
-   `inventory`
-   `store`
-   `category`
-   `film_category`

## How to Use

1.  Set up the PostgreSQL DVD Rental sample database.
2.  Open `25questions.sql` in a SQL editor such as pgAdmin, DBeaver, or
    VS Code with a PostgreSQL extension.
3.  Read each exercise prompt and try solving it before looking at the
    query beneath it.
4.  The SQL statements in the current file are commented out with `--`.
    Remove the comment markers from a query before executing it.

## Notes

-   This is a learning/practice project, not a production application.
-   The SQL file contains my attempts and worked solutions. Some
    exercises may still need a solution or further refinement as I
    continue learning.
-   The project focuses on PostgreSQL syntax.

## Learning Progress

I am using this repository to practice SQL step by step and build a
portfolio of practical data analysis exercises.

------------------------------------------------------------------------

**Database:** PostgreSQL DVD Rental\
**Language:** SQL
