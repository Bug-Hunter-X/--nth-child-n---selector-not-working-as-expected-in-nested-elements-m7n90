# :nth-child(n) Selector Issue in Nested Elements

This repository demonstrates a problem with the CSS `:nth-child(n)` selector when used with nested elements. The selector doesn't behave as expected when targeting a specific child within a nested structure.

## Problem Description
The `:nth-child(n)` selector, when applied to nested elements, does not correctly calculate the index based on the nested hierarchy. It considers the index based on all direct children of the parent element, even if there is nested structure between the parent and the target element.

## Steps to reproduce
1. Clone this repository.
2. Open `bug.css` and `bugSolution.css`.
3. Notice the issue of unexpected styles in `bug.css` and the corrected styling in `bugSolution.css`. 

## Solution
The solution involves using more specific selectors to target the desired nested elements. Using child combinators and other techniques ensures accurate selection. See `bugSolution.css` for detailed solutions.