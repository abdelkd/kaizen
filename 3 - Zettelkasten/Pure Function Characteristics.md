---
tags:
  - type/zettel
  - concept/pure-functions
aliases: 
created: 2025-04-12 00:22:13
---
# Function Characteristics

A pure function is a function has to be predictable and with no side effects (external calls/values).

Some key characteristics has to exist in a function to define whether it is pure or not
## Key Characteristics

- **Predicability:** Since pure functions rely on input only, their behavior and return value is predicable.
- **Testability:** Since the function doesn't rely on any external state except the inputs, testing it would be as easy as calling it with the desired input.
- **Referential Transparency:** Being a pure function means ability to change the function calls to actual value without affecting the program's behavior.
- **Readability and Maintainability:** a function that doesn't rely on external states makes it readable and maintainable.

## Connections
[[What is Pure Function]]