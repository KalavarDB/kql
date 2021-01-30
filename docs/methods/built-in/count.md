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
### Quick Look

|Name|Arguments|Returns|
|:---:|:---:|:---:|
|Count|`filter`|[Unsigned Integer](https://kalavar.cf/documentation/data-types/integer/)|

### Arguments

|Name|Example|Required|
|:---:|:---:|:---:|
|`filter`|`FILTER email == "member@example.com"`|<img src="https://kalavar.cf/assets/images/tick.png" width="30px" height="30px" alt="✅"/>|


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
