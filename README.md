# Test Score Calculator (LC-3 Assembly)

## Overview

This is a simple program written in LC-3 Assembly that lets a user enter 5 test scores between 0 and 100. After entering the scores, it calculates and displays the **minimum**, **maximum**, and **average** score, along with a corresponding **letter grade (A–F)** for each result.

It was made by our group, **The Squad**, as a way to get more comfortable with LC-3 programming and stack usage.

## How It Works

The program follows these main steps:

1. **Initialize the stack**
2. **Ask the user to input 5 scores**
3. **Find the minimum and maximum**
4. **Calculate the average**
5. **Display results**, including grades for min, max, and average

All of this happens through subroutines and memory-mapped I/O (like GETC and PUTS) to interact with the user.

## Features

- Score input (supports two-digit entry from the keyboard)
- Calculates:
  - Minimum score
  - Maximum score
  - Average score (uses repeated subtraction to divide)
- Displays letter grades based on:
  - A: 90–100
  - B: 80–89
  - C: 70–79
  - D: 60–69
  - F: <60

## How to Run It

1. Load the program into the **LC-3 Simulator** (like LC3Edit or PennSim).
2. Assemble and run the code starting at address `x3000`.
3. Follow the prompts to enter 5 scores (e.g., type `82` when asked).
4. The program will show the min, max, and average, along with letter grades.

> Make sure you're inputting 2-digit scores one digit at a time, as the program reads characters using `GETC`.

## Files Included

- `test_score_calculator.asm` — the full LC-3 source code
- `README.md` — this file

## Author(s)

The Squad (student project team)

