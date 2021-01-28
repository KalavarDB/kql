---
has_children: false
layout: default
title: Upper
parent: Built-in Methods
grand_parent: Methods
nav_order: 4
---
# Upper
Converts text to its uppercase equivalent

## Overview
### Quick Look

|Name|Arguments|Returns|
|:---:|:---:|:---:|
|Lower|`text`|[String](https://kalavar.cf/documentation/data-types/string/)|

### Arguments

|Name|Example|Required|
|:---:|:---:|:---:|
|`text`|`"hello, world!"`|<img src="https://kalavar.cf/assets/images/tick.png" width="30px" height="30px" alt="✅"/>|


## Example
```
GET upper("hello, world!")
```
The above example would return a table which looks a little like this:

```
+---------------------+
|        upper        |
+---------------------+
|   "HELLO, WORLD!"   |
+---------------------+
```
