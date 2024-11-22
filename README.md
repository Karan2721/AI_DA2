# DIGITAL ASSIGNMENT - 2

**NAME**: Karan Dugar  
**REG. NUMBER**: 22BCI0189  
**COURSE**: Artificial Intelligence – BCSE306L  
**FACULTY**: Prof. Saravanaguru Ra.K  

---

## Project Overview

This repository contains solutions for **Digital Assignment - 2** of the Artificial Intelligence course. The tasks involve implementing three AI-related systems:

1. **8-Puzzle Problem Solver using Hill Climbing Algorithm**  
2. **Student Eligibility Checker with Prolog and REST API**  
3. **Monte Carlo Simulation for Bayesian Belief Network Inference**

---

## Task Descriptions and Usage

### 1. 8-Puzzle Problem Solver
- Implements the **Hill Climbing Algorithm** to solve the 8-puzzle problem.
- Demonstrates algorithm limitations such as **local maxima** and **plateaus**.
- **Usage**:
  - Modify `initial_state` in the code.
  - Run the script to display results and paths for different test cases.

### 2. Student Eligibility Checker
- **Prolog-based system** to determine student eligibility for scholarships and exam permissions based on attendance and CGPA.
- **REST API**:
  - Load data dynamically from `data.csv`.
  - Query eligibility of specific/all students.
- **Usage**:
  - Run the Prolog code and start the HTTP server.
  - Test using browser/Postman at:
    - `http://localhost:8080/check?id=<Student_ID>`
    - `http://localhost:8080/check`

### 3. Monte Carlo Simulation for Bayesian Belief Network
- Solves inference problems using **Monte Carlo Simulation** on a Bayesian Belief Network.
- Demonstrates how sample size affects accuracy.
- **Usage**:
  - Define the Bayesian network structure in the script.
  - Run the script to compute probabilities for selected nodes.

---

## Example
- **Input for Eligibility Checker (data.csv)**:
  ```csv
  Student_ID,Name,Attendance,CGPA
  101,John,80,9.2
  102,Alice,70,8.5
