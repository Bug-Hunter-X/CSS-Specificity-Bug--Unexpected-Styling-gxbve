# CSS Specificity Bug
This repository demonstrates a subtle bug related to CSS selector specificity. The problem arises from the interaction between class selectors, ID selectors, and attribute selectors.  Understanding CSS specificity is crucial for avoiding these types of unexpected styling issues.

## Bug Description
The `bug.css` file contains CSS rules that conflict in terms of specificity. This leads to unexpected styling, where the intended style is not applied.

## Solution
The `bugSolution.css` file provides a corrected version of the CSS, addressing the specificity issue by adjusting the selectors to ensure the desired styles are applied correctly.

## How to reproduce the bug
1. Create an HTML file (e.g., `index.html`) with elements matching the selectors in `bug.css`
2. Include `bug.css` in your HTML file.
3. Observe that the styling does not match the intended style due to the specificity conflict.

## How to view the solution
1. Replace `bug.css` with `bugSolution.css` in your HTML file.
2. Refresh the page to see the correct styling applied.