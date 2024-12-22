# Unexpected Behavior in CSS calc() function
This repository demonstrates a common yet easily overlooked error when using the `calc()` function in CSS. The problem stems from incorrect spacing and mixing incompatible units within the calculation.

## Bug Report
The primary issue lies in how spaces are handled within the `calc()` function and attempting to combine incompatible units.

* **Incorrect Spacing:** Missing or extra spaces in `calc()` can cause unexpected results or even parse errors. 
* **Incompatible Units:** Combining percentage and pixel units improperly can lead to incorrect computations.  

## Solution
The solution involves carefully reviewing the spacing and ensuring compatible unit usage within `calc()` expressions.

See `bugSolution.css` for the correct implementation.