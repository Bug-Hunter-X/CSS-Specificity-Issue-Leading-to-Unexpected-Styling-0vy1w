# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity issues.  A more specific selector unintentionally overrides a less specific one, leading to unexpected styling behavior. The `bug.css` file contains the erroneous code, while `bugSolution.css` provides the corrected version.

## Problem

The original CSS has a specificity conflict. The more specific selector overrides the intended style.  This often occurs when using IDs, classes, and element selectors together without understanding the specificity rules.

## Solution

The solution involves carefully reviewing the CSS selectors, understanding the rules of specificity, and potentially adjusting selectors to ensure the styles are applied correctly.

## How to reproduce

1. Clone the repository.
2. Open `bug.html` in a browser (you may need to create this simple HTML). 
3. Observe the unexpected styling.
4. Replace `bug.css` with `bugSolution.css` and refresh. 
5. Observe the corrected styling.