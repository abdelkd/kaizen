---
tags:
  - type/zettel
  - concept/pure-functions
aliases: 
created: 2025-04-12 00:02:55
---
# Pure Functions

## What is a Pure Function

A pure function is a function that adheres to two principles: **Deterministic** and **No side effects** 

* **Determistic:** given the same inputs the function would return the same value.
* **No side effects:** The function doesn't invoke any side effects such as: 
    * make HTTP requests
    * change global values
    * change arguments passed to the function
    * change program's state in any way.

## Connections

* [[Pure Function Characteristics]]