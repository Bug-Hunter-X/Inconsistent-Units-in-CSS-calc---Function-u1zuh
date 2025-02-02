# Inconsistent Units in CSS calc() Function

This repository demonstrates a common CSS error involving inconsistent unit usage within the `calc()` function and provides a solution.

## Bug Description
The `calc()` function in CSS is powerful for dynamic calculations, but it's crucial to use units consistently. Mixing units like percentages and pixels directly can result in incorrect calculations and unexpected layout.

## How to Reproduce
1. Open `bug.css`.
2. Observe the inconsistent unit usage in the `width` calculation.
3. Compare the result with the expected layout.

## Solution
The solution involves converting all units to a consistent type before using them in `calc()`. `bugSolution.css` shows the corrected calculation using a consistent unit.