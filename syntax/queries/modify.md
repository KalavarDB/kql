---
has_children: false
layout: default
title: Modifying Data
parent: Basic Queries
grand_parent: Syntax
nav_order: 4
---

> ## ⚠️ Warning ⚠️
> #### The documentation you are reading is neither implemented, nor finalised. please do not take this at anything more than face value, until this message has been removed. Thank you.

# Modify
Should the client wish to update the values of a table:
```
MODIFY my_database.A
FILTERS: 1:"name"=="John Doe"
AND 1:"pass"=="abc123"
OR 2:"pass"==NUll
VALUES: "abc122", "abc133", "abc321"
```