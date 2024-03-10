# WEEK 2 - Python Multiprocessing Optimization Project

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

### How to Run the Code

# Run tests with prints
```
PYTHONPATH=../ pytest test.py -s
```
# From the parent folder
```
PYTHONPATH=./w2 pytest w2/test.py -s
```
# Run tests without prints
```
PYTHONPATH=../ pytest test.py
```
# From the parent folder
```
PYTHONPATH=./w2 pytest w2/test.py
```

# Run on `test` data
```
PYTHONPATH=../ python main.py --type tst
```
# From the parent folder
``````
PYTHONPATH=./w2 python -m w2.main --type tst
``````

# Run on `small` data
```
PYTHONPATH=../ python main.py --type sml
```
# From the parent folder
```
PYTHONPATH=./w2 python -m w2.main --type sml
```

# Run on the `big` data
```
PYTHONPATH=../ python main.py --type bg
```
# From the parent folder
```
PYTHONPATH=./w2 python -m w2.main --type bg
```
# Start FastAPI server
````
PYTHONPATH=.. uvicorn server:app --workers 2
````