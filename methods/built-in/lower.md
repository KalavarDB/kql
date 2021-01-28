---
has_children: false
layout: default
title: Lower
parent: Built-in Methods
grand_parent: Methods
nav_order: 4
---
# Lower
Converts text to its lowercase equivalent

## Overview
### Quick Look

|Name|Arguments|Returns|
|:---:|:---:|:---:|
|Lower|`text`|[String](https://kalavar.cf/documentation/data-types/string/)|

### Arguments

|Name|Example|Required|
|:---:|:---:|:---:|
|`text`|`"HELLO, WORLD!"`|<img src="https://kalavar.cf/assets/images/tick.png" width="30px" height="30px" alt="✅"/>|


## Example
```
GET lower("HELLO, WORLD!")
```
The above example would return a table which looks a little like this:

```
+---------------------+
|        lower        |
+---------------------+
|   "hello, world!"   |
+---------------------+
```
