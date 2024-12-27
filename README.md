# CSS Float and Width Issue

This repository demonstrates a common CSS issue related to floating elements and width percentages.  When using `float: left` and `width: 50%` without specifying the parent container's width, the divs might not render correctly. This is due to the fact that browsers calculate the percentage width relative to the parent's actual rendered width.  If the parent's width is not specified, it might be smaller than expected due to its content.

The `bug.css` file shows the problematic code, while `bugSolution.css` provides a solution.