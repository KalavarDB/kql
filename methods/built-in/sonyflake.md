---
has_children: false
layout: default
title: SonyFlake
parent: Built-in Methods
grand_parent: Methods
nav_order: 3
---
# SonyFlake
Generates a SonyFlake identifier from the provided arguments

## Overview
### Quick Look

|Name|Arguments|Returns|
|:---:|:---:|:---:|
|SonyFlake|`machine_id`, `sequence`|[SonyFlake](https://kalavar.cf/documentation/data-types/sonyflake/)|

### Arguments

|Name|Example|Required|
|:---:|:---:|:---:|
|`machine_id`|`8`|<img src="https://kalavar.cf/assets/images/cross.png" width="30px" height="30px" alt="❌"/>|
|`sequence`|`804`|<img src="https://kalavar.cf/assets/images/cross.png" width="30px" height="30px" alt="❌"/>|

## Example
```
GET sonyflake()
```
The above example would return a table which looks a little bit like this:

```
+-----------------+
|       id        |
+-----------------+
| 20f8707d6000108 |
+-----------------+
```
