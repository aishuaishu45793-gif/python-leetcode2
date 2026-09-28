# 🐍 Python LeetCode Practice

Welcome to my **Python LeetCode Practice Repository** 🚀

This repository contains my Python programming practice and LeetCode problem-solving journey.

I am starting with **basic Python concepts** and gradually moving toward **Data Structures and Algorithms (DSA)** and more advanced LeetCode problems.

---

## 🎯 Objective

The main objectives of this repository are:

* Learn Python programming.
* Improve logical thinking.
* Practice coding problems.
* Learn Data Structures and Algorithms.
* Solve LeetCode problems.
* Understand different problem-solving approaches.
* Improve time and space complexity knowledge.
* Prepare for coding interviews.
* Track my programming progress.

---

# 📚 Topics Covered

### 🟢 Beginner Python

* Hello World
* Variables
* Data Types
* Input and Output
* Operators
* Type Conversion
* Conditional Statements
* `if`, `elif`, `else`
* `for` loops
* `while` loops
* Nested loops

### 🟡 Intermediate Python

* Functions
* Strings
* Lists
* Tuples
* Sets
* Dictionaries
* List Comprehension
* Lambda Functions
* Exception Handling
* File Handling
* Modules

### 🔵 DSA

* Arrays
* Strings
* Hashing
* Two Pointers
* Sliding Window
* Stack
* Queue
* Linked List
* Binary Search
* Sorting
* Trees
* Binary Search Tree
* Graphs
* Recursion
* Backtracking
* Greedy Algorithms
* Dynamic Programming

### 🔴 LeetCode

This repository will contain solutions to LeetCode problems from easy to advanced difficulty.

---

# 🛠️ Technologies Used

* **Python 3**
* **Visual Studio Code**
* **Git**
* **GitHub**
* **LeetCode**

---

# 🚀 How to Create the Project

## Step 1: Install Python

Check whether Python is installed:

```bash
python --version
```

Example:

```text
Python 3.x.x
```

---

## Step 2: Create a Folder

Create a project folder:

```text
python-leetcode2
```

Open the folder in **VS Code**.

---

## Step 3: Create Python Files

Example:

```text
python-leetcode2/
│
├── README.md
│
├── 01_hello_world.py
├── 02_variables.py
├── 03_data_types.py
├── 04_input_output.py
├── 05_operators.py
├── 06_if_else.py
├── 07_loops.py
├── 08_functions.py
├── 09_strings.py
├── 10_lists.py
└── ...
```

---

# 💻 Example Python Program

### Variables

```python
name = "Aishwarya"
age = 21
course = "Python"

print("Name:", name)
print("Age:", age)
print("Course:", course)
```

### Output

```text
Name: Aishwarya
Age: 21
Course: Python
```

---

# 🔢 Example LeetCode Problem

## Two Sum

Given an array of integers and a target value, find the indices of two numbers whose sum equals the target.

### Python Solution

```python
class Solution:
    def twoSum(self, nums, target):
        for i in range(len(nums)):
            for j in range(i + 1, len(nums)):
                if nums[i] + nums[j] == target:
                    return [i, j]


solution = Solution()

nums = [2, 7, 11, 15]
target = 9

print(solution.twoSum(nums, target))
```

### Output

```text
[0, 1]
```

---

# 🧩 How It Works

My learning process follows this order:

```text
Python Basics
      ↓
Variables & Data Types
      ↓
Input & Output
      ↓
Conditions
      ↓
Loops
      ↓
Functions
      ↓
Strings
      ↓
Lists & Arrays
      ↓
Dictionaries
      ↓
Hashing
      ↓
Two Pointers
      ↓
Sliding Window
      ↓
Stack & Queue
      ↓
Linked List
      ↓
Binary Search
      ↓
Trees
      ↓
Graphs
      ↓
Recursion
      ↓
Backtracking
      ↓
Greedy
      ↓
Dynamic Programming
      ↓
Advanced LeetCode
```

---

# ▶️ How to Run the Programs

Open the project folder in VS Code.

Open the terminal:

```bash
python filename.py
```

For example:

```bash
python 02_variables.py
```

You can also click **Run Python File** in VS Code.

---

# 🧠 Problem-Solving Method

For every coding problem, I follow these steps:

1. Read and understand the problem.
2. Identify the input.
3. Identify the expected output.
4. Think about possible approaches.
5. Write the Python solution.
6. Test the solution.
7. Check edge cases.
8. Analyze time complexity.
9. Analyze space complexity.
10. Save the solution to GitHub.

---

# 📁 Suggested Folder Structure

As the repository grows, I will organize the problems by topic:

```text
python-leetcode2/
│
├── 01_python_basics/
│
├── 02_variables/
│
├── 03_conditions/
│
├── 04_loops/
│
├── 05_functions/
│
├── 06_strings/
│
├── 07_lists/
│
├── 08_dictionaries/
│
├── 09_hashing/
│
├── 10_two_pointers/
│
├── 11_sliding_window/
│
├── 12_stack/
│
├── 13_queue/
│
├── 14_linked_list/
│
├── 15_binary_search/
│
├── 16_sorting/
│
├── 17_trees/
│
├── 18_graphs/
│
├── 19_recursion/
│
├── 20_backtracking/
│
├── 21_greedy/
│
└── 22_dynamic_programming/
```

---

# 📊 Practice Problems

Some of the problems I am practicing include:

| Problem                         | Topic                 |
| ------------------------------- | --------------------- |
| Hello World                     | Python Basics         |
| Variables                       | Python Basics         |
| Data Types                      | Python Basics         |
| Even or Odd                     | Conditions            |
| Multiplication Table            | Loops                 |
| Factorial                       | Functions / Recursion |
| Palindrome Number               | Strings / Math        |
| Two Sum                         | Arrays / Hashing      |
| Fizz Buzz                       | Loops                 |
| Best Time to Buy and Sell Stock | Arrays                |
| Contains Duplicate              | Hashing               |
| Valid Anagram                   | Strings / Hashing     |
| Binary Search                   | Searching             |
| Reverse Linked List             | Linked List           |
| Valid Parentheses               | Stack                 |

---

# 📈 Progress

* [x] Python Basics
* [x] Variables
* [x] Data Types
* [ ] Input and Output
* [ ] Conditions
* [ ] Loops
* [ ] Functions
* [ ] Strings
* [ ] Lists
* [ ] Dictionaries
* [ ] Hashing
* [ ] Two Pointers
* [ ] Sliding Window
* [ ] Stack
* [ ] Queue
* [ ] Linked List
* [ ] Binary Search
* [ ] Sorting
* [ ] Trees
* [ ] Graphs
* [ ] Recursion
* [ ] Backtracking
* [ ] Greedy
* [ ] Dynamic Programming
* [ ] Advanced LeetCode

---

# 🔧 Git and GitHub

After creating or updating Python programs:

```bash
git add .
```

Commit the changes:

```bash
git commit -m "Add more Python LeetCode practice"
```

Push the changes:

```bash
git push
```

For the first push:

```bash
git branch -M main
git remote add origin https://github.com/aishuaishu45793-gif/python-leetcode2.git
git push -u origin main
```

---

# 🌱 What I Am Learning

Through this repository, I am developing skills in:

* Python programming
* Problem solving
* Logical thinking
* Data Structures
* Algorithms
* Debugging
* Time complexity
* Space complexity
* Git
* GitHub
* LeetCode

---

# 🎓 Learning Journey

This repository represents my journey from **Python beginner to advanced problem solving**.

I will continue adding new programs and LeetCode solutions as I learn new concepts.

The goal is to practice consistently and improve step by step.

---

# 👩‍💻 Author

**Aishwarya**

Python & LeetCode Practice

---

# ⭐ Goal

```text
Learn
  ↓
Practice
  ↓
Solve
  ↓
Understand
  ↓
Improve
  ↓
Repeat 🚀
```

**Keep Coding! 💻🐍**
