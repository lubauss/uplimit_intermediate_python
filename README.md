# Intermediate Python

## Install all dependencies

- Make you're using Python version >= 3.9.0
- Install all the modules

```
pip install -r requirements.txt
```

## Generate data

Generate test data (useful for unit testing code)

```
python generate_data.py --type tst
```

Generate small data (useful for quick testing of logic)

```
python generate_data.py --type sml
```

Generate big data (actual data)

```
python generate_data.py --type bg
```

# Python Data Processing Project - Week 1 Insights

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