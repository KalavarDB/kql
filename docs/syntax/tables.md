---
has_children: false
layout: default
title: Tables
parent: Syntax
nav_order: 4
---

# Tables
KQL table definitions are simple, there is no encoding limits, no errors relating to tables, and nothing confusing. Just set the name, and set the columns, its that simple!

## Defining a table
```
CREATE TABLE
    table_name
WITH COLUMNS
    id SNOWFLAKE,
    username STRING,
    email STRING
    password STRING
```
To create a table, you use the phrase `CREATE TABLE` followed by the name of the table. You must also provide at least one field for the table to contain.

