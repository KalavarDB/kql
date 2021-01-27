---
has_children: false
layout: default
title: Responses
parent: Sample Queries
nav_order: 7
---

> ## ⚠️ Warning ⚠️
> #### The documentation you are reading is neither implemented, nor finalised. please do not take this at anything more than face value, until this message has been removed. Thank you.



# Responses

## Phase 1:
> Sent immeditately after receiveing and parsing a query. contains two fields<br>
> `SNOWFLAKE` - (Always present) The `QueryID`. __KEEP THIS STORED__<br>
> `POSITION` - (Nullable) The (estimated) position in the query queue. This is not a guarantee, and should not be used for tracking query information.
```
SNOWFLAKE: 882b46ec
POSITION: 10
```
Example with `NULL` position:
```
SNOWFLAKE: 882b46ec
POSITION: NULL
```

## Phase 2:
> Sent once the query has been processed, clients are expected to recognise a `QueryID` and return the data for the correct request accordingly.
```
RESPONSE <query ID>
COLUMNS: "name":"type"
"name":"type"
"name":"type"
ROWS: John Doe|email@provider.tld|abc123
John Doe|email@provider.tld|abc123
John Doe|email@provider.tld|abc123
John Doe|email@provider.tld|abc123
John Doe|email@provider.tld|abc123
```