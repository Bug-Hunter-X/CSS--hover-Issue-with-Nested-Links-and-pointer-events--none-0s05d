# CSS :hover Issue with Nested Links and `pointer-events: none;`

This repository demonstrates a common CSS issue where the `:hover` pseudo-class behaves unexpectedly when applied to links nested within elements that have `pointer-events: none;` set.  This can lead to hover effects not being triggered correctly, impacting user experience.

The `bug.css` file contains the problematic CSS, while `bugSolution.css` provides a solution using the `pointer-events: auto;` property on the nested link.