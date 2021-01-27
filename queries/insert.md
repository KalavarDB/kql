---
has_children: false
layout: default
title: Inserting Data
parent: Sample Queries
nav_order: 3
---

> ## ⚠️ Warning ⚠️
> #### The documentation you are reading is neither implemented, nor finalised. please do not take this at anything more than face value, until this message has been removed. Thank you.

# Insert

When the client wishes to insert values into a table, the following fields must be present, `FIELDS`, `VALUES`
```
INSERT my_database.A
FIELDS: "name", "email", "pass"
VALUES: "John Doe", "email@provider.tld", "abc123"
"John Doe", "email@provider.tld", "abc123"
"John Doe", "email@provider.tld", "abc123"
```