# WEEK 1 - Python Data Processing Project

## 🚀 Project Overview
This project focuses on building a data processing module using Python, incorporating advanced features like generators, comprehensions, and object-oriented programming. The goal is to extract and analyze year-over-year revenue and revenue by region from Bamazon Inc.'s sales data spanning 2015 to 2021.

## 🧭 Learning Objectives
- Mastering Python's advanced data structures and functionalities.
- Efficiently handling and parsing large data files.
- Implementing robust testing strategies with pytest.

## 💡 Key Insights

### Python Generators and Iterators
- Explored the use of generators for memory-efficient data processing.
- Learned the significance of the `__iter__` method in creating iterable objects.

### Comprehensions in Python
- Utilized list comprehensions to simplify data manipulation and filtering tasks.

### Object-Oriented Programming
- Applied OOP principles to structure the data processing module, enhancing code modularity and reusability.

### Testing with Pytest
- Adopted pytest for writing and executing test cases, ensuring code reliability.

### Handling Large Data Files
- Investigated techniques for processing large datasets without compromising performance.

## 🛠️ Challenges and Solutions

### ModuleNotFoundError and PYTHONPATH
- Encountered issues with Python module discovery.
- Resolved by correctly setting the `PYTHONPATH` environment variable.

### Running Scripts from Different Directories
- Faced difficulties executing the main script due to directory structure.
- Overcame by adjusting the command line invocation to specify the correct module path.

### Debugging IndentationError
- Identified and fixed syntax errors that were causing script failures.

## 📊 Project Outcomes

Successfully developed and tested a Python module capable of:
- Generating insights from large datasets.
- Aggregating sales data to calculate revenue metrics.
- Producing reports including bar graphs and JSON files for data visualization.

## Commands for Running the W1 Code

### W1

# Run tests with prints
PYTHONPATH=../ pytest test.py -s
# From the parent folder
```
PYTHONPATH=./w1 pytest w1/test.py -s
```
# Run tests without prints
```
PYTHONPATH=../ pytest test.py
```
# From the parent folder
```
PYTHONPATH=./w1 pytest w1/test.py
```

# Run on `test` data
```
PYTHONPATH=../ python main.py --type tst
```
# From the parent folder
```
PYTHONPATH=./w1 python -m w1.main --type tst
```

# Run on `small` data
```
PYTHONPATH=../ python main.py --type sml
```
# From the parent folder
```
PYTHONPATH=./w1 python -m w1.main --type sml
```

# Run on the `big` data
```
PYTHONPATH=../ python main.py --type bg
```
# From the parent folder
```
PYTHONPATH=./w1 python -m w1.main --type bg
```