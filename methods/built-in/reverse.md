---
has_children: false
layout: default
title: Reverse
parent: Built-in Methods
grand_parent: Methods
nav_order: 6
---
# Reverse
Reverses the position for all characters in a given string

## Overview
### Quick Look

|Name|Arguments|Returns|
|:---:|:---:|:---:|
|Reverse|`text`|[String](https://kalavar.cf/documentation/data-types/string/)|

### Arguments

|Name|Example|Required|
|:---:|:---:|:---:|
|`text`|`"hello, world!"`|<img src="https://kalavar.cf/assets/images/tick.png" width="30px" height="30px" alt="✅"/>|


## Example
```
GET reverse("hello, world!")
```
The above example would return a table which looks a little like this:

```
+---------------------+
|       reverse       |
+---------------------+
|   "!dlrow ,olleh"   |
+---------------------+
```
