---
title: Python, how to concatenating two lists
date: "2020-07-04T10:12:03.284Z"
tags: ['python', 'beginners']
published: true
---

## Introduction

A list is a collection which is ordered and changeable. In Python lists are written with square brackets. For declaring a list in Python you have to use the following code

```python
list_name = ['banana', 'apple']
```

You can access the list item by referring to the index number. Remember that the first element has index zero:
```python
list_name = ['banana', 'apple']
print(list_name[1])
# Output: apple
```

Lists in Python can be concatenated in two ways:

- Using + operator
- Using extend

First of all declare the lists as below:

```python
list_a = [1, 2, 3]
list_b = [4, 5, 6]
```

## Use the "+" operator to concatenate two list

We can use the "+" operator to concatenate two lists in Python:

```python
list_c = list_a + lis_b
print(list_c)
# Output: [1, 2, 3, 4, 5, 6]
```

## Use the "extend" operator to concatenate two list

We can use the "extend" operator to concatenate the two lists in Python:

```python
list_a.extend(list_b)
print(list_a)
# Output: [1, 2, 3, 4, 5, 6]
```

With the extend operator python the first list will be modified. It is not possible to store the value into the third list.

## What is the best solution to concatenate two lists in python?

There is not much difference in performance. The "+" operators is just a little bit fast, but we will not notice it until we will concatenate very long lsit - thousands of elements per list
