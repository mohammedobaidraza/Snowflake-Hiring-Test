# Snowflake Hiring Test Solutions

This repository contains solutions to various computational and algorithmic challenges designed for a Snowflake hiring test. The notebook addresses problems across different domains, including chemistry, optimization, and string manipulation.

## Notebook Overview

The notebook includes the following problem solutions:

### 1. Balancing Chemical Equations
A function designed to balance a chemical equation by parsing the reactants and products, identifying unique elements, setting up a system of linear equations, and solving them. The function uses symbolic computation to provide integer coefficients that represent the balanced form of the equation.

#### Example Usage:
```python
# Input
chemical_equation = "H2 + O2 -> H2O"
result = balanceEquation(chemical_equation)
print(result)  # Outputs balanced coefficients, e.g., "2 1 2"
```

### 2. Maximum Server Upgrades
This function calculates the maximum number of servers that can be upgraded based on available resources. It considers parameters such as the number of servers, available money, server sale price, and the cost to upgrade. The function returns the maximum number of upgrades possible for each server network.
#### Example Usage:
``` python
# Inputs
num_servers = [4, 3]
money = [8, 9]
sell = [4, 2]
upgrade = [4, 5]
print(getMaxUpgradedServers(num_servers, money, sell, upgrade))
# Expected Output: [3, 2]
```

### 3. Target String Formation
A dynamic programming solution to find the number of ways to form a target string using characters from a list of words. It constructs a frequency table for each character position and calculates possible formations of the target string.

#### Example Usage:
``` python
# Inputs
words = ["valya", "lyglb", "vldoh"]
target = "val"
print(numWays(words, target))  # Outputs the number of ways to form the target
``` 

### Folder Structure
snowflake_Test.ipynb: Jupyter notebook containing all the solutions.
README.md: Overview of the project and instructions.

