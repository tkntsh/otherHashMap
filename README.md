# Java Collections Framework Examples

This repository contains two Java programs demonstrating the use of `HashMap` and `ArrayList`, two key components of the Java Collections Framework. These examples illustrate basic operations like adding, retrieving, iterating, and removing elements.

---

## Files

### **1. HashMapExample.java**
- **Purpose**: Demonstrates how to use a `HashMap` to store and manage key-value pairs.
- **Features**:
  - Adds key-value pairs to a `HashMap`.
  - Retrieves a value by its key.
  - Iterates through the `HashMap` using its keys.
  - Removes a key-value pair from the `HashMap`.

#### Example Code Snippet
```java
HashMap<String, Integer> ages = new HashMap<>();
ages.put("Alice", 25);
ages.put("Bob", 30);
ages.put("Charlie", 22);
System.out.println("Alice's age: " + ages.get("Alice"));
