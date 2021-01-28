---
has_children: false
layout: default
title: Creating A Table
parent: Basic Queries
grand_parent: Syntax
nav_order: 1
---

> ## ⚠️ Warning ⚠️
> #### The documentation you are reading is neither implemented, nor finalised. please do not take this at anything more than face value, until this message has been removed. Thank you.

## Creating a table
In order to create a table, you must use the `CREATE TABLE` syntax. We have provided a basic table definition below to get you started
```
CREATE TABLE
    public.users
WITH COLUMNS
    id SNOWFLAKE,
    username STRING,
    email STRING
    password STRING
```