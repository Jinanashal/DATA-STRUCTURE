# 🐍 Python Data Structures – Notes Only

This repository is a structured summary of the core data structures in Python. It covers key features, characteristics, and differences—without code examples.

---

## 📋 List

- Ordered collection
- Mutable (can be changed)
- Allows duplicate elements
- Elements can be of different data types
- Supports indexing and slicing
- Common operations: append, remove, insert, pop, sort

---

## 📦 Tuple

- Ordered collection
- Immutable (cannot be changed after creation)
- Allows duplicate elements
- Supports indexing and slicing
- Faster than lists due to immutability
- Commonly used for fixed data

---

## 🧾 Dictionary

- Collection of key-value pairs
- Unordered (ordered as of Python 3.7+)
- Keys must be unique and immutable
- Values can be of any type
- Mutable (values can be updated or removed)
- Common operations: add, update, delete, iterate

---

## 🔢 Set

- Unordered collection of unique elements
- Mutable (can add or remove elements)
- Does not allow duplicates
- No indexing or slicing
- Useful for set operations like union, intersection, difference

---

## 🔤 String

- Immutable sequence of characters
- Supports indexing, slicing, and many built-in methods
- Commonly used for text processing
- Immutable (modifications return a new string)
- Often used in combination with loops and conditionals

---

## 📌 Comparison Table

| Data Structure | Ordered | Mutable | Duplicate Allowed | Unique Feature              |
|----------------|---------|---------|-------------------|-----------------------------|
| List           | Yes     | Yes     | Yes               | Dynamic, general-purpose    |
| Tuple          | Yes     | No      | Yes               | Immutable and faster        |
| Dictionary     | Yes*    | Yes     | No (keys only)    | Key-value pair structure    |
| Set            | No      | Yes     | No                | Unordered, unique elements  |
| String         | Yes     | No      | Yes               | Immutable text sequence     |

> *Note: Dictionaries preserve insertion order starting from Python 3.7.

---

## 🧠 Summary

These data structures are the building blocks of Python programming. Understanding their properties and use cases helps write cleaner, faster, and more efficient code.

---

## 🌟 Share & Star

If you find these notes useful, consider giving the repository a ⭐ and sharing it with others.

