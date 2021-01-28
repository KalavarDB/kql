---
has_children: false
layout: default
title: Count
parent: Built-in Methods
grand_parent: Methods
nav_order: 1
---
# Count
Counts the number of items matching a filter from a table

## Overview
|Name|Arguments|Returns|
|:---:|:---:|:---:|
|Count|`Filter`|Unsigned Integer|

## Example
```
GET forum.users
FIELDS count(FILTER email == "member@example.com")
```
The above example would return a table which looks a little bit like this:

```
+-------+
| count |
+-------+
|   1   |
+-------+
```
