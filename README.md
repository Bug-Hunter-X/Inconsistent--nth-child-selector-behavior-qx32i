# Inconsistent :nth-child selector behavior

This repository demonstrates a problem with the CSS `:nth-child(n)` selector. The expected behavior is to highlight every other list item, however, the implementation shows inconsistent results.  The bug.css file contains the problematic CSS, while bugSolution.css offers a potential fix.

## Setup
1. Clone this repository.
2. Open `index.html` in your web browser.

## Problem
The `:nth-child(even)` selector is not consistently highlighting every other list item. This could be due to other CSS rules, unintended HTML structure, or an unexpected browser behavior. This is a good example of a subtle issue that can be hard to identify and debug in CSS.  Check the `bug.css` file to see the code. 