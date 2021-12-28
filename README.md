# Challenge_5: Financial Simulations and API's

UNCC Online FinTech Bootcamp Module 5 Challenge due by 11:59pm 1/9/2022

![](Images/normal_distribution.png)

https://courses.bootcampspot.com/courses/980/files/1033388/download

---

## Background

In this Challenge, we’ve decided to start a fintech consulting firm that focuses on projects to benefit local communities. We just won our first contract with a large credit union. The project entails building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets. Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. The chief technology officer (CTO) of the credit union wants us to develop a prototype application to present at its next assembly.

---

### What's being created

We’ll create two financial analysis tools by using a single Jupyter notebook:

1. A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

 ---

## Technologies

This application is written in Python 3.7 using JupyterLab version 3.0.14.

Python libraries used:
- Pathlib: [https://docs.python.org/3.7/library/pathlib.html](https://docs.python.org/3.7/library/pathlib.html)  
  *Pathlib is a library that enables consistent input and output of files from the main app.*
 - Pandas: [https://pandas.pydata.org/pandas-docs/stable/](https://pandas.pydata.org/pandas-docs/stable/)  
    *Pandas is is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.*
 - Requests: [https://docs.python-requests.org/en/master/](https://docs.python-requests.org/en/master/)  
    *Requests is an elegant and simple HTTP library for Python, built for human beings.*
 - JSON: [https://www.json.org/json-en.html](https://www.json.org/json-en.html)  
     *JSON is a lightweight data-interchange format.*

### Installation Guide

prior to running these libraries, install them from the command line:  
  - pandas: `conda install pandas` or `pip install pandas`  
  - pathlib: `pip install pathlib`
  - requests: `python -m pip install requests`
  
---

## Usage

#### Our Jupyter Notebook will be useful in answering the following questions:


---
### Contributors

Geoff Tarleton - jobeycat@protonmail.com

adapted from Starter Code supplied by UNCC FinTech Online Bootcamp by Trilogy Educational Services, a 2U, Inc. brand.

---

### License

MIT