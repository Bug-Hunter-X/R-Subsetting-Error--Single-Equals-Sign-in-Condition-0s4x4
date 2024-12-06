# R Subsetting Bug

This repository demonstrates a common yet subtle error in R programming related to subsetting data frames. The error involves the incorrect use of the assignment operator (=) instead of the comparison operator (==) within a subsetting condition.

## Problem

The `bug.R` file contains code that attempts to subset a data frame based on a condition. However, it uses a single equals sign (=) which leads to unexpected behavior and makes the bug difficult to find. This results in an unexpected data frame that is not the intended subset.

## Solution

The `bugSolution.R` file provides the corrected code, showcasing the proper use of the double equals sign (==) for comparison within the subsetting condition.  The corrected code accurately subsets the data frame as intended.

## How to Reproduce

1. Clone this repository.
2. Open `bug.R` and run the code. Observe the unexpected output.
3. Open `bugSolution.R` and run the code. Observe the correct output.

This example highlights the importance of careful attention to detail when writing R code, particularly regarding the correct use of operators.