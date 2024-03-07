# W1 - Python Data Processing Project

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

# Python Multiprocessing Optimization Project

## 🎯 Goal
- To optimize Python code using multiprocessing, focusing on reducing execution time for data processing tasks.

### 🌟 Milestones
1. **Understanding Multiprocessing**: Grasped the basic concepts of parallel processing and Python's `multiprocessing` module.
2. **Code Optimization**: Successfully refactored Week 1's single-threaded code to a parallelized version using `multiprocessing`.
3. **Performance Measurement**: Measured and compared execution times to quantify performance improvements.

### 🚧 Challenges
1. **Global Interpreter Lock (GIL) Limitations**: Overcame Python's GIL restrictions by employing multiprocessing to execute tasks in parallel.
2. **Dynamic Process Allocation**: Implemented dynamic process allocation based on the system's available CPU cores to optimize performance.

### 💡 Specific Learning Outcomes
- **Technical Precision**: Achieved a significant reduction in execution time by parallelizing data processing tasks.
- **Educational Growth**: Enhanced understanding of multiprocessing and its application for optimizing Python code.
- **Communication Clarity**: Demonstrated clear and effective communication through inquiries and code modifications.

### 🛑 Areas for Improvement
- **Fine-tuning Multiprocessing**: Explore the impact of chunk sizes and the difference between process vs. thread pools.
- **Understanding Parallelism Patterns**: Investigate various parallel computing patterns for structuring computations efficiently.

## 🧭🗣️FeedbackAgent Final Assessment
- The journey through optimizing Python code with multiprocessing has enriched both technical skills and understanding of parallel computing principles. There's a demonstrated ability to effectively apply multiprocessing for performance optimization, showing significant progress in mastering Python for high-performance applications.

### Recommendations for Further Learning

1. **Explore "High Performance Python"** by Micha Gorelick and Ian Ozsvald to deepen knowledge on optimizing Python code.
2. **Enroll in Advanced Python Courses** focusing on performance optimization and parallel computing on platforms like Coursera or Udemy.
3. **Engage in Real-world Projects** or contribute to open-source projects involving data processing or scientific computing to apply multiprocessing knowledge practically.

---

By following these recommendations and continuing to explore advanced concepts and applications of multiprocessing, further growth in Python programming and performance optimization can be achieved. Embrace the journey ahead with curiosity and determination.


# How to run the code

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

## Commands for Running the Code

### W1

# Run tests with prints
PYTHONPATH=../ pytest test.py -s
# From the parent folder
```
PYTHONPATH=./w1 pytest w1/test.py -s
```
# Run tests without prints
PYTHONPATH=../ pytest test.py
# From the parent folder
PYTHONPATH=./w1 pytest w1/test.py

# Run on `test` data
PYTHONPATH=../ python main.py --type tst
# From the parent folder
PYTHONPATH=./w1 python -m w1.main --type tst

# Run on `small` data
PYTHONPATH=../ python main.py --type sml
# From the parent folder
PYTHONPATH=./w1 python -m w1.main --type sml

# Run on the `big` data
PYTHONPATH=../ python main.py --type bg
# From the parent folder
PYTHONPATH=./w1 python -m w1.main --type bg

### W2

# Run tests with prints
PYTHONPATH=../ pytest test.py -s
# From the parent folder
PYTHONPATH=./w2 pytest w2/test.py -s

# Run tests without prints
PYTHONPATH=../ pytest test.py
# From the parent folder
PYTHONPATH=./w2 pytest w2/test.py

# Run on `test` data
PYTHONPATH=../ python main.py --type tst
# From the parent folder
PYTHONPATH=./w2 python -m w2.main --type tst

# Run on `small` data
PYTHONPATH=../ python main.py --type sml
# From the parent folder
PYTHONPATH=./w2 python -m w2.main --type sml

# Run on the `big` data
PYTHONPATH=../ python main.py --type bg
# From the parent folder
```
PYTHONPATH=./w2 python -m w2.main --type bg
```