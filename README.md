# Mastering NumPy: Numerical Python Foundations

This repository contains my personal notes, code snippets, and project implementations while mastering **NumPy**, the fundamental package for scientific computing in Python.

---

## 🚀 About NumPy
NumPy (Numerical Python) is an open-source library that provides support for large, multi-dimensional arrays and matrices, along with a collection of high-level mathematical functions to operate on these arrays. It is the backbone of the Python Data Science ecosystem, powering libraries like Pandas, Matplotlib, and Scikit-learn.



---

## 🛠️ Key Topics Covered

### 1. Array Basics & Creation
Understanding the `ndarray` object, data types, and different ways to initialize arrays.
* Creating arrays from Python lists.
* Using `np.zeros()`, `np.ones()`, `np.full()`, and `np.eye()`.
* Generating sequences with `np.arange()` and `np.linspace()`.

### 2. Array Manipulation
Techniques for changing the structure of data without changing the data itself.
* **Reshaping:** Changing dimensions using `.reshape()`.
* **Transposing:** Swapping axes.
* **Joining:** Concatenating and stacking (`hstack`, `vstack`).
* **Splitting:** Dividing one array into multiple.

### 3. Indexing & Slicing
* Basic slicing (similar to Python lists).
* Advanced indexing: Integer array indexing and Boolean masking (filtering data).
* Multi-dimensional slicing.

### 4. Vectorization & Broadcasting
One of NumPy's most powerful features is the ability to perform element-wise operations without explicit `for` loops.
* **Broadcasting:** How NumPy treats arrays with different shapes during arithmetic operations.



---

## 💻 Code Examples

### Simple Vectorization
```python
import numpy as np

# Traditional Python approach
data = [1, 2, 3, 4, 5]
plus_ten = [x + 10 for x in data]

# NumPy vectorized approach
arr = np.array([1, 2, 3, 4, 5])
arr_plus_ten = arr + 10

print(arr_plus_ten)
```
---
## 🔧 Installation

To set up your environment and run the code in this repository, you need to install NumPy. It is recommended to use a virtual environment.

```bash
# Install NumPy via pip
pip install numpy
```
---
## 📚 Resources

Here are some essential links and documentation I used while learning:

* **[Official NumPy Documentation](https://numpy.org/doc/stable/)** – The definitive source for all NumPy functions and classes.
* **[NumPy Quickstart Guide](https://numpy.org/doc/stable/user/quickstart.html)** – A great place for beginners to see the "essential" features.
* **[NumPy Illustrated Guide](https://betterprogramming.pub/numpy-illustrated-the-visual-guide-to-numpy-3b1d79710c27)** – A highly visual way to understand how array axes and shapes work.
* **[NumPy Tutorials on GitHub](https://github.com/numpy/numpy-tutorials)** – Community-contributed tutorials and educational content.
