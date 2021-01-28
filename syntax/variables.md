---
has_children: false
layout: default
title: Variables
parent: Syntax
nav_order: 2
---

# Variables

KQL supports 3 different types of variables, public variables, private variables, and constants. Further documentation on these can be found below.

### Overview

|Name|Lifetime|Public|Accepted Data Types|
|:---:|:---:|:---:|:---:|
|Public Variable|Program|<img src="https://kalavar.cf/assets/images/tick.png" width="30px" height="30px" alt="✅"/>|All|
|Private Variable|Connection|<img src="https://kalavar.cf/assets/images/cross.png" width="30px" height="30px" alt="❌"/>|All|
|Constant|Program|<img src="https://kalavar.cf/assets/images/tick.png" width="30px" height="30px" alt="✅"/>|All|

## Public Variables
A public variable can be read, written, and removed by any connection at any time. These values are [ephemeral](/glossary#ephemeral) meaning they disappear when the database closes for any reason

### Code Sample(s)
```
DEFINE PUBLIC my_variable = "Hello, World!";
```

---

## Private Variables
A private variable can be read, written, and removed at any moment by the connection which initiated them. These values are [ephemeral](/glossary#ephemeral) meaning they disappear when the database closes for any reason

### Code Sample(s)
```
DEFINE my_variable = "Hello, World!";
```

---

## Constants
Although not by definition "variable", these data containers are written to their own internal database upon creation, and are always considered public. They are also considered permanent. These values may be only be defined, never over-written, and will automatically load into the system when called for, no matter if the system has had a shutdown since it was created.
### Code Sample(s)
```
DEFINE CONST my_constant = 42
```

```
DEFINE CONSTANT my_constant = 42
```