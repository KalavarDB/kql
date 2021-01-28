---
has_children: false
layout: default
title: Snowflake
parent: Built-in Methods
grand_parent: Methods
nav_order: 2
---
# Snowflake
Generates a Snowflake identifier from the provided arguments

## Overview
### Quick Look

|Name|Arguments|Returns|
|:---:|:---:|:---:|
|Snowflake|`machine_id`, `sequence`|[Snowflake](https://kalavar.cf/documentation/data-types/snowflake/)|

### Arguments

|Name|Example|Required|
|:---:|:---:|:---:|
|`machine_id`|`8`|<img src="https://kalavar.cf/assets/images/cross.png" width="30px" height="30px" alt="❌"/>|
|`sequence`|`804`|<img src="https://kalavar.cf/assets/images/cross.png" width="30px" height="30px" alt="❌"/>|

## Example
```
GET snowflake()
```
The above example would return a table which looks a little bit like this:

```
+----------------------+
|          id          |
+----------------------+
| 10765432100123456789 |
+----------------------+
```
