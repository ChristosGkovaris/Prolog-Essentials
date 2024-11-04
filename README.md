# Prolog Utility Functions

Welcome to the "Prolog Utility Functions" repository, a collection of useful functions implemented in Prolog. These functions cover various tasks such as mathematical computations, list manipulations, and data processing.

## Functions Overview

### Recursive Function
- **Function:** `f(0, X, Y, Res)`
- **Objective:** Calculate a value based on the inputs.  
- **Example:** `f(0, X, Y, Res)` returns `Res is (Y + 1)`.

### Helper Function for Conditional Logic
- **Function:** `f(A, B, I, Res)`  
- **Objective:** Perform calculations based on conditions and helper logic.  
- **Example:** Use in various calculations, where `helper/4` facilitates the process.

### Sum of Digits
- **Function:** `sum_of_digits(N, Res)`  
- **Objective:** Calculate the sum of the digits of a number.  
- **Example:** `sum_of_digits(123, Res)` returns `Res is 6`.

### Generate List
- **Function:** `generate_list(M, N, L)`  
- **Objective:** Generate a list of integers from M to N.  
- **Example:** `generate_list(1, 5, L)` returns `L = [1, 2, 3, 4, 5]`.

### Generate Arithmetic Progression
- **Function:** `generate_list_ap(N, M, K, L)`  
- **Objective:** Generate a list of an arithmetic progression.  
- **Example:** `generate_list_ap(3, 1, 2, L)` returns `L = [1, 3, 5]`.

### Insert at Position
- **Function:** `insertAt(X, N, L, S)`  
- **Objective:** Insert an element at a specified position in a list.  
- **Example:** `insertAt(10, 2, [1, 2, 3], S)` returns `S = [1, 10, 2, 3]`.

### Insert After Element
- **Function:** `insertAfter(X, Y, L, S)`
- **Objective:** Insert an element after a specified value in a list.
- **Example:** `insertAfter(10, 2, [1, 2, 3], S)` returns `S = [1, 2, 10, 3]`.

### Insert New Element
- **Function:** `insertNew(X, L, S)`  
- **Objective:** Insert a new element into a list without duplicates.  
- **Example:** `insertNew(2, [1, 2, 3], S)` returns `S = [1, 2, 3]`.

### Delete K-th Element
- **Function:** `deleteK(X, K, L, S)`  
- **Objective:** Delete the k-th occurrence of an element from a list.  
- **Example:** `deleteK(2, 1, [1, 2, 2, 3], S)` returns `S = [1, 2, 3]`.

### Delete N-th Occurrence
- **Function:** `deleteN(X, N, L, S)`
- **Objective:** Delete the N-th occurrence of a specific element from a list.  
- **Example:** `deleteN(2, 1, [1, 2, 2, 3], S)` returns `S = [1, 2, 3]`.

### Integral Calculation
- **Function:** `integral(F, A, B, D, Res)`  
- **Objective:** Calculate the integral of a function using the trapezoidal rule.  
- **Example:** Use for numerical integration tasks.

## Implementation Details
- The functions are implemented in Prolog and are designed to handle various tasks related to numerical computations and list manipulations.

## How to Run
- **Clone the Repository:**
  ```bash
     git clone https://github.com/ChristosGkovaris/Prolog-Essentials.git
     cd Prolog-Essentials
