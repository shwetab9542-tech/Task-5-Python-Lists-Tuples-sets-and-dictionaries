# Python Lists, Tuples, Sets and Dictionaries

## Task Description

This project demonstrates the use of Python's four important collection data structures:

* Lists
* Tuples
* Sets
* Dictionaries

The programs perform common operations such as adding, removing, searching, updating, and sorting elements.

## Objective

The main objective of this task is to develop practical skills in handling structured data using Python collection data structures.

## Tools Used

* Python
* Jupyter Notebook

## Collection Types Covered

### 1. Lists

Lists are ordered and mutable collections that can store multiple values and allow duplicate elements.

**Operations demonstrated:**

* `append()`
* `remove()`
* `sort()`
* Searching using `in`
* Updating elements

**Example:**

```python
marks = [85, 72, 90, 65, 88]
marks.append(95)
marks.remove(65)
marks.sort()
```

### 2. Tuples

Tuples are ordered and immutable collections. Once created, their elements cannot be changed.

**Operations demonstrated:**

* Accessing elements using indexes
* Searching using `in`
* `count()`
* `index()`

**Example:**

```python
employee = ("E101", "Rahul", "Data Analyst", 35000)

print(employee[1])
print("Data Analyst" in employee)
```

### 3. Sets

Sets are unordered collections that store only unique elements. They are useful when duplicate values need to be removed.

**Operations demonstrated:**

* `add()`
* `remove()`
* `update()`
* Searching using `in`
* Removing duplicate values

**Example:**

```python
student_ids = [101, 102, 101, 103, 102]
unique_ids = set(student_ids)

print(unique_ids)
```

### 4. Dictionaries

Dictionaries store information in key-value pairs. Values can be accessed and updated using their keys.

**Operations demonstrated:**

* Accessing values using keys
* Adding key-value pairs
* Updating values
* Removing values using `pop()`
* Searching for keys

**Example:**

```python
employee = {
    "id": 101,
    "name": "Priya",
    "department": "Data Science",
    "salary": 45000
}

employee["salary"] = 50000
employee["experience"] = 2
```

## Dataset Used

The examples use simple **Student** and **Employee** data.

### Student Dataset

The student data contains:

* Student ID
* Student Name
* Marks

Example:

```python
students = [
    {"id": 1, "name": "Amit", "marks": 85},
    {"id": 2, "name": "Sneha", "marks": 92},
    {"id": 3, "name": "Rahul", "marks": 78}
]
```

### Employee Dataset

The employee data contains:

* Employee ID
* Employee Name
* Department
* Salary
* Experience

## Comparison

| Feature       | List               | Tuple      | Set           | Dictionary      |
| ------------- | ------------------ | ---------- | ------------- | --------------- |
| Ordered       | Yes                | Yes        | No            | Yes             |
| Mutable       | Yes                | No         | Yes           | Yes             |
| Duplicates    | Allowed            | Allowed    | Not allowed   | Keys are unique |
| Access Method | Index              | Index      | Membership    | Key             |
| Main Purpose  | General collection | Fixed data | Unique values | Key-value data  |

## Conclusion

This project provides practical experience with Python's fundamental collection data structures. Lists, tuples, sets, and dictionaries are widely used in data science for storing, organizing, and processing structured data. The examples demonstrate their common operations and practical use with student and employee datasets.
