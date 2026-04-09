# ADA Lab 4: Constraint Algorithms & Pattern Matching

**Name:** Vidit Bansal\
**Roll no. -**  2401420018\
**Course Batch:** B.Tech CSE (Data Science) IBM, 2024-2028\
**Semester:** 4\
**Course/Assignment:** ADA Lab Assignment 2

## Overview
This repository contains implementations of NP-hard problem-solving strategies using Backtracking and Branch & Bound for Airline Crew Scheduling. It also includes an experimental analysis of String Matching algorithms (Naive vs KMP) simulating search engine methodologies.

## Setup
1. `python -m venv .venv`
2. Activate environment.
3. `pip install -r requirements.txt`
4. Run `jupyter lab` and open `notebooks/crew_scheduling_notebook.ipynb`

## Key Implementations
* **Crew Scheduling:** Backtracking with Branch & Bound pruning to balance workload while respecting strict time-overlap constraints.
* **String Matching:** KMP algorithm implemented to avoid redundant character comparisons in worst-case text patterns.