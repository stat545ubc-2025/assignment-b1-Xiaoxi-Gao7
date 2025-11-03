# STAT545B: Assignment B1 - Z-Score Normalization Function

## Overview

This repository holds the complete solution for STAT545B's Assignment B1. The core is a single, robust R function: `standardize_vector()`.

This function calculates **Z-Scores** for any numeric vector, transforming it into a variable with a mean of 0 and a standard deviation of 1.

## Key Features

* **Core Logic:** Takes a numeric vector and returns standardized Z-Scores.
* **Robustness:** Safely handles the critical edge case where all non-NA values are identical (standard deviation is zero).
* **Data Handling:** Calculates statistics while ignoring NAs, but preserves the original position of NAs in the final output.

## Repository Contents

* **`assignmentb1solution.Rmd`**
* **`assignmentb1solution.md`**
