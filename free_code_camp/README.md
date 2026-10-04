# 🎓 freeCodeCamp Certifications

Professional certifications demonstrating proficiency in Python programming, data analysis, and scientific computing

[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-blue.svg)](../LICENSE)
[![Language](https://img.shields.io/badge/Language-Python%203.8+-green.svg)]()
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Certifications](#-certifications)
- [Technologies](#️-technologies)
- [License](#-license)

## 🎯 Overview

This repository contains projects completed while earning **freeCodeCamp certifications** in Python programming. The materials demonstrate practical skills in data analysis, scientific computing, algorithm design, and problem-solving.

All projects follow **freeCodeCamp curriculum requirements** and include test suites to validate functionality. The repository serves as a portfolio of completed certification projects and learning resources.

Each certification consists of **5 required projects** demonstrating mastery of specific Python domains, from basic programming to advanced data analysis and visualization.

## ✨ Features

- **Scientific Computing with Python** - 5 projects demonstrating OOP, algorithms, and problem-solving
- **Data Analysis with Python** - 5 projects using Pandas, NumPy, Matplotlib, and Seaborn
- **Guided Learning Codes** - 11 practice exercises covering algorithms and data structures
- **Test Suites** - All projects include unit tests validating correctness
- **Real-World Datasets** - Projects use actual demographic, medical, and time series data

## 🚀 Installation

### Prerequisites

```bash
# Python 3.8 or newer
python3 --version

# pip package manager
pip3 --version
```

### Setup

```bash
# Clone repository
git clone https://github.com/ulpati/certifications.git
cd certifications/free_code_camp

# Create virtual environment (recommended)
python3 -m venv venv
source venv/bin/activate  # Linux/macOS
# venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt
```

## 💻 Usage

### Running Projects

```bash
# Navigate to specific project
cd scientific_computing/arithmetic_formatter

# Run main script
python3 main.py

# Run tests
python3 test_module.py
```

### Running Data Analysis Projects

```bash
# Navigate to data analysis project
cd data_analysis/demographic_data_analyzer

# Run analysis
python3 main.py

# Verify results
python3 test_module.py
```

## 📁 Project Structure

```
free_code_camp/
├── README.md                          # This file
├── requirements.txt                   # Python dependencies
├── scientific_computing/              # Python programming certification
│   ├── README.md                      # Track overview
│   ├── arithmetic_formatter/          # Project 1: Format arithmetic problems
│   ├── time_calculator/               # Project 2: Add duration to time
│   ├── budget_app/                    # Project 3: Budget management OOP
│   ├── polygon_area_calculator/       # Project 4: Shape calculations
│   ├── probability_calculator/        # Project 5: Probability experiments
│   └── guided_codes/                  # 11 practice exercises
│       ├── cipher.py                  # Vigenère cipher
│       ├── luhn_algorithm.py          # Credit card validation
│       ├── password_generator.py      # Secure password generation
│       ├── tower_of_hanoi_puzzle.py   # Recursive puzzle solver
│       ├── merge_sort_algorithm.py    # Sorting algorithm
│       ├── sudoku_solver.py           # Backtracking solver
│       └── ...                        # 5 more exercises
└── data_analysis/                     # Data analysis certification
    ├── README.md                      # Track overview
    ├── mean_variance_standard_deviation_calculator/  # Project 1: NumPy statistics
    ├── demographic_data_analyzer/     # Project 2: Census data analysis
    ├── medical_data_visualizer/       # Project 3: Medical data visualization
    ├── page_view_time_series_visualizer/  # Project 4: Time series plots
    └── sea_level_predictor/          # Project 5: Linear regression prediction
```

## 🏆 Certifications

### Scientific Computing with Python

**Status**: ✅ Completed (2024)  
**Focus**: Python fundamentals, OOP, algorithms, problem-solving

#### Required Projects (5/5 completed):

1. **Arithmetic Formatter** - Vertically arrange arithmetic problems with error handling
2. **Time Calculator** - Add time duration with day-of-week calculation
3. **Budget App** - Object-oriented budget tracking with category management
4. **Polygon Area Calculator** - Rectangle and Square classes with area/perimeter methods
5. **Probability Calculator** - Simulate probability experiments with random draws

#### Guided Learning (11 exercises):

- Vigenère Cipher encryption/decryption
- Luhn Algorithm for credit card validation
- Password Generator with security requirements
- Shortest Path Algorithm graph traversal
- Tower of Hanoi recursive puzzle solver
- Merge Sort Algorithm implementation
- Sudoku Solver using backtracking
- Binary Search Tree data structure
- Expense Tracker application
- Case Converter (camelCase ↔ snake_case)

### Data Analysis with Python

**Status**: ✅ Completed (2024)  
**Focus**: Data manipulation, visualization, statistical analysis

#### Required Projects (5/5 completed):

1. **Mean-Variance-Standard Deviation Calculator** - NumPy array statistics (mean, variance, std, max, min, sum)
2. **Demographic Data Analyzer** - Census data analysis with Pandas (education, income, occupation patterns)
3. **Medical Data Visualizer** - Categorical plots and correlation heatmaps for cardiovascular data
4. **Page View Time Series Visualizer** - Line plots, bar charts, and box plots for forum analytics
5. **Sea Level Predictor** - Linear regression trend analysis with future predictions

## 🛠️ Technologies

**Core Libraries:**
- **Python 3.8+** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing and array operations
- **Matplotlib** - Data visualization and plotting
- **Seaborn** - Statistical data visualization
- **pytest** - Unit testing framework

**Concepts Covered:**
- Object-Oriented Programming (classes, inheritance)
- Data Structures (lists, dictionaries, sets)
- Algorithms (sorting, searching, recursion, backtracking)
- Statistical Analysis (mean, variance, correlation)
- Data Cleaning (outlier removal, normalization)
- Data Visualization (line plots, bar charts, box plots, heatmaps)
- Time Series Analysis
- Linear Regression

## 📄 License

This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)** - see the [LICENSE](../LICENSE) file for details.

## 🙏 Acknowledgements

- **freeCodeCamp** - For providing comprehensive, free programming education
- **freeCodeCamp Community** - For support and guidance throughout the learning process

---

**Author**: [ulpati](https://github.com/ulpati)  
**Completion Date**: 2024  
**Certification Links**:
- Scientific Computing with Python: [View Projects](./scientific_computing)
- Data Analysis with Python: [View Projects](./data_analysis)