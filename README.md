## 0. Reference Books 
   ***Python3从入门到实战***

   ***Fluent Python***

   [Python for Data Analysis](https://wesmckinney.com/book/)


## 1. Environment Setup

Why Python vs Why Not Python?

Python is an interpreted programming language, making it easy to debug and suitable for rapid development.

### Tools and Setup
- **VS Code + WSL + Ubuntu**: A powerful combination for Python development.
- **Microsoft Store**: Install Ubuntu directly from the Microsoft Store.

### Anaconda vs Miniconda
Miniconda is a lightweight alternative to Anaconda, providing just the essentials for Python package management.

#### Installation Steps:
1. Download Miniconda:
   ```bash
   wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   wget https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/Miniconda3-latest-Linux-x86_64.sh
   bash Miniconda3-latest-Linux-x86_64.sh

   source /opt/miniconda3/bin/activate
   conda init 
   conda info -e
   ```

2. setup isolated environment:
   ```bash
   conda create -n pydata
   conda activate pydata
   ```


## 2. Python Core Concept 
   ```bash
   1 Data Types (Strings/Numbers/Booleans)
   2 Data Structures (Lists/Tuples/Sets/Dictionaries)
   3 Control Statements (If/Loop)
   4 Functions 
   5 Input and Output 
   6 Try/Catch/Finally 
   7 Object Programming 
   8 import/package/module 
   ```


## 3. NumPy and Pandas
   ```bash
   pandas vs polars vs dask
   ```

## 4. Data Loading and Storage 
   ```bash
   files: csv/excel/pdf/xml/json
   database: postgresql
   ```

## 5. Data Visualization 
   ```bash
   (Add content here) 
   ```

## 6. Practice
   ```bash
   (Add content here) 
   ```