---
has_children: false
layout: default
title: Pruning Data
parent: Sample Queries
nav_order: 5
---

> ## ⚠️ Warning ⚠️
> #### The documentation you are reading is neither implemented, nor finalised. please do not take this at anything more than face value, until this message has been removed. Thank you.


# Prune
In order to remove values from table, the client must send a `PRUNE` query, a type of query which allows the client to specify the type of logic matching they wish to achieve. The filters are always prepended with a number, matching them to any paired logical operations (see below example for further clarification).
```
PRUNE my_database.A
FILTERS: 1:"name"=="John Doe"
AND 1:"pass"=="abc123"
OR 2:"pass"==NUll
```