# 🐍 Python List Manipulation

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## 📋 Project Overview

This repository contains a Python script designed to demonstrate advanced list manipulation techniques. It showcases the versatility of Python's built-in list data structure by performing a sequence of CRUD (Create, Read, Update, Delete) operations, sorting algorithms, and index querying.

This script serves as a concise reference for handling dynamic arrays in Python 3.

---

## 🔧 Technologies Used

* **Python 3.x** - Core programming language.

---

## 🚀 Key Operations Demonstrated

The script systematically performs the following logic flow:

1.  **Initialization:** Creating an empty dynamic list.
2.  **Appends:** Populating the list with initial integer data (`10`, `20`, `30`, `40`).
3.  **Insertion:** Injecting values at specific index positions (inserting `15` at index `1`).
4.  **Extension:** Merging another list (`[50, 60, 70]`) into the existing structure.
5.  **Deletion:** Removing the last element using the stack-like `.pop()` method.
6.  **Sorting:** Reordering the list in ascending order.
7.  **Querying:** locating the specific index of a target value (`30`).

---

## 📂 Project Structure

```text
week-2-my-list-python-assignment/
│
├── my_list.py      # Main script containing the list logic
└── README.md       # Documentation

---

## 🏃‍♂️ How to Run

### 1. Clone the Repository
```bash
git clone [https://github.com/Cynthia-M-M/week-2-my-list-python-assignment.git](https://github.com/Cynthia-M-M/week-2-my-list-python-assignment.git)

```

### 2. Navigate to the Folder

```bash
cd week-2-my-list-python-assignment

```

### 3. Run the Script

```bash
python my_list.py

```

---

## 💻 Code Preview

Here is the core logic implemented in `my_list.py`:

```python
# 1. Create an empty list
my_list = []

# 2. Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# 3. Insert value 15 at index 1
my_list.insert(1, 15)

# 4. Extend the list
my_list.extend([50, 60, 70])

# 5. Remove the last element
my_list.pop()

# 6. Sort the list
my_list.sort()

# 7. Find and print the index of 30
index_of_30 = my_list.index(30)
print(f"The index of 30 is: {index_of_30}")
print(f"Final List: {my_list}")

```

---

## 📊 Expected Output

When you run the script, the console should display:

```text
The index of 30 is: 3
Final List: [10, 15, 20, 30, 40, 50, 60]

```

---

## 📄 License

This project is open-source and created for educational purposes.

```

```
