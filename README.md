# CSS `calc()` Unexpected Behavior

This repository demonstrates a common issue encountered when using the `calc()` function in CSS, specifically when combining percentages and fixed units (like pixels or ems).  In some browsers, the expected layout isn't rendered correctly, potentially leading to unexpected behavior and layout issues.  This example highlights the problem and offers a solution.

## Files

- `bug.css`: Contains the CSS code demonstrating the buggy behavior.
- `bugSolution.css`: Provides a solution to mitigate the issue.

## How to reproduce the problem

1.  Open `bug.html` (which is linked to `bug.css`) in various browsers. 
2.Observe the unexpected layout differences.