# CSS Specificity and Inheritance Bug

This repository demonstrates a common yet sometimes subtle bug in CSS related to specificity and inheritance. The bug occurs when conflicting styles affect an element, making it difficult to predict the final rendered style.

## Bug Description
The CSS code in `bug.css` shows a scenario where the specificity of selectors and inheritance interactions lead to unexpected styling. The solution involves a more thorough understanding of how CSS specificity works and making adjustments to the selectors to achieve the desired outcome.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` (if one is provided) in a web browser.
3. Observe the rendered text color; it might not be what is intuitively expected.

## Solution
The solution is in `bugSolution.css`.  A more robust and readable method of managing specificity is showcased, ensuring the intended styling is applied predictably.