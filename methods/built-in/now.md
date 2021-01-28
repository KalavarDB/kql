---
has_children: false 
layout: default 
title: Now 
parent: Built-in Methods 
grand_parent: Methods 
nav_order: 8
---

# Now

Grabs the current timestamp and returns it as a value

## Overview

### Quick Look

|Name|Arguments|Returns|
|:---:|:---:|:---:|
|Now|Not Applicable|[Naive Timestamp](https://kalavar.cf/documentation/data-types/naive-timestamp/)|

### Arguments

> This method does not take any arguments

## Example

```
GET now()
```

The above example would return a table which looks a little like this:

```
+-------------------------+
|           Now           |
+-------------------------+
| 2021 01 01-00:00:00.000 |
+-------------------------+
```
