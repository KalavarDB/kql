---
has_children: false
layout: default
title: Comments
parent: Syntax
nav_order: 3
---

# Comments

KQL supports two types of comment, inline, and block. Comments are used to provide context to code.

### Overview

|Name|Start|End|Description|
|:---:|:---:|:---:|:---:|
|Inline|`#`|`\n` (new line)| An inline comment marks everything after itself as a comment, up until the next line begins. This means that the compiler will ignore it and move onto the next line|
|Block|`/#`|`#/`| A block comment marks everything between the starting indicator, and the ending indicator, as a comment. the compiler will ignore this section and resume processing after it has skipped the comment|

## Inline Comments
Inline comments mark any content after them until the beginning of the next line, as a comment. Commented items are skipped by the compiler.

### Example {#inline-example}
```
# Here we define a table
# It is very basic
CREATE TABLE
    public.users
WITH COLUMNS
    id SNOWFLAKE,
    username STRING,
    email STRING
    password STRING
```

## Block Comments
Block comments mark any content between the beginning identifier (`/#`) and the ending identifier (`#/`) as a comment. Commented items are skipped by the compiler.

### Example {#block-example}
```
/#
  Here we define a table
  It is very basic
#/
CREATE TABLE
    public.users
WITH COLUMNS
    id SNOWFLAKE,
    username STRING,
    email STRING
    password STRING
```